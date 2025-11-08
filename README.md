# Activity Tracker - GitHub Pages Setup

This folder contains the support and privacy policy pages for the Activity Tracker app.

## Files

- `index.html` - Support page with FAQ and contact info
- `privacy.html` - Comprehensive privacy policy
- `README.md` - This file

## How to Upload to GitHub Pages

### Step 1: Create a New GitHub Repository

1. Go to https://github.com and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Repository name: `activity-tracker-support`
4. Description: `Support and privacy pages for Activity Tracker app`
5. Make it **Public** ✅
6. Check **"Add a README file"** ✅
7. Click **"Create repository"**

### Step 2: Upload the HTML Files

**Option A: Via GitHub Web Interface (Easiest)**

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop `index.html` and `privacy.html` into the upload area
3. Add commit message: "Add support and privacy pages"
4. Click **"Commit changes"**

**Option B: Via Git Command Line**

```bash
# Clone the new repository
git clone https://github.com/YOUR_USERNAME/activity-tracker-support.git
cd activity-tracker-support

# Copy the HTML files
cp /path/to/index.html .
cp /path/to/privacy.html .

# Commit and push
git add index.html privacy.html
git commit -m "Add support and privacy pages"
git push origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings**
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 4: Get Your URLs

After deployment, your pages will be available at:

- **Support URL:** `https://YOUR_USERNAME.github.io/activity-tracker-support/`
- **Privacy Policy URL:** `https://YOUR_USERNAME.github.io/activity-tracker-support/privacy.html`

**These are the URLs you'll use in App Store Connect!**

### Step 5: Test Your Pages

1. Open the URLs in your browser
2. Check that all links work
3. Verify the email address is correct
4. Test on mobile devices

## Customization

You can customize these pages by editing the HTML files:


- Change colors (currently using #007AFF blue)
- Add more FAQ questions
- Update the version number in footer

## Support

If you need help setting this up, reach out!

---

**Note:** Remember to update App Store Connect with:
- Support URL: Your GitHub Pages URL
- Privacy Policy URL: Your GitHub Pages privacy.html URL
