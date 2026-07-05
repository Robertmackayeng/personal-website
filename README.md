# Personal Website & Portfolio - Robert MacKay, P.Eng.

A professional portfolio website built with Jekyll and hosted on GitHub Pages. This site showcases my project experience in nuclear energy, oil & gas, and industrial automation, along with technical articles and insights.

## Project Overview

This is a static website generated with Jekyll, featuring:

- **Home Page** - Overview and featured projects
- **Project Portfolio** - Detailed case studies of major engineering projects
- **Blog** - Technical articles on control systems, nuclear standards, and automation
- **About** - Professional background and expertise overview
- **Responsive Design** - Mobile-friendly layout
- **Dark Blue Theme** - Professional engineering aesthetic

## Features

### Content Sections

1. **Projects** (`projects.md`)
   - BWRX-300 Small Modular Reactor
   - Ontario Power Generation Nuclear Facilities
   - Suncor East Tank Farm
   - TC Energy Pipeline Projects

2. **Blog** (`_posts/`)
   - Technical articles and insights
   - Industry trends and analysis
   - Professional development topics

3. **About** (`about.md`)
   - Professional background
   - Core competencies
   - Contact information

### Technical Features

- **Jekyll-powered** - Static site generation for fast performance
- **GitHub Pages ready** - Deploy directly from git repository
- **SEO optimized** - Structured data and meta tags
- **RSS feed** - Subscribe to blog updates
- **Mobile responsive** - Works on all devices
- **Custom CSS styling** - Professional, clean design

## Local Development

### Prerequisites

- Ruby 2.7 or higher
- Bundler

### Setup

1. Clone the repository:
```bash
git clone https://github.com/robertmackayeng/personal-website.git
cd personal-website
```

2. Install dependencies:
```bash
bundle install
```

3. Serve locally:
```bash
bundle exec jekyll serve
```

4. Visit `http://localhost:4000` in your browser

### Creating Blog Posts

1. Create a new file in `_posts/` directory
2. Use the filename format: `YYYY-MM-DD-post-title.md`
3. Add front matter at the top:

```markdown
---
layout: default
title: Your Article Title
date: 2026-07-05
categories: [tag1, tag2]
excerpt: Brief description of the article
---
```

4. Write your content in Markdown
5. Commit and push to GitHub

### Customization

- **Site settings**: Edit `_config.yml`
- **Styling**: Modify `assets/css/style.css`
- **Navigation**: Update header nav in `_layouts/default.html`

## Deployment

### GitHub Pages Setup

1. Create a repository named `personal-website`
2. In repository settings, enable GitHub Pages
3. Set source to `main` branch
4. Push your changes

Your site will be available at: `https://robertmackayeng.github.io/personal-website`

### Custom Domain (Optional)

To use a custom domain:

1. Create a `CNAME` file with your domain name
2. Update DNS records with GitHub's nameservers
3. Enable HTTPS in repository settings

## Site Structure

```
personal-website/
├── _config.yml           # Jekyll configuration
├── _layouts/
│   └── default.html      # Base layout template
├── _posts/               # Blog posts
│   └── YYYY-MM-DD-title.md
├── assets/
│   ├── css/
│   │   └── style.css     # Custom styling
│   └── images/           # Image assets
├── index.md              # Home page
├── projects.md           # Project portfolio
├── blog.md               # Blog index
├── about.md              # About page
├── Gemfile               # Ruby dependencies
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## Blog Topics

The blog is designed to cover:

- **Nuclear Engineering** - IEC 61513, safety standards, reactor design
- **Control Systems** - DCS design, PLC programming, automation
- **Industrial Projects** - Case studies and lessons learned
- **Professional Development** - Career insights and technical leadership
- **Technology Trends** - Emerging technologies in automation

## Content Management

### Adding Projects

Edit `projects.md` to add new project descriptions. Each project should include:
- Project name and client
- Duration and location
- Project scope
- Your specific role and contributions
- Technical focus areas

### Adding Blog Posts

Create new `.md` files in `_posts/` directory following the naming convention:
- Date: YYYY-MM-DD format
- Title: lowercase, hyphen-separated
- Example: `2026-07-15-control-systems-best-practices.md`

## Performance Optimization

- Static HTML generation ensures fast load times
- No database required
- Minimal CSS for quick rendering
- Suitable for low-bandwidth environments

## Security

- No sensitive information in repository
- Static site cannot be directly hacked
- HTTPS enabled via GitHub Pages
- Regular dependency updates via Bundler

## License

Personal portfolio - All rights reserved

## Contact

- **Email:** robert.james.mackay@outlook.com
- **LinkedIn:** [linkedin.com/in/robertjamesmackay](https://linkedin.com/in/robertjamesmackay)
- **GitHub:** [github.com/robertmackayeng](https://github.com/robertmackayeng)

## Future Enhancements

- [ ] Add project timeline visualization
- [ ] Implement search functionality
- [ ] Add speaking engagements section
- [ ] Create technical resource library
- [ ] Add dark mode toggle
- [ ] Implement newsletter subscription

## Contributing

This is a personal portfolio, but feedback and suggestions are welcome. Feel free to reach out via email or LinkedIn.

---

Built with Jekyll • Hosted on GitHub Pages • Updated: July 2026
