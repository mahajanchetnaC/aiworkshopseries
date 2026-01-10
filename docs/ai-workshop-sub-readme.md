# AI Workshop: Aspirational Path Generator Prompts

### Version 1: Demo Mode (NO API Key Required) ⭐ RECOMMENDED FOR WORKSHOP

```
Create a single-page web application called "career-path-finder-demo.html" that helps users discover their aspirational career path.

IMPORTANT: This is a DEMO version that works WITHOUT an API key. Instead of calling OpenAI:
- Generate realistic example responses based on the user's input
- Use template-based responses that feel personalized
- Include 5 different career path templates (tech, creative, business, academic, entrepreneurial)
- Match the user's input to the most relevant template
- Still make it feel dynamic and personalized

FUNCTIONALITY:
- Input fields for:
  * Current Role / Activity
  * Skills / Strengths
  * Years of Experience / Training
  * Interests / Focus Areas

- A "Generate My Aspirational Path (Demo)" button

- When clicked, generate a response that includes:
  1. 3-5 aspirational career goals (numbered list) relevant to their field
  2. A detailed 10-15 year path to the first goal with:
     📍 Milestones & Skills
     🎯 Opportunities & Achievements
     ⚠️ Risks & Setbacks
     💡 Recommended Actions

- Add a note at the top: "🎨 Demo Mode: This version uses pre-built templates. For AI-powered personalization, add an OpenAI API key."

DESIGN REQUIREMENTS:
- Modern gradient background (purple to blue theme)
- Glassmorphism card effect
- Responsive layout
- Smooth animations and hover effects
- Loading spinner (simulate 2-3 second delay)
- Use emojis throughout
- Professional yet fun aesthetic

TECHNICAL REQUIREMENTS:
- Single HTML file with embedded CSS and JavaScript
- Create 5 detailed career path templates in JavaScript
- Use string interpolation to personalize responses with user's input
- Add realistic delay to simulate API call
- Include helpful code comments
- Form validation

AFTER CREATING THE FILE:
- Automatically open the HTML file in the default browser so the user can test it immediately

Make it feel like a real AI app, even though it's using templates!
```


### Version 2: Local AI with Ollama (For Advanced Users)

```
Create a single-page web application called "career-path-finder-local.html" that uses Ollama (local AI) instead of OpenAI.

CONFIGURATION:
- Use Ollama's local API endpoint: http://localhost:11434/api/generate
- Use the "llama2" model (or "mistral" if available)
- Include instructions for users to install Ollama first

[Rest of functionality same as Version 1, but adapted for Ollama's API format]

Add a setup section at the top explaining:
1. Install Ollama from https://ollama.ai
2. Run: ollama pull llama2
3. Start Ollama service
4. Open this HTML file

Make sure to handle CORS properly for localhost requests.
```

### Version 3: With OpenAI API (Requires API Key)

```
Create a single-page web application called "career-path-finder.html" that helps users discover their aspirational career path.

FUNCTIONALITY:
- Input fields for:
  * Current Role / Activity
  * Skills / Strengths
  * Years of Experience / Training
  * Interests / Focus Areas

- A "Generate My Aspirational Path" button

- When clicked, call OpenAI GPT-4o-mini API to generate:
  1. 3-5 aspirational career goals (numbered list) including:
     - Ambitious "stretch" goals
     - Influential figures in their field
     - Fun and creative possibilities
  
  2. A detailed 10-15 year hypothetical path to the FIRST goal including:
     📍 MILESTONES & SKILLS:
     - Key milestones they'll reach
     - Skills they'll gain along the way
     
     🎯 OPPORTUNITIES & ACHIEVEMENTS:
     - Career opportunities
     - Notable achievements
     - Competitions or recognitions
     
     ⚠️ RISKS & SETBACKS:
     - Potential challenges
     - Possible setbacks or plot twists
     - How to overcome them
     
     💡 RECOMMENDED ACTIONS:
     - Concrete steps to reach the next stage
     - Resources to leverage
     - Networks to build

- Display results in a clean, formatted output area with proper spacing

DESIGN REQUIREMENTS:
- Modern gradient background (purple to blue theme)
- Glassmorphism card effect for the main container
- Responsive layout that works on mobile and desktop
- Smooth animations and hover effects on buttons
- Loading spinner while AI generates response
- Use emojis throughout to make it engaging
- Professional yet fun aesthetic
- Clean typography with good spacing

TECHNICAL REQUIREMENTS:
- Single HTML file with embedded CSS and JavaScript
- Use fetch API to call OpenAI's chat completions endpoint
- Include a clearly marked constant for API key: const OPENAI_API_KEY = 'YOUR_API_KEY_HERE';
- Add loading states and error handling
- Include helpful code comments explaining each section
- Form validation before submission
- Smooth scroll to results

STYLE:
- Make the AI response aspirational, imaginative, fun, realistic, and brutally honest
- Include optional plot twists to make it engaging
- Use emojis to highlight different sections

AFTER CREATING THE FILE:
- Automatically open the HTML file in the default browser so the user can test it immediately

Make it beautiful, functional, and ready to use immediately when opened in a browser!
```

