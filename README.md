# Personal Website of Artur Myszkowski

[![Website-Status](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Farturmyszkowski.pl)](https://arturmyszkowski.pl)
[![Netlify Status](https://api.netlify.com/api/v1/badges/87c81a46-6519-4017-9210-fa0ae4c4b0ef/deploy-status)](https://app.netlify.com/projects/scintillating-tiramisu-37b9e8/deploys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The source code for my personal website, available at
[arturmyszkowski.pl](https://arturmyszkowski.pl).

This project was created to serve as a digital business card, and in the future
a place to showcase my most interesting projects, and a platform for writing
technical articles.

<!-- ![Project Screenshot](https://link-to-your-screenshot.png) -->

## ✨ Features

- **Minimalist & Modern Design:** A clean, fast, and content-focused layout
  using Hugo and the PaperMod theme.
- **Profile-Centric Homepage:** A simple landing page with a circular profile
  photo, a short bio, and links to my social profiles.
- **Bilingual Content:** Fully supports English and Polish content with a
  language switcher.
- **Future-Ready:** Includes layouts for detailed project pages and a complete
  blog section.
- **SEO Optimized:** Built with best practices to ensure high search engine
  visibility for my name and personal brand.
- **Developer Focused:** Integrates seamlessly with a modern developer workflow.

## 🚀 Tech Stack

This project is built with a stack chosen for speed, simplicity, and the
learning experience.

- **Static Site Generator:** [Hugo](https://gohugo.io/)
- **Theme:** [Hugo PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- **Hosting & Deployment:**
    - **Platform:** [Netlify](https://www.netlify.com/)
    - **DNS & CDN:** Managed globally via Netlify's Edge Network.
    - **CI/CD:** Automated builds and deployments triggered by `git push` to the
      `main` branch.
- **Development Environment:**
  [Visual Studio Code](https://code.visualstudio.com/),
  [Starship Prompt](https://starship.rs/), and
  [Nerd Fonts](https://www.nerdfonts.com/).

## 🛠️ Local Development & Workflow

This project uses **Node.js** and **npm** for managing development dependencies
and running scripts. This is the recommended way to work with the project.

### 1. Prerequisites

- **Node.js:** Make sure you have Node.js (which includes `npm`) installed on
  your system.
- **Hugo:** This site is built with Hugo. Ensure you have the latest version
  installed. On macOS, this can be done with Homebrew: `brew install hugo`.

### 2. Initial Project Setup

To get started, clone the repository and install the necessary dependencies.

```bash
# Clone the repository
git clone git@github.com:rthrs/personal-website.git

# Navigate into the project directory
cd personal-website

# Install the dev dependencies (Prettier, Netlify CLI, etc.)
npm install

# Initialize the theme submodule
git submodule update --init
```

### 3. Available Scripts

This project includes several `npm` scripts to streamline the development and
build process. These are the main commands you will use.

#### `npm run dev`

Starts the local Hugo development server with live reloading. This is the
primary command you will use for everyday development, writing content, and
testing style changes. The server will be available at `http://localhost:1313`.

#### `npm run build`

Creates a clean, production-ready build of the website in the `/public`
directory. This command first deletes the old build and then runs
`netlify build` to execute a production-grade Hugo build, including
minification.

#### `npm run preview`

Serves the contents of the generated `/public` folder with a simple local web
server. **You must run `npm run build` first.** This is useful for previewing
the final, optimized site before deploying.

#### `npm run format`

Automatically formats all project files (`.html`, `.md`, `.css`, `.js`, etc.)
using **Prettier**.

#### `npm run netlify`

Provides direct access to the locally installed **Netlify CLI** for running
one-off commands. Use `--` to pass arguments. For example:
`npm run netlify -- status`.

## 💄 Favicon

The favicon set for this website was generated using the excellent tool
[RealFaviconGenerator.net](https://realfavicongenerator.net/). This service was
used to create a comprehensive set of icons, ensuring correct and high-quality
display on all major browsers and platforms. The generated files are located in
the `static/` directory, and the necessary HTML link tags have been added via a
custom `layouts/partials/extended_head.html` partial.
