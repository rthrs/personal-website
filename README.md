# Personal Website of Artur Myszkowski

[![Website-Status](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Farturmyszkowski.pl)](https://arturmyszkowski.pl)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The source code for my personal website, available at [arturmyszkowski.pl](https://arturmyszkowski.pl).

This project was created to serve as a digital business card, and in the future a place to showcase my most interesting projects, and a platform for writing technical articles.
<!-- It is built with Hugo for maximum performance and hosted on AWS to practice and demonstrate my skills with cloud infrastructure. -->

<!-- ![Project Screenshot](https://link-to-your-screenshot.png) -->

## ✨ Features

*   **Minimalist & Modern Design:** A clean, fast, and content-focused layout using the PaperMod theme.
*   **Profile-Centric Homepage:** A simple landing page with a circular profile photo, a short bio, and links to my social profiles.
*   **Bilingual Content:** Fully supports English and Polish content with a language switcher.
*   **Future-Ready:** Includes layouts for detailed project pages and a complete blog section.
*   **SEO Optimized:** Built with best practices to ensure high search engine visibility for my name and personal brand.
*   **Developer Focused:** Integrates seamlessly with a modern developer workflow.

## 🚀 Tech Stack

This project is built with a stack chosen for speed, simplicity, and the learning experience.

*   **Static Site Generator:** [Hugo](https://gohugo.io/)
*   **Theme:** [Hugo PaperMod](https://github.com/adityatelange/hugo-PaperMod)
<!-- *   **Hosting:**
    *   **Storage:** [AWS S3](https://aws.amazon.com/s3/)
    *   **CDN & SSL:** [AWS CloudFront](https://aws.amazon.com/cloudfront/)
    *   **DNS:** [AWS Route 53](https://aws.amazon.com/route53/) -->
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