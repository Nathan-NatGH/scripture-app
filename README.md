# Scripture of the Day 📖

A beautiful, minimalist web app that displays daily Bible verses with AI-generated age-appropriate explanations.

## Features

- 🎯 **Random Bible Verses** - Fetches from 35+ popular scriptures
- 🤖 **AI-Powered Summaries** - Claude AI generates explanations for 4 age levels (5yo, 10yo, 15yo, Adult)
- 📱 **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- 🎨 **Minimalist UI** - Clean, distraction-free interface inspired by wordcounter.net
- 🌐 **Free Bible API** - Uses Bible Brain API (no API key needed)
- ⚡ **Fast & Lightweight** - Built with React + Vite

## Quick Start (Local Development)

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser:**
   ```
   http://localhost:5173
   ```

## Deployment Instructions

### Option 1: Vercel (Recommended - Easiest!) 🚀

**Method A: Using Vercel CLI**
1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Follow the prompts - that's it!

**Method B: Using Vercel Website**
1. Go to [vercel.com](https://vercel.com)
2. Sign up/login (free)
3. Click "Add New" → "Project"
4. Upload this folder or connect GitHub
5. Click "Deploy"
6. Your app is live! 🎉

### Option 2: Netlify

1. Go to [netlify.com](https://netlify.com)
2. Sign up/login (free)
3. Drag and drop the `scripture-app` folder
4. Wait 30 seconds - done!

### Option 3: GitHub Pages

1. Build the app:
   ```bash
   npm run build
   ```

2. Deploy the `dist` folder to GitHub Pages

### Option 4: Any Static Host

Build the app and upload the `dist` folder to any static hosting:
```bash
npm run build
```

The `dist` folder contains everything needed!

## Project Structure

```
scripture-app/
├── src/
│   ├── App.jsx          # Main app component
│   ├── main.jsx         # React entry point
│   └── index.css        # Tailwind CSS
├── index.html           # HTML template
├── package.json         # Dependencies
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind configuration
└── README.md           # This file
```

## Tech Stack

- **React 18** - UI framework
- **Vite** - Build tool (super fast!)
- **Tailwind CSS** - Styling
- **Bible Brain API** - Scripture data
- **Claude AI API** - Age-appropriate summaries

## API Information

### Bible Brain API
- **URL:** https://4.dbt.io/api/bible/verse
- **Cost:** FREE (no API key needed)
- **Translation:** English Standard Version (ESV)
- **Documentation:** https://www.faithcomesbyhearing.com/

### Claude AI API
- **Used for:** Generating summaries
- **How it works:** Makes requests from the browser to generate age-appropriate explanations
- **Note:** The Claude API calls are handled client-side using the Anthropic API integration available in this environment

## Customization Ideas

Want to extend this app? Here are some ideas:

- Add more Bible translations (NIV, KJV, NLT)
- Allow users to search specific verses
- Add a "Favorite verses" feature
- Daily notifications
- Share verses on social media
- Dark mode
- Multiple languages (Spanish, Portuguese)
- Add audio playback

## Browser Support

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## License

Free to use for personal or ministry purposes!

## Credits

Built with ❤️ using:
- Bible Brain API for scripture data
- Claude AI for intelligent summaries
- React + Vite for the framework
- Tailwind CSS for beautiful styling

---

**Need Help?**

If you run into issues:
1. Make sure Node.js is installed (v18+)
2. Delete `node_modules` and run `npm install` again
3. Check that ports 5173 (dev) or 4173 (preview) aren't in use

**Happy Coding! 🙏**
# scripture-app
# scripture-app
# scripture-app
