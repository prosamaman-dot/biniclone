# Bini AI - Serverless Version 🚀

A modern ChatGPT-style AI chatbot built with **pure JavaScript** - no backend server required! Host it anywhere for free!

## ✨ Features

- **🤖 Bini AI**: Biniyam Lemma's digital clone - Ethiopian teenager from Bure dreaming to become a millionaire through software engineering. Calm, funny, practical, and empathetic personality
- **💾 Persistent Storage**: Conversations saved in browser localStorage
- **🛠️ Tool Selection**: Create Image, Search Web, Write Code, Deep Research, Think Longer
- **📸 Image Upload**: Attach and analyze images
- **🎨 Modern UI**: ChatGPT-style interface with dark mode support
- **📱 Responsive**: Works on desktop, tablet, and mobile
- **🌐 Serverless**: No backend server needed - runs entirely in the browser!

## 🚀 Quick Start

1. **Download the files**:
   - `serverless-index.html`
   - `modern-style.css`
   - `serverless-script.js`

2. **Open in browser**:
   - Simply open `serverless-index.html` in any modern browser
   - Or host on any static hosting platform

3. **Start chatting**:
   - Bini AI is ready to chat about becoming a millionaire, software engineering, life goals, and more!

## 🌐 Free Hosting Options

### GitHub Pages (Recommended)
1. Create a new GitHub repository
2. Upload the 3 files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" → "main"
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the 3 files to deploy
3. Get instant free hosting with custom domain support

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

### Glitch
1. Go to [glitch.com](https://glitch.com)
2. Create a new project
3. Upload the files
4. Get instant hosting

## 🔧 How It Works

- **Frontend**: Pure HTML, CSS, JavaScript
- **AI Backend**: Direct calls to Google Gemini API from the browser
- **Storage**: Browser localStorage (no database needed)
- **No Server**: Everything runs client-side!

## 🛠️ Customization

### Change API Key
Edit `serverless-script.js` and update the `geminiApiKey` variable:
```javascript
this.geminiApiKey = 'YOUR_GEMINI_API_KEY_HERE';
```

### Modify Personality
Edit the prompt in the `callGeminiAPI` function to change Bini AI's personality. Current personality: calm, kind, funny, hardworking, empathetic, practical with Ethiopian English style.

### Add Features
The modular JavaScript structure makes it easy to add new features like:
- Voice recording
- File uploads
- Custom tools
- Themes

## 📁 File Structure

```
ai-clone/
├── serverless-index.html    # Main HTML file
├── modern-style.css         # Beautiful CSS styling
├── serverless-script.js     # JavaScript backend logic
└── README.md               # This file
```

## 🔒 Security Note

The Gemini API key is visible in the client-side code. For production use, consider:
- Using environment variables
- Implementing a proxy server
- Using serverless functions to hide the API key

## 🎯 Features Included

- ✅ Modern ChatGPT-style UI
- ✅ Bini AI personality: calm, funny, practical, empathetic, millionaire-focused mindset
- ✅ Tool selection (Image, Search, Code, Research, Think)
- ✅ Image upload and analysis
- ✅ Conversation history persistence
- ✅ Dark mode support
- ✅ Responsive design
- ✅ Voice recording placeholder
- ✅ Keyboard shortcuts
- ✅ Auto-resizing textarea

## 🚀 Deploy Now!

1. **GitHub Pages**: Upload to GitHub and enable Pages
2. **Netlify**: Drag and drop for instant deployment
3. **Vercel**: Connect GitHub repo for automatic deployments
4. **Any static host**: Works on any platform that serves HTML files

## 💡 Tips

- The app works offline for viewing conversations
- Conversations are stored locally in your browser
- Each browser gets its own conversation history
- No server maintenance required!

---

**Built with ❤️ by Bini AI - "The world is not perfect, but we can't make it perfect now" 😎💪**
# Bini AI Clone - Dream to Become a Millionaire
# biniclone
