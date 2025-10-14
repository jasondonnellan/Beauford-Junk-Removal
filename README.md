# FastHaul Junk Removal Website

A simple, professional website for a junk hauling service, designed to be deployed on GitHub Pages.

## Complete Deployment Guide

### Step 1: Set Up Web3Forms Contact Form
1. Go to https://web3forms.com
2. Sign up for a free account
3. Get your access key from the dashboard
4. In `index.html`, replace `YOUR_ACCESS_KEY_HERE` with your actual access key
5. Forms will be sent to the email address associated with your Web3Forms account

### Step 2: Create GitHub Repository
1. Go to https://github.com and create a new repository
2. Name it something like `junk-removal-site` or `fasthaul-website`
3. Make it public (required for free GitHub Pages)
4. Don't initialize with README, .gitignore, or license

### Step 3: Push Your Code to GitHub
```bash
# From your project directory
git add .
git commit -m "Initial FastHaul junk removal website"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo-name.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click the "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"

### Step 5: Access Your Live Site
- Your site will be available at: `https://yourusername.github.io/your-repo-name`
- It may take 5-10 minutes to deploy initially
- Every time you push changes, the site will automatically update

### Step 6: Test Everything
1. Visit your live site URL
2. Test the contact form by filling it out
3. Check that phone numbers are clickable on mobile
4. Verify the site looks good on desktop and mobile

### Deployment Requirements Summary:
- GitHub account (free)
- Web3Forms account (free)
- Replace access key in HTML file
- Repository must be public for free GitHub Pages
- Files must be in root directory (not in a subfolder)

## Site Features

- **Contact Form**: Web3Forms integration for lead capture
- **Phone Numbers**: Multiple contact numbers displayed
- **Services**: Residential, Commercial, and Yard Waste removal
- **Mobile Responsive**: Works on all devices
- **Professional Design**: Clean, modern styling

## Current Business Information

The site is set up for FastHaul Junk Removal with:
- Phone: (520) 451-0767, (520) 729-5116, (520) 3310-9972
- Services: Residential, Commercial, Yard Waste & Outdoor Cleanup
- Features: Free Estimates, Same-Day Service, Family Owned
- Tagline: "Clearing your clutter, supporting your community, and making your life easier"

## Customization

To customize for your business, edit the following in `index.html`:
- Company name
- Phone numbers
- Email addresses
- Service descriptions
- Any other business-specific details

## File Structure

- `index.html` - Main webpage
- `styles.css` - Styling and layout
- `README.md` - This file

The site is fully responsive and will work well on mobile devices.