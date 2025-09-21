# Deploying to Cloudflare Pages

This guide explains how to deploy the compounding calculator as a static site on Cloudflare Pages.

## Live Demo

You can view the deployed calculator here: [https://compounding-calculator-js.pages.dev/](https://compounding-calculator-js.pages.dev/)

## Prerequisites
- A Cloudflare account.
- A GitHub or GitLab repository containing this project.

## Steps to Deploy

1.  **Push the project to your repository.**
    Make sure the `public` directory and all its contents are included.

2.  **Create a new Cloudflare Pages project.**
    - Log in to your Cloudflare dashboard and go to **Workers & Pages**.
    - Click **Create application** and select the **Pages** tab.
    - Connect your GitHub/GitLab account and choose the repository for this project.

3.  **Configure the build settings.**
    - **Framework preset:** Select **None**.
    - **Build command:** Leave this blank.
    - **Build output directory:** Set this to `public`.

4.  **Save and Deploy.**
    - Click **Save and Deploy**. Cloudflare will automatically pull your files and deploy them.

Your site will be live at the URL provided by Cloudflare Pages. Any future pushes to your repository's main branch will trigger automatic redeployments.
