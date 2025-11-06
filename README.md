# OnceWas Website - Complete with Core Rule Book Integration

## 🎉 What's Included

Your complete OnceWas RPG website with **fully integrated Core Rule Book**!

### Files:
```
oncewas-final/
├── index.html                          # Main website homepage
├── core-rules.html                     # PDF viewer page (NEW!)
├── styles.css                          # All styling
├── script.js                           # Interactive features
├── Core_Rule_Book.pdf                  # Your 103-page rulebook (22MB) (NEW!)
├── Core_Rule_Book_Cover.jpg            # Rulebook cover image (NEW!)
├── OnceWas_logo.png                    # Your logo
├── Book_One_Cover.jpg                  # Novel cover
├── world_map_RW.jpg                    # World map
├── The_Ogres_of_Worros_Woods.jpg      # Adventure A1 cover
├── The_Meldorin_Winery.jpg            # Adventure A2 cover
├── Tower_of_the_Immortal_Orc.jpg      # Adventure A3 cover
├── Werewolves_of_Orckrag.jpg          # Adventure A4 cover
└── Silvandor_and_the_Shattered_Light.jpg  # Adventure A5 cover
```

**Total Size:** 50MB

---

## ✨ What's New - Core Rule Book Integration

### 1. **New PDF Viewer Page** (`core-rules.html`)
A professional, dedicated page for viewing your Core Rule Book:
- ✅ Embedded PDF viewer (reads right in the browser)
- ✅ Download PDF button
- ✅ Open in new tab option
- ✅ Link to buy print copy on Amazon
- ✅ Mobile-friendly
- ✅ Fallback for browsers that don't support embedded PDFs

### 2. **Updated Main Website**
Your homepage now features:
- ✅ Core Rule Book cover image in the "What is OnceWas?" section
- ✅ Clickable cover that takes you to the PDF viewer
- ✅ All "View Core Rules" buttons updated to work properly
- ✅ Download PDF option in footer and CTA sections
- ✅ Three options: View Online, Download PDF, Buy Print

### 3. **Three Ways to Access the Rules**
Your visitors can now:
1. **View Online Free** → Opens `core-rules.html` with embedded PDF
2. **Download PDF Free** → Downloads `Core_Rule_Book.pdf` 
3. **Buy Print Copy** → Links to Amazon (add your ASIN)

---

## 🚀 How It Works

### For Visitors:

**Option 1: View Online**
1. Click "View Core Rules Online" anywhere on the site
2. Opens the PDF viewer page
3. PDF loads right in the browser
4. Can scroll, zoom, navigate pages
5. Works on desktop, tablet, and mobile

**Option 2: Download PDF**
1. Click "Download PDF"
2. Gets the 22MB PDF file
3. Can read offline, print, or save

