# Carrion Crown GitHub Pages Wiki

This repo is pre-configured for **MkDocs Material + GitHub Pages** and supports **browser-only editing**.

## What to edit before first push

Open `mkdocs.yml` and replace these placeholders:

- `YOUR_GITHUB_USERNAME`
- `YOUR_REPO_NAME`

Example:

```yaml
site_url: https://ahmetselim.github.io/carrion-crown-wiki/
repo_url: https://github.com/ahmetselim/carrion-crown-wiki
edit_uri: edit/main/docs/
```

## Deploy on GitHub

1. Create a new GitHub repo.
2. Upload all files from this folder to the repo root.
3. Commit to the `main` branch.
4. In GitHub go to **Settings -> Pages**.
5. Under **Build and deployment**, choose **GitHub Actions**.
6. Push any change to `main`.
7. GitHub will build and publish the wiki automatically.

## Browser editing

Anyone with write access can:

- open a page in the live wiki
- click **Edit this page**
- edit the Markdown in GitHub
- commit in the browser

They can also press `.` on the GitHub repo page to open the browser editor (`github.dev`).

## Suggested permissions model

- Give trusted players **Write** access if they should edit directly.
- Give others **Read** access only.
- If you want public reading but limited editing, keep the repo public and only invite a few editors.

## Notes

- Images were moved to `docs/assets/`.
- Section landing pages were added for `Locations`, `Organizations`, `Sessions`, and `NPCs` so navigation works on GitHub Pages.
- Absolute asset paths were converted to relative paths so this works as a project site like `https://username.github.io/repo/`.
