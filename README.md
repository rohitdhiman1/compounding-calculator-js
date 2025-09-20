

# Compounding Calculator

A simple, modern web-based compounding calculator built with Vue.js and Chart.js. All calculations are performed in the browser—no backend required.

## Features

- Modern, user-friendly UI
- Input validation and error messages
- Responsive design for desktop and mobile
- Automatic formatting of large numbers with commas for readability
- Interactive chart showing principal and compounded interest growth

## How to Deploy on Cloudflare Pages

1. Copy the contents of the `public` folder (especially `index.html`) to your Cloudflare Pages project.
2. In Cloudflare Pages, set the build output directory to `public` (or the folder containing `index.html`).
3. Deploy your site. No build step is required—this is a static SPA.
4. Your calculator will be available at your Cloudflare Pages URL.

## Example Usage

Enter:
- Initial Amount: 100,000
- Annual Rate: 7
- Duration: 10 years
- Annual Add-on: 1,000

Click "Calculate" to see the final amount and growth chart.