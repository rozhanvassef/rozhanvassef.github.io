# rozhanvassef.github.io

Personal academic website of Rozhan Vassef.

## Before uploading

Put your photo in the `images` folder and name it exactly `profile.jpg`
(portrait or square crop, around 600–800 px wide, under ~300 KB).

## Publishing on GitHub Pages

1. Sign in to GitHub as **rozhanvassef**.
2. Create a new repository:
   - Name: exactly `rozhanvassef.github.io`
   - Description (optional): `Personal academic website`
   - Visibility: **Public**
   - Leave "Add a README file", ".gitignore" and "license" **off**
3. On the new empty repo page, click **uploading an existing file**, then drag in the
   things *inside* this folder (`index.html`, `README.md`, and the `images` folder).
   Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then Save.
5. After a minute or two the site is live at **https://rozhanvassef.github.io**

## Editing later

Everything is in `index.html`. Each section is marked with a comment like
`<!-- ========== PROJECTS ========== -->`, so you can find it and edit the text directly
on GitHub (click the file, then the pencil icon). Changes go live within a minute or two.

## Adding your CV later

1. In the repo, click **Add file → Upload files** and drag in a folder named `files`
   containing your CV named exactly `Rozhan_Vassef_CV.pdf`
   (use a version without your phone number, since it's public).
2. Open `index.html`, click the pencil icon, and search for `CV-START`.
   It appears twice (the menu link and the Download CV button).
   Each time, delete the whole `CV-START ...` line and the matching `CV-END ...` line,
   leaving the lines between them. Commit the change.

## Adding a code link to a project

Put this line inside the project's card, after its chips:

```html
<a href="https://github.com/rozhanvassef/REPO-NAME" target="_blank">Code →</a>
```

## Hiding the site from Google (optional)

The site is listed on Google by default. To hide it, add this line in `index.html`
right after the `<meta name="viewport" ...>` line, and delete it again to undo:

```html
<meta name="robots" content="noindex, nofollow">
```
