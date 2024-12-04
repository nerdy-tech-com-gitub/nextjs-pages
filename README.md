# Deploy Next.js to GitHub Pages

This is a Next.js template which can be deployed to GitHub Pages as a static site.

## Deploying to GitHub Pages

1.  Create a new public GitHub repository
1.  Edit `next.config.ts` to match your GitHub repository name:
    - Given the pattern `https://github.com/<user>/<repo>`
    - Update your `basePath` config to the name of your repo (e.g. `/repo`)
1.  Push the starter code to the `main` branch
1.  Run the `deploy` script (e.g. `npm run deploy`) to create the `gh-pages` branch
1.  On GitHub, go to **Settings** > **Pages** > **Branch**, and choose `gh-pages` as the branch with the `/root` folder. Hit **Save**
1.  Make a change
1.  Run the `deploy` script again to push the changes to GitHub Pages

Congratulations! You should have a URL like:

```bash
https://<github-user-name>.github.io/<github-project-name>/
```

For more information, see our [deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying/static-exports).

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!
