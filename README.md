# smArt :eye:

Ever come home from school ready to relax… and then remember you’ve got **five Achieve3000 assignments due tomorrow**?

### Well, this fixes that.

**smArt** is a lightweight browser bookmarklet that injects a small floating assistant onto the assignment page and helps you get through questions with the support of artificial intelligence by:
- Reading the passage + question from the page
- Sending it to the artificial intelligence
- Automatically selecting answers for multiple-choice questions
- Generating and inserting responses for writing prompts

## How it works 🧠
1. Add the bookmarklet to your browser
2. Open an **Achieve3000** activity
3. Click the bookmark **→** a draggable launcher appears
4. Hit **work smArt-er** to start *(and **stop.** to stop)*
5. Modify the settings with **the gear cog** on the bottom left of the launcher

## Settings :gear:
- Multiple-choice timing *(delay between questions to mimic real solving times)*
- Optional random-answer percentage *(to mimic real users)*
- Groq URL + model *(with reset to defaults)*
- Single **GroqCloud** API key *(you can get a free key from https://console.groq.com/keys )*

## How to Add the Bookmarklet 🤔
1. Copy everything in `bookmarklet.js`
2. In your browser, add new page to your bookmarklets. 
> for Google Chrome, right click on the bookmarklet bar and press on "add new page"
3. Add any name to your page
4. For the URL, paste everything you copied from `bookmarklet.js` **as is**

> **Note:** This tool depends on Achieve3000’s page structure. If they change the markup, selectors/XPaths may need updates.

---
*"Because automation is Art."*
