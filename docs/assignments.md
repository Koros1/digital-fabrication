# Assignment 1 — Documentation and GitHub Pages Setup

## What was the goal?

My goal was to create a website to document my Digital
Fabrication coursework and share my learning process online.

## What did I do?

I created a public GitHub repository called digital-fabrication.
I added a mkdocs.yml configuration file and created Markdown
pages inside the docs folder.

I set up a GitHub Actions workflow to build the website with
MkDocs and publish it through GitHub Pages. I added Home,
About Me, Assignments, and Projects pages.

Finally, I downloaded the repository as a ZIP file and opened
the docs folder in Obsidian to edit my documentation.

## What tools did I use?

- GitHub to store my files and track changes
- MkDocs to generate the static website
- GitHub Actions to automate building and publishing
- GitHub Pages to host the website
- Obsidian to edit Markdown files
- CSS to customise the design

## What went wrong?

At first, I was unsure where to create the configuration,
content, and workflow files. I also accidentally created
an unwanted folder and note in Obsidian.

Another challenge was understanding how my local edits
would appear on the published website.

## What did I change? How did I solve the problems?

I checked the folder structure: mkdocs.yml belongs in the
repository root, Markdown pages belong in docs, and the
publishing workflow belongs in .github/workflows.

I learned how to remove unwanted items and how to upload
edited Markdown files to the correct folder on GitHub.
Obsidian saves my edits locally; uploading them to GitHub
triggers the workflow that updates the website.

I also added a custom CSS file to change the navigation
colour, background colour, typography, and spacing.

## What was the result?

I created and published a working documentation website
with four main sections. I checked the home page and
confirmed that the publishing workflow completed successfully.

I can now write my documentation in Obsidian and upload
updates to GitHub as the course progresses.

[Visit my website](https://koros1.github.io/digital-fabrication/)