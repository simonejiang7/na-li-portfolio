# Na Li Portfolio

A Hugo-based portfolio website built with the Hugolify template, optimized for Netlify deployment with CMS editing capabilities.

## Features

- **Fast & Accessible**: Built with Hugo for optimal performance
- **CMS Integration**: Edit content directly through Netlify's admin interface
- **Responsive Design**: Mobile-friendly and modern UI
- **SEO Optimized**: Built-in SEO features and meta tags
- **Low Carbon**: Optimized for minimal environmental impact

## Deployment on Netlify

### Automatic Deployment

1. **Connect to Netlify**:
   - Go to [Netlify](https://netlify.com)
   - Click "New site from Git"
   - Connect your GitHub account
   - Select this repository: `simonejiang7/na-li-portfolio`

2. **Build Settings** (should be auto-detected):
   - Build command: `yarn build`
   - Publish directory: `public`
   - Hugo version: `0.146.4`

3. **Deploy**:
   - Click "Deploy site"
   - Your site will be available at `https://your-site-name.netlify.app`

### Content Management

1. **Access Admin Panel**:
   - Visit `https://your-site-name.netlify.app/admin/`
   - Sign up/Login with Netlify Identity

2. **Edit Content**:
   - Pages: Edit home page, contact page, etc.
   - Site Settings: Update SEO, menus, banner settings
   - Legal Pages: Manage privacy policy and legal mentions

3. **Media Management**:
   - Upload images through the CMS
   - Images are stored in `static/assets/images/`

## Local Development

```bash
# Install dependencies
yarn install

# Start development server
yarn watch

# Build for production
yarn build
```

## CMS Configuration

The CMS is configured to edit:
- **Pages**: Home, Contact, Legal pages
- **Site Settings**: SEO, menus, banner
- **Media**: Images and assets

All changes are automatically committed to the GitHub repository and trigger a new deployment.

## Live demos

### Base

**Netlify**

https://demo.hugolify.io/

[![Netlify Status](https://api.netlify.com/api/v1/badges/5a4fa061-e7a5-4e66-9612-4fae713bda09/deploy-status)](https://app.netlify.com/sites/hugolify-demo/deploys)

**Cloudflare Pages**

https://hugolify.pages.dev/


### Theme 1

https://theme-1--hugolify-demo.netlify.app/

### Theme 2

https://theme-2--hugolify-demo.netlify.app/

### Theme 3

https://theme-3--hugolify-demo.netlify.app/

### Theme 4

https://theme-4--hugolify-demo.netlify.app/

### Theme 5

https://theme-5--hugolify-demo.netlify.app/

### Products

https://demo-products--hugolify-demo.netlify.app

## Documentation

https://www.hugolify.io/docs/

## License

Hugolify is free for personal or commercial projects (MIT license)
