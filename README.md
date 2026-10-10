# Tribute Page – Dr. A. P. J. Abdul Kalam

A responsive, single-page tribute website dedicated to Dr. A. P. J. Abdul Kalam, India's former President, scientist, teacher, and author.

This project was developed as **Task 1 of the Veda Technology Web Development Internship** to practice semantic HTML5, CSS3, page structure, and responsive web design.

## Technologies Used

- **HTML5:** Semantic page structure and accessible content.
- **CSS3:** Layout, typography, styling, responsive design, and interaction states.

No JavaScript, CSS frameworks, or build tools are used.

## Features

- Responsive, single-page tribute website.
- Navigation links to Home, Biography, Achievements, Timeline, and Legacy.
- Introductory section with a portrait and description of Dr. A. P. J. Abdul Kalam.
- Biography covering his life, education, scientific career, and presidency.
- Six achievement highlights presented in cards.
- Chronological timeline containing eight important life events.
- Inspirational quote with attribution.
- Legacy and inspiration section.
- Semantic HTML elements and descriptive image alternative text.
- Visible keyboard focus states for improved accessibility.
- Responsive layouts for mobile phones, tablets, and desktop screens.
- CSS support for reduced-motion preferences.

## Project Structure

```text
## Project Structure

```text
Tribute-Page/
├── index.html
├── style.css
├── README.md
├── assets/
│   └── images/
│       └── apj-abdul-kalam.jpg (optional)
└── evidence/
    ├── Screenshot 2026-10-10 135049.png
    └── Screenshot 2026-10-10 135119.png
```

**Note:** The portrait image is optional if the website uses the externally hosted Wikimedia Commons image. The `evidence/` folder contains screenshots documenting the project and rollback test.
```

**Note:** The local portrait image is optional if the website uses the externally hosted Wikimedia Commons image. The `assets/images/` directory is needed if you choose to store the portrait locally.

## How to Run Locally

No installation or build process is required.

1. Download or clone the project repository.
2. Open the `tribute-page` folder.
3. Double-click `index.html` to open the website in your browser.
4. Alternatively, open the project in Visual Studio Code and use the Live Server extension.

The externally hosted portrait requires an internet connection. If the image does not load, check the image URL and your internet connection.

## Portrait Image and Attribution

The portrait is sourced from Wikimedia Commons:

[File: A. P. J. Abdul Kalam.jpg]
(https://commons.wikimedia.org/wiki/File:A._P._J._Abdul_Kalam.jpg)

The source page credits the Government of India and identifies the image as available under the Government Open Data License – India (GODL-India).

Please review the source page for the applicable license terms and attribution requirements before redistributing the image.

### How to Replace the Portrait with a Local Image

1. Obtain a portrait image that you are permitted to use.
2. Save it as `apj-abdul-kalam.jpg` inside `assets/images/`.
3. Open `index.html`.
4. Update the image's `src` attribute to:

   `assets/images/apj-abdul-kalam.jpg`

5. Keep the descriptive `alt` text and include any required image attribution in the caption.

## Responsive Design Testing

The website should be checked at different viewport widths.

Suggested test widths:

- 320px – small mobile screens.
- 375px – standard mobile screens.
- 768px – tablet screens.
- Desktop width – larger screens.

To test responsiveness in Microsoft Edge:

1. Open `index.html`.
2. Press `F12` to open Developer Tools.
3. Press `Ctrl + Shift + M` to toggle the device toolbar.
4. Select a device or enter a custom viewport width.
5. Check that the content remains readable and does not overflow horizontally.

These are testing instructions; verify the website at each size before claiming that all tests have passed.

## Publish with GitHub Pages

1. Create a public repository on GitHub.
2. Upload the contents of the `tribute-page` folder to the repository root.
3. Ensure that `index.html` is in the selected publishing folder.
4. Open the repository's **Settings**.
5. Select **Pages** from the sidebar.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and the `/ (root)` folder.
8. Click **Save**.
9. Wait for the deployment to complete.
10. Open the published URL displayed in the GitHub Pages settings and verify the website.

The live website URL and successful deployment should be recorded here after deployment:

Live Website: https://rutvibjadav.github.io/Tribute-Page/

Live Website: https://rutvibjadav.github.io/Tribute-Page/

## Rollback and Recovery

Git can be used to review project history and recover an earlier working version when a change introduces an issue.

### Recommended Recovery Procedure

1. Commit a working version of the project before making significant changes.
2. Use `git log --oneline` to review previous commits.
3. Identify the commit containing the last known working version.
4. Review the changes before restoring or reverting anything.
5. If a change has already been committed and shared, consider using `git revert <commit-hash>` to create a new commit that reverses that change.
6. Test the recovered website locally.
7. If necessary, publish the corrected version and verify the deployment.

**Evidence:** Keep relevant Git history, screenshots of the working website, and deployment results as evidence when required by the internship.

Do not claim that rollback has been tested unless you have actually performed and verified a recovery procedure.

## Project Outcome

This project presents the life, achievements, and legacy of Dr. A. P. J. Abdul Kalam in a clear and accessible single-page layout.

It demonstrates practical use of semantic HTML5, standalone CSS3, responsive design, accessible content, and basic website deployment preparation.

The project also provides an opportunity to practice Git version control and publishing a static website through GitHub Pages.

---

**Developed as part of the Veda Technology Web Development Internship – Task 1: Tribute Page.**