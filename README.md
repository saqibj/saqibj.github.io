# SJLabs - Personal Website & Portfolio

Welcome to SJLabs, a modern personal website and portfolio built with Jekyll and Decap CMS. This site includes features for blog posts, projects, and static pages.

## Features

- 📝 Blog system with markdown support
- 💻 Project showcase with technology tags
- 📄 Static pages (About, etc.)
- 🎨 Modern, responsive design
- 📱 Mobile-friendly
- 🚀 Fast loading with optimized assets

## Getting Started

### Prerequisites

- Ruby 3.1 or higher
- Git
- GitHub account
- GitHub Personal Access Token

### Installation

1. Clone the repository:
```bash
git clone [https://github.com/saqibj/saqibj.github.io.git](https://github.com/saqibj/saqibj.github.io.git)
cd saqibj.github.io
Install dependencies:
bash
CopyInsert in Terminal
bundle install
Start the local development server:
bash
CopyInsert in Terminal
bundle exec jekyll serve
The site will be available at http://localhost:4000

Using Decap CMS
Access the CMS at:
Production: https://saqibj.github.io/admin
Local: http://localhost:4000/admin
Login with your GitHub credentials
Available Collections:
Blog Posts: Create and manage blog content
Projects: Add and edit project showcases
Pages: Edit static pages like About
Directory Structure
CopyInsert
saqibj.github.io/
├── _data/              # Project data
│   └── projects/       # Project YAML files
├── _includes/         # Reusable components
├── _layouts/          # Page layouts
├── _posts/            # Blog posts
│   └── blog/          # Blog post markdown files
├── admin/             # CMS configuration
│   └── .env          # GitHub token (not in git)
├── static/            # Static assets
│   ├── css/          # Stylesheets
│   ├── images/       # Images
│   └── js/           # JavaScript
└── config.yml        # CMS configuration
Adding Content
Blog Posts
Create new posts in _posts/blog/ with the format:
yaml
CopyInsert
---
title: "Your Title"
date: YYYY-MM-DD
tags: ["tag1", "tag2"]
---
Your content here
Projects
Create new project files in _data/projects/:
yaml
CopyInsert
---
name: "Project Name"
description: "Project description"
url: "https://project-url.com"
tech:
  - "Technology 1"
  - "Technology 2"
---
Pages
Edit static pages directly:
about.md
index.md
Deployment
The site is automatically deployed to GitHub Pages when you push to the main branch. GitHub Actions will:

Build the Jekyll site
Deploy to GitHub Pages
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For issues or questions, please open an issue in the repository.

Acknowledgments
Built with Jekyll
Uses Decap CMS for content management
Hosted on GitHub Pages
CopyInsert

This README includes:
1. Clear installation instructions
2. Usage guide for Decap CMS
3. Directory structure explanation
4. Content creation guidelines
5. Deployment information
6. Contributing guidelines
7. License and contact information

Would you like me to help you create this README.md file or make any adjustments to the content?
Feedback submitted
Me

generate the file

Revert
I'll help you create the README.md file. Here's the content you can use:

markdown
CopyInsert
# SJLabs - Personal Website & Portfolio

Welcome to SJLabs, a modern personal website and portfolio built with Jekyll and Decap CMS. This site includes features for blog posts, projects, and static pages.

## Features

- 📝 Blog system with markdown support
- 💻 Project showcase with technology tags
- 📄 Static pages (About, etc.)
- 🎨 Modern, responsive design
- 📱 Mobile-friendly
- 🚀 Fast loading with optimized assets

## Getting Started

### Prerequisites

- Ruby 3.1 or higher
- Git
- GitHub account
- GitHub Personal Access Token

### Installation

1. Clone the repository:
```bash
git clone [https://github.com/saqibj/saqibj.github.io.git](https://github.com/saqibj/saqibj.github.io.git)
cd saqibj.github.io
Install dependencies:
bash
CopyInsert in Terminal
bundle install
Start the local development server:
bash
CopyInsert in Terminal
bundle exec jekyll serve
The site will be available at http://localhost:4000

Using Decap CMS
Access the CMS at:
Production: https://saqibj.github.io/admin
Local: http://localhost:4000/admin
Login with your GitHub credentials
Available Collections:
Blog Posts: Create and manage blog content
Projects: Add and edit project showcases
Pages: Edit static pages like About
Directory Structure
CopyInsert
saqibj.github.io/
├── _data/              # Project data
│   └── projects/       # Project YAML files
├── _includes/         # Reusable components
├── _layouts/          # Page layouts
├── _posts/            # Blog posts
│   └── blog/          # Blog post markdown files
├── admin/             # CMS configuration
│   └── .env          # GitHub token (not in git)
├── static/            # Static assets
│   ├── css/          # Stylesheets
│   ├── images/       # Images
│   └── js/           # JavaScript
└── config.yml        # CMS configuration
Adding Content
Blog Posts
Create new posts in _posts/blog/ with the format:
yaml
CopyInsert
---
title: "Your Title"
date: YYYY-MM-DD
tags: ["tag1", "tag2"]
---
Your content here
Projects
Create new project files in _data/projects/:
yaml
CopyInsert
---
name: "Project Name"
description: "Project description"
url: "https://project-url.com"
tech:
  - "Technology 1"
  - "Technology 2"
---
Pages
Edit static pages directly:
about.md
index.md
Deployment
The site is automatically deployed to GitHub Pages when you push to the main branch. GitHub Actions will:

Build the Jekyll site
Deploy to GitHub Pages
Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For issues or questions, please open an issue in the repository.

Acknowledgments
Built with Jekyll
Uses Decap CMS for content management
Hosted on GitHub Pages