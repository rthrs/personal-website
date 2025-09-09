# Personal Website of Artur Myszkowski

[![Website-Status](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Farturmyszkowski.pl)](https://arturmyszkowski.pl)
[![Netlify Status](https://api.netlify.com/api/v1/badges/87c81a46-6519-4017-9210-fa0ae4c4b0ef/deploy-status)](https://app.netlify.com/projects/scintillating-tiramisu-37b9e8/deploys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The source code for my personal website, available at [arturmyszkowski.pl](https://arturmyszkowski.pl).

This project was created to serve as a digital business card, and in the future a place to showcase my most interesting projects, and a platform for writing technical articles.

<!-- ![Project Screenshot](https://link-to-your-screenshot.png) -->

## ✨ Features

*   **Minimalist & Modern Design:** A clean, fast, and content-focused layout using Hugo and the PaperMod theme.
*   **Profile-Centric Homepage:** A simple landing page with a circular profile photo, a short bio, and links to my social profiles.
*   **Bilingual Content:** Fully supports English and Polish content with a language switcher.
*   **Future-Ready:** Includes layouts for detailed project pages and a complete blog section.
*   **SEO Optimized:** Built with best practices to ensure high search engine visibility for my name and personal brand.
*   **Developer Focused:** Integrates seamlessly with a modern developer workflow.

## 🚀 Tech Stack

This project is built with a stack chosen for speed, simplicity, and the learning experience.

*   **Static Site Generator:** [Hugo](https://gohugo.io/)
*   **Theme:** [Hugo PaperMod](https://github.com/adityatelange/hugo-PaperMod)
*   **Hosting & Deployment:**
    *   **Platform:** [Netlify](https://www.netlify.com/)
    *   **DNS & CDN:** Managed globally via Netlify's Edge Network.
    *   **CI/CD:** Automated builds and deployments triggered by `git push` to the `main` branch.
*   **Development Environment:** Visual Studio Code, iTerm2 with Zsh, [Starship Prompt](https://starship.rs/), and [Nerd Fonts](https://www.nerdfonts.com/).

## 🛠️ Getting Started: Local Development

To run this project on your local machine, follow these steps.

### Prerequisites

*   **Git:** You'll need Git installed to clone the repository.
*   **Hugo:** Make sure you have the latest version of Hugo installed. On macOS, you can use Homebrew:
    ```sh
    brew install hugo
    ```

### Installation

1.  **Clone the repository:**
    ```sh
    git clone git@github.com:rthrs/personal-website.git
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd personal-website
    ```

3.  **Initialize the theme submodule:**
    This theme is included as a Git submodule. You must run this command to download it.
    ```sh
    git submodule update --init
    ```

### Running the Local Server

Start the Hugo development server to see a live preview of the site. The `-D` flag includes posts marked as drafts.

```sh
hugo server -D
```

## 💄 Favicon

The favicon set for this website was generated using the excellent tool [RealFaviconGenerator.net](https://realfavicongenerator.net/). This service was used to create a comprehensive set of icons, ensuring correct and high-quality display on all major browsers and platforms, including:

*   Standard browser tabs (`favicon.ico`, PNG versions)
*   Apple touch icons for iOS (`apple-touch-icon.png`)
*   Android Chrome home screen icons
*   Pinned tab icons for Safari (SVG)
*   Windows Metro tiles

The generated files are located in the `static/` directory, and the necessary HTML link tags have been added to the site's `<head>` via a custom `layouts/partials/extended_head.html` partial, which is a standard Hugo and PaperMod theme practice for this type of customization.