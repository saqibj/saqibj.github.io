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
git clone https://github.com/saqibj/saqibj.github.io.git
cd saqibj.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Start the local development server:
```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

## Using Decap CMS

1. Access the CMS at:
   - Production: https://saqibj.github.io/admin
   - Local: http://localhost:4000/admin

2. Login with your GitHub credentials

3. Available Collections:
   - **Blog Posts**: Create and manage blog content
   - **Projects**: Add and edit project showcases
   - **Pages**: Edit static pages like About

## Directory Structure

```
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
```

## Adding Content

### Blog Posts

1. Create new posts in `_posts/blog/` with the format:
```yaml
---
title: "Your Title"
date: YYYY-MM-DD
tags: ["tag1", "tag2"]
---
Your content here
```

### Projects

1. Create new project files in `_data/projects/`:
```yaml
---
name: "Project Name"
description: "Project description"
url: "https://project-url.com"
tech:
  - "Technology 1"
  - "Technology 2"
---
```

### Pages

1. Edit static pages directly:
   - `about.md`
   - `index.md`

## Deployment

The site is automatically deployed to GitHub Pages when you push to the main branch. GitHub Actions will:
1. Build the Jekyll site
2. Deploy to GitHub Pages

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For issues or questions, please open an issue in the repository.

## Acknowledgments

- Built with Jekyll
- Uses Decap CMS for content management
- Hosted on GitHub Pages
