# 💝 Valentine's Week 2026 - Complete Love Journey 💝

A beautiful, interactive 8-day Valentine's Week website for Soha, featuring unique designs and heartfelt messages for each day from February 7-14, 2026.

## ✨ What's Included

This Valentine's Week website features **8 beautiful pages**:

1. **Index Page** - Main hub showing all days of the week
2. **Rose Day (Feb 7)** 🌹 - Red & Deep Pink theme
3. **Propose Day (Feb 8)** 💌 - Romantic Red & Blush Pink theme
4. **Chocolate Day (Feb 9)** 🍫 - Chocolate Brown & Gold theme
5. **Teddy Day (Feb 10)** 🧸 - Teddy Beige & Pastel Pink theme
6. **Promise Day (Feb 11)** 🤝 - Trust Blue & Pure White theme
7. **Hug Day (Feb 12)** 🤗 - Peach & Soft Rose theme
8. **Kiss Day (Feb 13)** 💋 - Passion Red & Maroon theme
9. **Valentine's Day (Feb 14)** ❤️ - Interactive questions with love meter (Classic Red & Romantic Pink)

## 🎨 Features

- **Unique Design for Each Day** - Every page has its own color scheme, fonts, and animations
- **Romantic Messages** - Personalized heartfelt messages for Soha
- **Beautiful Animations** - Floating hearts, petals, sparkles, and more
- **Interactive Valentine's Day** - Special page with questions, love meter, and celebration
- **Easy Navigation** - Navigate between days seamlessly
- **Mobile Responsive** - Looks beautiful on all devices
- **Background Music** - Optional music on Valentine's Day page

## 🚀 How to Deploy

### Option 1: GitHub Pages (Free & Easy)

1. **Create a GitHub Account** (if you don't have one)
   - Go to [github.com](https://github.com)
   - Sign up for free

2. **Create a New Repository**
   - Click the "+" icon in the top right
   - Select "New repository"
   - Name it: `valentine-week-2026` (or any name you prefer)
   - Make it **Public**
   - Click "Create repository"

3. **Upload Your Files**
   - Click "uploading an existing file"
   - Drag and drop ALL the files from this folder:
     - index.html
     - rose-day.html
     - propose-day.html
     - chocolate-day.html
     - teddy-day.html
     - promise-day.html
     - hug-day.html
     - kiss-day.html
     - valentine-day.html
     - config.js
     - script.js
     - styles.css
     - theme.js
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to repository "Settings"
   - Click "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 2-3 minutes

5. **Get Your Website Link**
   - Your site will be live at: `https://yourusername.github.io/valentine-week-2026`
   - Share this link with Soha! 💕

### Option 2: Netlify (Custom Domain, Also Free)

1. **Sign Up on Netlify**
   - Go to [netlify.com](https://netlify.com)
   - Sign up for free

2. **Deploy Your Site**
   - Drag and drop the entire folder
   - Or connect your GitHub repository
   - Netlify will automatically deploy

3. **Custom Domain (Optional)**
   - Click "Domain settings"
   - Choose a custom subdomain like: `soha-valentine-2026.netlify.app`

## 🎵 Adding Background Music (Optional)

To add your own romantic song to the Valentine's Day page:

1. **Upload to Cloudinary**
   - Go to [cloudinary.com](https://cloudinary.com) and sign up
   - Upload your MP3 file (keep under 10MB)
   - Copy the URL

2. **Update config.js**
   - Open `config.js`
   - Find the `music` section
   - Replace `musicUrl` with your Cloudinary URL

```javascript
music: {
    enabled: true,
    autoplay: true,
    musicUrl: "YOUR_CLOUDINARY_URL_HERE",
    startText: "🎵 Play Music",
    stopText: "🔇 Stop Music",
    volume: 0.5
}
```

## 💝 Customization

All the messages are already personalized for Soha, but you can customize further:

### Changing Messages

Edit any `.html` file to change the messages. Look for the `<div class="message">` sections.

### Changing Colors

Each day already has its own unique color scheme, but you can adjust:
- Edit the `style` section in each day's HTML file
- Look for `background: linear-gradient(...)` to change colors

### Changing the Valentine's Day Interactive Page

Edit `config.js` to customize:
- Questions
- Button text
- Celebration messages
- Love meter messages
- Colors and animations

## 📱 Testing Before Sending

1. Open `index.html` in your web browser
2. Click through each day to test
3. Test on mobile by resizing your browser
4. Make sure all links work
5. Test the Valentine's Day interactive questions

## 💌 How to Share

Once deployed, you can:

1. **Send via Email**
   - Compose a romantic email
   - Include your website link
   - Send on February 7th or earlier!

2. **Send via Text/WhatsApp**
   - Share the link directly
   - Add a cute message like: "I made something special for you 💕"

3. **Show in Person**
   - Open it on your phone or laptop
   - Show her during a special moment

## 🎯 Recommended Timeline

- **Before Feb 7**: Send her the link
- **Feb 7-13**: She visits each day for a new message
- **Feb 14**: The grand finale with the interactive Valentine's Day experience!

## 📝 Files Included

```
valentine-week-2026/
├── index.html              # Main hub page
├── rose-day.html          # February 7
├── propose-day.html       # February 8
├── chocolate-day.html     # February 9
├── teddy-day.html         # February 10
├── promise-day.html       # February 11
├── hug-day.html          # February 12
├── kiss-day.html         # February 13
├── valentine-day.html    # February 14
├── config.js             # Valentine's Day configuration
├── script.js             # Valentine's Day interactive features
├── styles.css            # Valentine's Day styling
├── theme.js              # Theme application
└── README.md             # This file
```

## 💖 Tips for Maximum Impact

1. **Send Early**: Share the link on February 6th so she can start on Rose Day
2. **Daily Reminders**: Send her a cute text each day reminding her to check the website
3. **Be Present**: On Valentine's Day (Feb 14), be with her when she completes the interactive questions
4. **Print Backup**: Consider printing out each day's message as a backup gift

## 🐛 Troubleshooting

**Links not working?**
- Make sure all files are in the same folder
- Check that filenames match exactly (case-sensitive)

**Music not playing?**
- Make sure you've added a valid Cloudinary URL
- Some browsers block autoplay - use the play button

**Website looks different on mobile?**
- This is normal, it's responsive!
- Test on your actual phone before sharing

## ❤️ Made with Love

Created with love for Soha.
Every line of code, every animation, every word - crafted to make her smile.

---

**Ready to make Valentine's Week 2026 unforgettable? Deploy your website and share the love! 💕**
