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
- Pick how adventurous the recipes should be
- Choose the AI's personality (home cook to molecular gastronomist)
- Creative writing

### 2. Image Generation (`02-image-generation.html`) 🍌
🍽️ **AI Food Plating Assistant**  
Transform an empty plate into a beautifully plated dish with AI. See before and after comparisons of your culinary creations.
- Food photography generation
- Before/after comparisons
- Professional plating

> **Note:** This demo uses Nano Banana 2 (`gemini-3.1-flash-image`) and requires a **paid API token** to function.

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
Turn free-flowing menu descriptions into neat, organized data — the kind a spreadsheet or database could use.
- From messy text to tidy tables
- You define the exact format you want back
- Menu parsing

### 6. Thinking Mode (`06-thinking.html`)
🧠 **Kitchen Problem Solver**  
Solve complex cooking puzzles with step-by-step reasoning. Watch AI think through cake baking optimization problems.
- Choose how deeply the AI thinks (quick answer vs. careful reasoning)
- Peek at its step-by-step thought process
- Math problems and logical deduction

### 7. Document Processing (`07-document-processing.html`)
📄 **Recipe Card Digitizer**  
Extract text from handwritten recipe cards. Digitize grandma's cursive writing and margin notes with AI.
- Reads handwriting, even cursive
- Upload a photo of any recipe card
- Keeps the recipe's structure intact

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
Control kitchen timers just by asking. Say "set a timer for 10 minutes for pasta" and the AI presses the buttons for you.
- Plain-English commands
- Set, extend, and cancel multiple timers
- Shows you exactly which action the AI chose to take

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

### 15. Streaming & Multi-Turn Chat (`15-streaming-chat.html`)
👨‍🍳 **Sous-Chef Chat**  
Chat with an AI sous-chef that remembers the whole conversation. Replies appear word by word as they're written, so you're never staring at a spinner.
- Replies stream in live, word by word
- Remembers earlier messages — ask follow-ups like "now make it vegetarian"
- Shows how quickly each reply started

### 16. Conversational Image Editing (`16-image-editing-chat.html`)
🎨 **Dish Refinement Studio**  
Create a picture of a dish, then keep tweaking it — add steam, change the lighting, swap the plate. Each edit builds on the last image.
- Edit the same picture over multiple turns
- A strip of thumbnails lets you revisit every version
- The dish stays recognizably "yours" between edits

> **Note:** Like demo #2, this uses Nano Banana 2 (`gemini-3.1-flash-image`) and requires a **paid API token**.

### 17. Search by Meaning (`17-embeddings-search.html`)
🔎 **Recipe Semantic Search**  
Search a cookbook the way you'd ask a friend. "Something warm for a rainy day" finds soups and stews — even though no recipe contains those words.
- Finds recipes by meaning, not exact keywords
- Results ranked by how closely they match your intent
- Powered by "embeddings" — Gemini turns text into numbers that capture meaning

### 18. Finding Things in Photos (`18-spatial-understanding.html`)
📦 **Pantry Shelf Scanner**  
Upload a photo of your pantry or countertop and watch Gemini find every item and draw a labeled box around it.
- Spots and names each item in the photo
- Draws boxes right on your picture
- Hover a label to highlight where it is

### 19. Real-Time Voice (`19-live-audio.html`)
🎙️ **Hands-Free Cooking Coach**  
Have an actual spoken conversation with a cooking coach while your hands are covered in flour. No typing, no tapping.
- Talk and listen in real time, like a phone call
- Interrupt just by speaking — the coach stops and listens
- A live transcript shows both sides of the conversation

> **Note:** Requires microphone access. Wear headphones so the coach doesn't hear itself talking.

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

- **Demos #2 and #16 (image creation and editing)** need a **paid API key** — image generation isn't part of the free tier
- **Demo #19 (voice conversation)** will ask permission to use your microphone
- All other demos work with a free API key
- Your API key is saved in your own browser only
- Nothing to install — each file works on its own

## 🛠️ Technical Details

*For the curious — you don't need to understand any of this to use the demos.*

- Pure HTML/CSS/JavaScript - no frameworks required
- Uses the `@google/genai` SDK via CDN (esm.sh)
- Responsive design works on desktop and mobile
- All demos include error handling and loading states

### Models Used

| Demo | Model |
|------|-------|
| Text, documents, images, video, audio, tools (1, 5, 7–15, 18) | `gemini-3.5-flash` |
| Image generation & editing (2, 16) | `gemini-3.1-flash-image` (Nano Banana 2) |
| Speech generation (3) | `gemini-3.1-flash-tts-preview` |
| Long context & thinking (4, 6) | `gemini-3.1-pro-preview`, `gemini-3.5-flash`, or `gemini-3.1-flash-lite` (selectable) |
| Embeddings (17) | `gemini-embedding-2` |
| Real-time voice (19) | `gemini-3.1-flash-live-preview` |

### Agent Skills

The repo includes a copy of the official [Gemini API skills](https://github.com/google-gemini/gemini-skills)
in [`.cursor/skills/`](.cursor/skills/). These are reference guides that AI coding
assistants (like Cursor) read automatically, so if you ask an AI to modify or extend
these demos, it will use current model names and best practices instead of outdated
ones. See [`.cursor/skills/README.md`](.cursor/skills/README.md).

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

