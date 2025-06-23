# Deployment Guide

## Replit Deployment

Your portfolio is already deployed on Replit and accessible at your unique Replit URL.

### Steps to Deploy on Replit:
1. Click the "Deploy" button in your Replit project
2. Choose "Autoscale" deployment for best performance
3. Your portfolio will be live at `https://your-repl-name.your-username.replit.app`

## GitHub Setup

### 1. Create GitHub Repository
1. Go to [GitHub](https://github.com)
2. Click "New repository"
3. Name: `karthikeya-portfolio`
4. Description: `Netflix-themed portfolio website showcasing my professional journey`
5. Make it public
6. Don't initialize with README (we already have one)

### 2. Upload Code to GitHub
Use these commands in your terminal:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit your code
git commit -m "Initial commit: Netflix-themed portfolio website"

# Add GitHub remote (replace with your actual GitHub username)
git remote add origin https://github.com/Karthik77991/karthikeya-portfolio.git

# Push to GitHub
git push -u origin main
```

### 3. Alternative: Upload via GitHub Web Interface
1. Create new repository on GitHub
2. Click "uploading an existing file"
3. Drag and drop all your project files
4. Add commit message: "Netflix-themed portfolio website"
5. Click "Commit changes"

## Other Deployment Options

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will auto-detect it's a Node.js project
3. Deploy with default settings

### Netlify
1. Connect GitHub repository to Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

### Heroku
1. Create new Heroku app
2. Connect to GitHub repository
3. Enable automatic deploys
4. App will be live at `https://your-app-name.herokuapp.com`

## Environment Variables
If you need database functionality:
- `DATABASE_URL`: Your PostgreSQL connection string
- `NODE_ENV`: Set to "production" for live deployment

## Custom Domain (Optional)
After deployment, you can add a custom domain:
1. Purchase domain from provider (GoDaddy, Namecheap, etc.)
2. Configure DNS settings in your deployment platform
3. Add SSL certificate (usually automatic)

Your portfolio is now ready for the world to see!