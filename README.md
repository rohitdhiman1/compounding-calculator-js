

# Compounding Calculator

A simple, modern web-based compounding calculator built with Vue.js and Chart.js. All calculations are performed in the browser—no backend required.

## Features

- Modern, user-friendly UI
- Input validation and error messages
- Responsive design for desktop and mobile
- Automatic formatting of large numbers with commas for readability
- Interactive chart showing principal and compounded interest growth

## How to Run Locally

Since this is a static website, you can run it using any simple web server. Here’s how to do it with Python's built-in server:

1.  **Navigate to the `public` directory:**
    ```bash
    cd public
    ```

2.  **Start the web server:**
    - If you have Python 3:
      ```bash
      python -m http.server 8000
      ```
    - If you have Python 2:
      ```bash
      python -m SimpleHTTPServer 8000
      ```

3.  **Open your browser** and go to `http://localhost:8000`.

## How to Deploy on Cloudflare Pages

For detailed deployment instructions, please see `README.cloudflare.md`.

## Example Usage

Enter:
- Initial Amount: 100,000
- Annual Rate: 7
- Duration: 10 years
- Annual Add-on: 1,000

Click "Calculate" to see the final amount and growth chart.
