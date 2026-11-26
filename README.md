# Emilio Jr. B. Ogardo — Portfolio

A responsive, static portfolio website for internship / OJT applications. It uses semantic HTML5, CSS3, and vanilla JavaScript with no framework or build step.

## Run locally in VS Code

1. Open this folder in VS Code.
2. Open `index.html` in a browser, or install the **Live Server** extension and choose **Go Live**.
3. Replace the placeholders for the university, academic year, email address, profile photo, and project screenshots.
4. Add your real PDF resume at `assets/resume.pdf`. The existing Download resume button will then work automatically.

## Add your images

The project cards currently use CSS artwork as honest placeholders. To use real screenshots, add image files inside `images/` and replace the project image blocks in `index.html` with `<img>` elements that include descriptive `alt` text. You can also replace the hero avatar placeholder with your profile photo.

## Contact form

The form is intentionally frontend-only. It shows a confirmation message but does not send email. Connect it to a backend, Formspree, Netlify Forms, or another service before using it as a live contact channel.

## Publish with GitHub Pages

1. Create a GitHub repository and push all files in this folder to its default branch.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
4. Wait for the deployment to finish. Your site will be available at `https://<your-username>.github.io/<repository-name>/`.

Because this is a static site with relative paths, it is compatible with GitHub Pages without additional configuration.
