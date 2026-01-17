# Lume Website - Legal Pages

This directory contains the HTML files for Lume's website legal pages.

## Files

- `index.html` - Landing page (optional)
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service

## Deployment

### Option 1: GitHub Pages (Recommended - Free & Easy)

1. **Create a GitHub repository** (or use existing)
   - Create a new repository on GitHub
   - Name it something like `lume-website`

2. **Upload these files**
   - Upload the `website/` folder contents to the repository root
   - Commit and push

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select branch (usually `main` or `master`)
   - Select folder: `/ (root)`
   - Click Save

4. **Get your URL**
   - Your site will be available at: `https://yourusername.github.io/lume-website/`
   - Privacy Policy: `https://yourusername.github.io/lume-website/privacy.html`
   - Terms: `https://yourusername.github.io/lume-website/terms.html`

5. **Update URLs in code** (if needed)
   - Replace `https://lumeapp.com` with your GitHub Pages URL
   - Update `Lume/App/LegalViews.swift` if you want to link to web versions

### Option 2: Vercel (Free & Easy)

1. **Sign up for Vercel** (vercel.com)
   - Free account, can use GitHub login

2. **Create new project**
   - Click "New Project"
   - Import Git repository (or drag and drop the website folder)
   - Deploy

3. **Get your URL**
   - Vercel provides a URL like: `https://lume-website.vercel.app`
   - Privacy Policy: `https://lume-website.vercel.app/privacy.html`
   - Terms: `https://lume-website.vercel.app/terms.html`

4. **Custom domain (optional)**
   - Add your own domain in Vercel settings
   - Update DNS records as instructed

### Option 3: Netlify (Free & Easy)

1. **Sign up for Netlify** (netlify.com)
   - Free account, can use GitHub login

2. **Deploy site**
   - Drag and drop the website folder to Netlify
   - Or connect to Git repository

3. **Get your URL**
   - Netlify provides a URL like: `https://lume-website.netlify.app`
   - Privacy Policy: `https://lume-website.netlify.app/privacy.html`
   - Terms: `https://lume-website.netlify.app/terms.html`

### Option 4: Cloudflare Pages (Free)

1. **Sign up for Cloudflare** (cloudflare.com)
2. **Go to Pages** in dashboard
3. **Create new project**
4. **Upload files** or connect Git repository
5. **Deploy**

## Custom Domain Setup (Optional)

If you have your own domain (e.g., `lumeapp.com`):

1. **Purchase domain** (if needed)
   - Namecheap, Google Domains, Cloudflare, etc.

2. **Configure DNS**
   - Add CNAME or A record pointing to your hosting service
   - Follow hosting service's instructions

3. **Update URLs**
   - Update email addresses in HTML files if needed
   - Update links in code to use your domain

## After Deployment

1. **Verify URLs work**
   - Test `privacy.html` URL
   - Test `terms.html` URL
   - Make sure they're accessible without login

2. **Add to App Store Connect**
   - Go to App Store Connect → Your App
   - App Information → Privacy Policy URL: `https://yourdomain.com/privacy.html`
   - App Information → Terms of Service URL: `https://yourdomain.com/terms.html`

3. **Update code** (optional)
   - Update URLs in `Lume/App/LegalViews.swift` if you want web links
   - Update any hardcoded URLs in the app

## Notes

- These pages use a dark theme matching the Lume app design
- They're mobile-responsive
- Update email addresses (`privacy@lumeapp.com`, `legal@lumeapp.com`, `support@lumeapp.com`) to your actual email addresses
- Update the App Store link in `index.html` once your app is live
- The "Last Updated" dates are set to January 1, 2026 - update as needed

## Support

For questions about deployment, contact your hosting service's support.
