# Deploy Helix Ltd Website to Vercel

Your static website is ready in the `public` folder!

## Option 1: Deploy via Vercel Dashboard (Easiest)

1. **Go to [vercel.com](https://vercel.com)** and sign up/login (use GitHub account)

2. **Drag & Drop Deploy:**
   - Go to your Vercel dashboard
   - Drag the `public` folder directly onto the page
   - Your site will be deployed instantly!

3. **Connect your domain (helixltd.co):**
   - Go to your project → Settings → Domains
   - Add `helixltd.co`
   - Add the DNS records Vercel shows you to your domain registrar

## Option 2: Deploy via Vercel CLI

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Deploy:**
   ```bash
   cd "/Users/Apple/Desktop/Helix trading/marketing /helixltd.co/public"
   vercel
   ```

3. **Follow the prompts to connect your domain**

## Files in your `public` folder:
- `index.html` - Home page
- `about.html` - About page
- `contact.html` - Contact page
- `services.html` - Services page
- `static/` - CSS, JS, Images
- `vercel.json` - Vercel configuration

## Connect Domain (helixltd.co)

After deploying, add these DNS records at your domain registrar:

| Type | Name | Value |
|------|------|-------|
| A | @ | 76.76.21.21 |
| CNAME | www | cname.vercel-dns.com |

## That's it! 🎉

Your website will be live at:
- `https://your-project.vercel.app` (immediately)
- `https://helixltd.co` (after DNS propagation, ~24-48 hours)
