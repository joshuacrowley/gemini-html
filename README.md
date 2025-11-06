# 🍳 Gemini API Cooking Demos

A collection of interactive HTML demos showcasing the capabilities of Google's Gemini API through cooking-themed examples. Each demo is a standalone HTML file that you can run directly in your browser - no build tools or server required!

## 🚀 Quick Start

1. **Get a free API key** from Google AI Studio: https://aistudio.google.com/api-keys
2. **Download or clone** this repository
3. **Drag and drop** any HTML file into your browser
4. **Enter your API key** when prompted (it's stored locally in your browser)
5. **Start exploring!**

## 📚 Demo Catalog

### 1. Text Generation (`01-text-generation.html`)
📝 **Recipe Writing Assistant**  
Generate creative and sophisticated recipes with AI. Create gourmet "Invisible Soup" recipes with adjustable creativity levels.
- Temperature control
- System instructions
- Creative writing

### 2. Image Generation (`02-image-generation.html`) 🍌
🍽️ **AI Food Plating Assistant**  
Transform an empty plate into a beautifully plated dish with AI. See before and after comparisons of your culinary creations.
- Food photography generation
- Before/after comparisons
- Professional plating

> **Note:** This demo uses Imagen (Nanobananas) and requires a **paid API token** to function.

### 3. Speech Generation (`03-speech-generation.html`)
🔊 **Cooking Show Narrator**  
Create dramatic audio for cooking competitions. Generate professional narrator voices with emphasis and timing.
- Multiple voice styles
- Adjustable speech rate
- Dramatic effects

### 4. Long Context Processing (`04-long-context.html`)
📚 **Cookbook Analyst**  
Process long cookbook chapters to extract specific recipes. Analyze large documents for desserts and ingredients.
- PDF processing
- Recipe extraction
- Large document handling

### 5. Structured Output (`05-structured-output.html`)
📊 **Restaurant Menu Database**  
Convert menu descriptions into structured JSON data. Transform text into organized database-ready formats.
- JSON schema validation
- Data structuring
- Menu parsing

### 6. Thinking Mode (`06-thinking.html`)
🧠 **Kitchen Problem Solver**  
Solve complex cooking puzzles with step-by-step reasoning. Watch AI think through cake baking optimization problems.
- Step-by-step reasoning
- Math problems
- Logical deduction

### 7. Document Processing (`07-document-processing.html`)
📄 **Recipe Card Digitizer**  
Extract text from handwritten recipe cards. Digitize grandma's cursive writing and margin notes with AI.
- Handwriting OCR
- Image upload support
- Text structure preservation

### 8. Image Understanding (`08-image-understanding.html`)
🖼️ **Fridge Inspector**  
Analyze fridge contents and get meal suggestions. AI identifies ingredients and recommends recipes you can make.
- Object detection
- Meal planning
- Photo analysis

### 9. Video Understanding (`09-video-understanding.html`)
📹 **Cooking Tutorial Analyzer**  
Extract step-by-step instructions from cooking videos. Generate timestamps and chapter markers automatically.
- Video processing
- Timestamp generation
- Step detection

### 10. Audio Processing (`10-audio.html`)
🎤 **Kitchen Timer Interpreter**  
Transcribe cooking podcasts and extract timing information. Find all cooking durations mentioned in audio.
- Audio transcription
- Time extraction
- Timeline creation

### 11. Function Calling (`11-function-calling.html`)
🔧 **Smart Kitchen Assistant**  
Control kitchen timers with natural language. Set, adjust, and manage multiple cooking timers through conversation.
- Natural language processing
- Timer control
- Function calls

### 12. Google Search Integration (`12-google-search.html`)
🔍 **Restaurant Fact Checker**  
Verify restaurant claims with real-time search. Check Michelin stars, opening dates, and current pricing information.
- Real-time search
- Fact verification
- Source citations

### 13. Code Execution (`13-code-execution.html`)
💻 **Recipe Scaler Calculator**  
Generate and execute code to scale recipe ingredients. Create functions that handle decimal values and proper rounding.
- Code generation
- Live execution
- Multiple languages

### 14. URL Context Processing (`14-url-context.html`)
🌐 **Recipe Blog Analyzer**  
Extract and compare recipes from food blog URLs. Analyze baking times, temperatures, and ingredient differences.
- URL processing
- Recipe extraction
- Comparison analysis

## 🎯 How to Use

### Running the Demos

Simply open the `index.html` file in your browser for an overview of all demos, or open any individual demo file directly:

```bash
# Option 1: Open the main index
open index.html

# Option 2: Open a specific demo
open 01-text-generation.html
```

Or just drag and drop any `.html` file into your browser window!

### API Key Setup

Each demo will prompt you to enter your Google AI API key on first use. The key is stored in your browser's localStorage and persists across sessions. You only need to enter it once per demo.

**Privacy Note:** Your API key is stored locally in your browser and is never sent to any third parties except Google's API endpoints.

## ⚠️ Important Notes

- **Demo #2 (Image Generation)** requires a **paid API token** as it uses the Imagen API (Nanobananas)
- All other demos work with the free API tier
- API keys are stored in your browser's localStorage
- No server or build process is required
- Each file is completely standalone

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no frameworks required
- Uses the `@google/generative-ai` SDK via CDN
- Responsive design works on desktop and mobile
- All demos include error handling and loading states

## 📖 Resources

- **Get API Key:** https://aistudio.google.com/api-keys
- **Gemini API Documentation:** https://ai.google.dev/gemini-api/docs
- **API Reference:** https://ai.google.dev/api

## 🤝 Contributing

These demos are designed to be educational examples. Feel free to:
- Use them as templates for your own projects
- Modify and extend them
- Share them with others learning about AI

## 📄 License

These demos are provided as-is for educational purposes.

---

**Happy Cooking with AI! 🧑‍🍳✨**

