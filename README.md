# Razib Ahsan — Portfolio

A clean, professional Jekyll portfolio website designed for senior software engineers. Built with a corporate aesthetic inspired by GitHub, Stripe, Linear, and Vercel.

## Quick Start

### Prerequisites

- Ruby 3.0+ ([installation guide](https://www.ruby-lang.org/en/documentation/installation/))
- Bundler (`gem install bundler`)

### Setup

```bash
# Install dependencies
bundle install

# Start the development server
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000) in your browser.

### Deploy to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to the branch you want to deploy from
4. The site will be live at `https://<username>.github.io/<repo-name>/`

> **Note:** If deploying to a subdirectory (e.g., `github.io/portfolio`), update `baseurl` in `_config.yml` to `/portfolio`.

## Project Structure

```
portfolio/
├── _config.yml           # Site configuration
├── _data/
│   └── navigation.yml    # Navigation menu items
├── _includes/
│   ├── head.html         # HTML <head> with meta, fonts, CSS
│   ├── header.html       # Sticky navigation header
│   └── footer.html       # Site footer with social links
├── _layouts/
│   ├── default.html      # Base HTML layout
│   └── page.html         # Page layout with optional header
├── assets/
│   └── css/
│       └── main.css      # Complete stylesheet (855 lines)
├── index.html            # Home page with hero section
├── about.md              # About, competencies, skills
├── experience.md         # Work history timeline
├── projects.md           # Project showcase grid
├── resume.md             # Education & certifications
├── contact.md            # Contact information cards
├── Gemfile               # Ruby dependencies
└── README.md             # This file
```

## Customization

### Personal Information

Edit `_config.yml` to update:

```yaml
title: "Your Name | Your Title"
description: "Your professional description."

author:
  name: Your Name
  email: your@email.com
  bio: Your Title
  github: yourgithub
  linkedin: yourlinkedin
```

### Navigation

Edit `_data/navigation.yml` to add/remove/reorder pages.

### Accent Color

Change the primary color in `assets/css/main.css`:

```css
:root {
  --color-primary: #2563EB;       /* Change this */
  --color-primary-hover: #1d4ed8; /* Slightly darker shade */
}
```

### Adding a Resume PDF

1. Place your PDF in `assets/` (e.g., `assets/resume.pdf`)
2. Update the download link in `resume.md`

## Design System

| Token | Value |
|---|---|
| Primary | `#2563EB` |
| Text | `#1e293b` |
| Secondary Text | `#64748b` |
| Background | `#ffffff` |
| Border | `#e2e8f0` |
| Font | Inter |
| Max Width | 1200px |
| Border Radius | 6px |

## License

MIT
