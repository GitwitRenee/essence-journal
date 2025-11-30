# essence-journal
AI-powered journal that transforms thoughts and feelings into visual art with sentiment analysis and uplifting insights


## 🌟 Live Demo

**[Visit Essence Journal](https://gitwitrenee.github.io/essence-journal/)**

## ✨ Features

- 📝 **Expressive Journaling**: Write your thoughts with thoughtful, rotating prompts
- 🎨 **AI-Generated Art**: Transform your entries into unique visual metaphors
- 💭 **Sentiment Analysis**: Understand the emotions behind your words
- 🌈 **Dynamic Color Palettes**: Each entry gets its own mood-based colors
- 💡 **Philosophical Insights**: Receive deep, meaningful reflections on your thoughts
- 🔄 **Beautiful UI**: Dark theme with smooth animations and transitions

## 🛠️ Setup Instructions

### Prerequisites

You'll need a **Google AI (Gemini) API key** to use this application.

### Getting Your API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click "Create API Key"
4. Copy your new API key

### Adding Your API Key

1. Open the `index.html` file in a text editor
2. Find line 25: `const API_KEY = 'YOUR_GEMINI_API_KEY_HERE';`
3. Replace `YOUR_GEMINI_API_KEY_HERE` with your actual API key
4. Save the file

**Example:**
```javascript
const API_KEY = 'AIzaSyD....your-actual-key-here';
```

⚠️ **Security Note**: Never commit your API key to a public repository. For local development only.

## 🚀 Running Locally

1. Clone this repository:
```bash
git clone https://github.com/GitwitRenee/essence-journal.git
cd essence-journal
```

2. Add your API key to `index.html` (see above)

3. Open `index.html` in your web browser

## 📋 How It Works

1. **Write**: Express your thoughts in response to a thoughtful prompt
2. **Analyze**: AI analyzes your entry for sentiment and themes
3. **Visualize**: An AI-generated image represents your inner world
4. **Reflect**: Receive a philosophical insight based on your entry
5. **Share**: Copy your insight to share with others

## 🎯 Technology Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Styling**: Tailwind CSS (CDN)
- **AI Models**: 
  - Google Gemini 2.0 Flash (text analysis)
  - Imagen 3.0 (image generation)

## 🔧 API Configuration

The application uses the following Google AI models:
- `gemini-2.0-flash-exp` for sentiment analysis and insight generation
- `imagen-3.0-generate-001` for visual art generation

## 📝 License

This project is open source and available for personal use.

## 🙏 Credits

Created with ❤️ using Google's Gemini AI

---

**Note**: This application requires an active internet connection and a valid Google AI API key to function properly.
