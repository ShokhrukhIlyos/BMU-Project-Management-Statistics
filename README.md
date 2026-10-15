# BMU Project Management Statistics

Static dashboard ready for GitHub and Netlify.

1. Upload this folder's contents to a GitHub repository.
2. In Netlify, choose **Add new project → Import an existing project**, select GitHub, then choose the repository.
3. Leave the build command empty. The publish directory is `public` (also configured in `netlify.toml`).
4. Deploy.

The dashboard is `public/index.html`. Its original embedded statistics are preserved. Only the custom JSON upload control was removed, with a null-safe event listener so startup still works. Chart libraries use the existing CDN links.
