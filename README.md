# Gymnasium am Turmhof - Germany-China School Exchange Website

Welcome to the website for the Germany-China school exchange program at Gymnasium am Turmhof!

## 📋 Overview

This is a simple, professional website designed to:
- Showcase information about Gymnasium am Turmhof
- Display photos and videos of the school
- Share a blog with news and updates
- Provide an easy way for Chinese schools to contact us about exchange opportunities

## 🚀 Getting Started

### What You Need to Do:

1. **Customize the Content** (in `index.html`):
   - Replace placeholder text with your school's actual information
   - Add your email address in the contact section
   - Add your school's phone number and address
   - Update the contact email (`exchange@gymnasium-turmhof.de`)

2. **Add Your Photos** (Replace placeholders):
   - Go to the Gallery section and replace placeholder images
   - You can either:
     - Upload images to a folder in this repository, OR
     - Use image hosting services like Imgur, Cloudinary, or GitHub's CDN
   - Update the image URLs in `index.html`

3. **Add Your Video**:
   - Film a short introduction video (30 seconds - 2 minutes)
   - Upload it to YouTube
   - Copy the YouTube video ID (the long string in the URL)
   - Replace `dQw4w9WgXcQ` in the Video section with your video ID
   - Find your YouTube video ID: Go to your video, the URL looks like: `https://www.youtube.com/watch?v=YOUR_VIDEO_ID`

4. **Deploy Your Website** (Make it live on the internet):
   
   **Option A: GitHub Pages (Easiest - FREE)**
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "main" branch as the source
   - Wait 1-2 minutes
   - Your site will be at: `https://nfpm62c8fh-glitch.github.io/gymnasium-am-turmhof-exchange`

   **Option B: Netlify (Also FREE)**
   - Go to https://www.netlify.com
   - Click "New site from Git"
   - Connect your GitHub repository
   - Netlify will automatically deploy your site

5. **Add Blog Posts**:
   - Edit the blog section in `index.html`
   - Update dates and content
   - Add more blog posts by duplicating the `<article>` blocks

## 📁 File Structure

```
gymnasium-am-turmhof-exchange/
├── index.html          # Main website file
├── styles.css          # Styling and design
├── script.js           # Interactivity
└── README.md           # This file
```

## 🎨 Colors Used

- Primary Blue: `#003366` (header, headings)
- Orange: `#FF6B35` (buttons, accents)
- Gold: `#FDB833` (highlights)

Feel free to customize the colors by editing the CSS variables in `styles.css`.

## 💡 Tips

- **Responsive Design**: The website works on phones, tablets, and desktop computers
- **Search Engines**: Add keywords in the `<title>` tag to help people find your site on Google
- **Contact Form**: Currently shows a confirmation message. To actually send emails, you'll need a backend service (we can add this later if needed)
- **Navigation**: The menu links smoothly scroll to each section

## 📸 Image Guidelines

- Use high-quality photos (1200x800px or larger)
- Compress images to keep the website fast (use tools like TinyPNG)
- Show diverse aspects of school life: students, classrooms, events, sports, facilities

## 🔗 How to Share

Once deployed, share the URL with Chinese schools:
- `https://nfpm62c8fh-glitch.github.io/gymnasium-am-turmhof-exchange` (GitHub Pages)
- Or the Netlify URL if you use that

## ❓ Need Help?

1. **Adding images**: Follow the "Add Your Photos" section above
2. **Changing colors**: Edit the `--primary-color`, `--secondary-color`, etc. in `styles.css`
3. **Adding more sections**: Copy existing sections and modify the content
4. **Deployment issues**: Check GitHub Pages settings in your repository

## 📧 Future Enhancements

- Email form submission (requires backend)
- Student profiles/profiles of exchange participants
- Calendar/timeline of exchange events
- Photo carousel/slideshow
- Multi-language support (German/Chinese)
- Event registration form

Good luck with your exchange program! 🌍
