# Practical Work II - Fundamentals of Computer Engineering

## 1. Description
This project consists of the development of a personal web application as part of the "Fundamentals of Computer Engineering" course. The main objective was to transform a simple web page into a multi-page site, implementing a coherent structure, global styles using CSS, and version control with Git and GitHub.

The website includes:
- **Home:** An interactive dashboard/index.
- **About Me:** Personal profile, CV download, and photo gallery.
- **Degree:** A detailed table of the Computer Engineering curriculum.
- **Net:** A network page linking to classmates' projects.
- **FCE:** Specific information about the Fundamentals of Computer Engineering subject.
- **Topic:** A page discussing the future of technology and AI.
- **Contact:** A functional HTML form.

## 2. Problems Encountered
During the development of this practice, I faced several challenges:
1. **CSS Linking:** Initially, the pages inside the `pages/` folder did not load the styles correctly. I solved this by understanding relative paths and changing the link to `../css/styles.css`.
2. **Folder Structure:** Organizing the files so that the `index.html` remained in the root while the other sections were in `pages/` required careful management of links (`href="../index.html"` vs `href="pages/about.html"`).
3. **GitHub Pages Updates:** Sometimes changes pushed to GitHub took time to reflect on the live site, which caused confusion regarding whether the code was correct.

## 3. Conclusions
This practical work has been essential to understand the workflow of a modern developer. I have learned:
- The importance of **Git** for tracking changes and the "Atomic Commit" philosophy.
- How to structure a web project professionally (separating HTML, CSS, and assets).
- The use of **GitHub Pages** for deployment.
- How to create a consistent user experience across multiple HTML files using a single CSS stylesheet.

Overall, this project has laid the foundation for my future web development tasks.