# Beneath the Conversation GitHub Pages Site

This folder is a static GitHub Pages package for the podcast visualization project.

## Structure

- `index.html`: the multi-episode landing page, Beneath the Conversation.
- `s8e1/index.html`: the S8E1 single-episode dashboard.
- `s8e1/S8E1.m4a`: local audio used by the S8E1 dashboard.
- `.nojekyll`: prevents GitHub Pages from filtering static assets.

## Interaction

Clicking any tree on the landing page opens the S8E1 dashboard:

```
index.html -> s8e1/index.html
```

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub: Settings -> Pages -> Build and deployment -> Deploy from a branch.
4. Select the branch and root folder.

Because both dashboards are bundled as static HTML, no server-side runtime is required.
