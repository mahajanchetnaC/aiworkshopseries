# AI Workshop: Aspirational Path Generator (Audience Demo App)

Welcome to the AI Workshop demo! 🎉  
Share this page with your audience to instantly try out a self-contained, browser-based AI-powered web app.

## What is it?

This tool generates an **aspirational career path** based on your current skills, experience, and interests, leveraging OpenAI GPT-5-mini.  
It's a **single HTML file** — just save, open, and run it on your computer. No installation, no dependencies, no copying — everything is wired up.

## What does it do?

- You fill out four fields about your background and goals:
  - Current Role / Activity
  - Skills / Strengths
  - Years of Experience / Training
  - Interests / Focus Areas
- Enter your **OpenAI API key** once (secure and local!).
- Click **“Show My Aspirational Path”**.
- The app:
  1. Sends your info + a structured prompt to OpenAI GPT-5-mini.
  2. Receives:
     - **3–5 aspirational goals or iconic figures** (with ambitious, stretch, and fun possibilities)
     - A **10–15 year career path** from your current role/skills to the first goal, including milestones, competitions, risks/setbacks/plot twists, and actionable steps.
  3. Displays the result in a **styled preformatted area**, emoji milestones, and more!
- Everything is **fully self-contained** in one HTML file — **ready to share and run**.

---

## PROMPT FOR THE APP (used by the AI):

> You are an expert full-stack web developer. Your task is to **generate a complete, fully working single-page web application** that runs on localhost. The user should be able to **just open it in their browser and use it immediately**. No extra instructions, no manual copying. Everything must be self-contained in **one HTML file**.

**FUNCTIONALITY:**

1. Inputs for the user:
   - Current Role / Activity
   - Skills / Strengths
   - Years of Experience / Training
   - Interests / Focus Areas

2. When the user clicks **“Show My Aspirational Path”**:
   - The app sends a prompt to **OpenAI GPT-5-mini** using the user’s inputs.
   - The AI should:
     1. Suggest **3–5 aspirational goals or iconic figures** relevant to the user (numbered list)
        - Include ambitious / “stretch” goals, influential figures, and fun possibilities
     2. Assume the **first goal** is selected as `{selected_goal}`
     3. Generate a **10–15 year hypothetical path** from current role/skills to `{selected_goal}` including:
        - Milestones & skills gained
        - Opportunities, achievements, competitions
        - Risks, setbacks, or plot twists
        - Recommended actions to reach the next stage
     - Style: aspirational, imaginative, fun, realistic, brutally honest, with optional plot twists

3. Display the output clearly in a **preformatted text area**:
   - Numbered list of aspirational goals
   - Step-by-step path to the selected goal

**TECHNICAL REQUIREMENTS:**

- Single HTML file with embedded CSS and JavaScript
- Clean, responsive, mobile-friendly layout
- Users only need to **enter their OpenAI API key** in one clearly labeled place in the JS
- Include comments explaining each section of the code
- Include fun visual touches: colors, spacing, emoji milestones, etc.
- Fully self-contained — no external libraries required
- The AI prompt, API call, and output display must be fully wired

**OUTPUT:**

- Generate the **entire HTML file** with embedded CSS and JavaScript **ready to save and run on localhost**  
- Include the OpenAI API call in JS with a placeholder for the API key
- Make sure the app works when opened in a browser, with all functionality described above

**AFTER CREATING THE FILE:**
- Automatically open the HTML file in the default browser so the user can test it immediately.

---

## Usage Instructions

**1. Copy & save the HTML file below:**  
Paste the full code into a file named `aspirational-path-generator.html`.

**2. Double-click to open** — or open in your favorite browser.

**3. Enter your OpenAI API Key, fill your info, and try it out! 🚀**

---

> **Source repository:** [mahajanchetnaC/aiworkshopseries](https://github.com/mahajanchetnaC/aiworkshopseries)