**Option 3: Buy Print**
1. Click "Buy Print Copy"
2. Goes to Amazon (you'll need to add your ASIN)

---

## 📋 Upload to Netlify

Since you already have a Netlify site, here's how to update it:

### Method 1: Drag & Drop (Easiest)
1. Go to your **Netlify dashboard** (app.netlify.com)
2. Click on your OnceWas site
3. Go to **"Deploys"** tab
4. Scroll down to the drag-and-drop area
5. **Drag the entire `oncewas-final` folder** onto it
6. Wait 30-60 seconds for processing
7. **Done!** Your site is live with the PDF

### Method 2: Manual Upload
1. Log into Netlify
2. Go to your site → **Settings** → **Domain Management**
3. Note your site URL
4. Click **"Deploys"** → **"Upload Files"**
5. Select all files from `oncewas-final`
6. Upload

---

## 🔧 Customization

### Add Your Amazon Print Link
In both `index.html` and `core-rules.html`, find:
```html
href="https://www.amazon.com/dp/YOUR-ASIN-HERE"
```

Replace `YOUR-ASIN-HERE` with your actual Amazon ASIN when you have it.

### Adjust PDF Settings
In `core-rules.html`, the PDF embed has these parameters:
```html
Core_Rule_Book.pdf#toolbar=1&navpanes=1&scrollbar=1
```

You can adjust:
- `toolbar=0` - Hide the PDF toolbar
- `navpanes=0` - Hide the navigation panes
- `page=5` - Open to specific page (e.g., `#page=5`)
- `zoom=150` - Set zoom level

### Change Colors/Styling
Edit `styles.css` - the color variables are at the top:
```css
:root {
    --primary-color: #8b4513;
    --accent-gold: #d4af37;
    /* etc. */
}
```

---

## 📱 Mobile Experience

The PDF viewer is fully responsive:
- ✅ Adjusts to screen size
- ✅ Touch-friendly controls
- ✅ Zoom and scroll work great
- ✅ Download button prominent on mobile

---

## 💡 Pro Tips

### For Best Performance:
1. **PDF Size**: At 22MB, it loads in 2-5 seconds on good connections
2. **Hosting**: Netlify's CDN will serve it fast worldwide
3. **Caching**: Once loaded, browsers cache it for return visitors

### If PDF is Too Large:
If you want faster loading, you could:
1. Create a "web optimized" version at 100 DPI (smaller file)
2. Keep the 22MB version for downloads
3. Use the smaller one in the embed

But honestly, 22MB is fine for most users!

---

## ✅ Testing Checklist

Before going live, test these:

**Homepage:**
- [ ] "Start Your Adventure" button in header → Goes to PDF viewer
- [ ] "View Core Rules Online" in hero → Goes to PDF viewer
- [ ] Core Rule Book cover shows in "What is OnceWas" section
- [ ] Clicking cover → Goes to PDF viewer
- [ ] "View Rules Online" in final CTA → Goes to PDF viewer
- [ ] "Download PDF" button → Downloads the file
- [ ] Footer "View Core Rules" link → Goes to PDF viewer

**PDF Viewer Page:**
- [ ] PDF loads and displays
- [ ] Can scroll through pages
- [ ] "Download PDF" button works
- [ ] "Open in New Tab" opens PDF in new window
- [ ] Navigation back to home works
- [ ] Looks good on mobile

---

## 🎯 What Visitors Will See

1. **Homepage** - Beautiful site with adventure covers, novel info, etc.
2. **Click "View Core Rules"** - Opens dedicated PDF viewer
3. **PDF Loads** - Full 103-page rulebook right in browser
4. **Can Navigate** - Scroll, zoom, jump to pages
5. **Download Option** - One click to save the PDF
6. **Buy Print** - Link to Amazon for physical copy

---

## 🛠 Troubleshooting

**PDF Won't Display in Browser?**
- Some browsers (especially mobile Safari) may not embed PDFs well
- The "Download PDF" and "Open in New Tab" buttons are fallbacks
- This is normal browser behavior

**File Too Large to Upload?**
- Netlify free tier allows 100MB deployments
- Your 50MB site is well within limits
- If you hit issues, you can compress images

**Links Not Working?**
- Make sure all files are in the same directory
- File names are case-sensitive on servers
- Check that you uploaded everything, including the PDF

---

## 📞 Next Steps

1. **Test Locally** - Open `index.html` in your browser to preview
2. **Upload to Netlify** - Drag the folder to update your live site
3. **Add Amazon ASIN** - When you have print copies available
4. **Share!** - Your Core Rule Book is now accessible to everyone

---

## 🎊 Summary

You now have:
- ✅ Professional website
- ✅ Embedded PDF viewer
- ✅ Free online access to Core Rules
- ✅ Download option
- ✅ Beautiful cover image integration
- ✅ Mobile-friendly design
- ✅ Ready to upload to Netlify

Your visitors can now:
- Read the rules online
- Download the PDF
- Buy a print copy
- All from one beautiful website!

**You're ready to launch!** 🚀

---

Need help with anything? Just ask!
