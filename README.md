# Clipitra Digital Services LLP Website

Welcome to the official repository for the **Clipitra Digital Services LLP** website. This website showcases our digital solutions including graphic design, video editing, web development, and UI/UX design.

## 🚀 Features

-   **Responsive Design**: Fully responsive layout that works on all devices.
-   **Service Showcase**: Detailed sections for our core services.
-   **Contact Form**: Integrated with Web3Forms for secure email delivery.
-   **Automated Deployment**: GitHub Actions workflow for building and deploying to GitHub Pages.

## 🛠️ Technologies Used

-   **HTML5**
-   **CSS3** (Custom styling)
-   **JavaScript**
-   **[Web3Forms](https://web3forms.com/)** (Contact form backend)
-   **GitHub Actions** (CI/CD)

## ⚙️ Setup & Deployment

This project uses **GitHub Actions** to securely inject the API key and deploy the website.

### Prerequisites

1.  **Web3Forms API Key**: You need an Access Key from Web3Forms.
2.  **GitHub Repository**: This code must be hosted on GitHub.

### Local Development

To run the site locally for testing:
1.  Clone the repository.
2.  Open `index.html` in your browser.
    *   *Note: The contact form will not work locally unless you temporarily replace `WEB3FORMS_ACCESS_KEY_PLACEHOLDER` in `index.html` with your actual key.*

### Deployment

The site is configured to deploy automatically to **GitHub Pages** when you push to the `main` branch.

**Important Configuration:**

1.  **Add Secret**:
    -   Go to your repository **Settings** > **Secrets and variables** > **Actions**.
    -   Add a new repository secret named `WPKEY` with your Web3Forms Access Key.

2.  **Enable GitHub Pages**:
    -   Go to **Settings** > **Pages**.
    -   Set **Source** to **GitHub Actions**.

## 📞 Contact

**Clipitra Digital Services LLP**
-   **Email**: help.clipitradigitalservices@gmail.com
-   **Address**: Raebareli, Uttar Pradesh, India
