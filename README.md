# William Denault academic website

This is a plain HTML/CSS website designed for GitHub Pages. It has no build
step, package manager, or framework.

## The files

- `index.html` — home page and biography
- `publications.html` — selected publications
- `resources.html` — resources and useful links
- `phd-students.html` — advising approach and expectations for PhD students
- `styles.css` — colours, spacing, typography, and mobile layout
- `profile.png` — profile photograph
- `assets/pdf/` — PDF files linked from the Resources page

## Edit the website

Open an HTML file in any text editor. Search for comments beginning with
`EDIT` to find the sections that are intended to be changed.

To change the photograph, replace `profile.png` with another image using the
same filename. To change colours or spacing, edit the variables at the top of
`styles.css`.

To add another PDF, place it in `assets/pdf/`, then copy an existing resource
entry in `resources.html` and change the filename, title, and author credit.

## Publish with GitHub Pages

1. Create a public GitHub repository named `YOUR-USERNAME.github.io`.
2. Upload all files from this folder to the top level of that repository.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.

The website will appear at `https://YOUR-USERNAME.github.io/` after GitHub
finishes publishing it.

## Preview locally

Double-click `index.html`. It will open in your browser, and the navigation
between the four pages will work without a web server.
