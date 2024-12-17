# Siri Grok Integration

Connect Siri to **ChatGPT-like responses** using X.ai’s free Grok API! This shortcut lets you ask Siri custom questions and get dynamic responses, even on older iPhones. 🚀

## Features
- Ask Siri anything and get intelligent responses.
- Works on any iPhone running the Shortcuts app.
- Easy setup with X.ai’s Grok API.

---

## How It Works
This shortcut sends your question to the Grok API and fetches a ChatGPT-style response. You’ll need an API key from X.ai to make it work.

---

## Installation

### Step 1: Download the Shortcut
1. Download the `.shortcut` file from this repository.
2. Open the file to add it to your Shortcuts app.

### Step 2: Enable Untrusted Shortcuts
If this is your first time using external shortcuts:
1. Go to **Settings** > **Shortcuts**.
2. Turn on **Allow Untrusted Shortcuts**.

---

## Adding Your API Key

1. **Get an API Key**
   - Sign up for an account at [X.ai](https://x.ai/) and generate a free Grok API key.

2. **Update the Shortcut**
   - Open the Shortcut in the Shortcuts app.
   - Find the **Authorization** field in the JSON setup (or script action).
   - Replace ` ` with your personal API key.
  
   - <img width="587" alt="place your api key here" src="https://github.com/user-attachments/assets/a1d3b718-0f19-4aa2-8a4b-e83ba4303b6d" />


Example:
```json
-H "Authorization: Bearer YOUR_API_KEY_HERE"
```

---

## Usage
1. Activate Siri and say something like:
   - *“Ask Grok what’s trending on Twitter.”*
   - *“Ask Grok for a joke.”*
2. Siri will fetch the response from the Grok API and display it on the screen, along with voice playback.

---

## Notes
- Ensure you have an active internet connection.
- This shortcut is optimized for Grok's free tier—check their documentation for any limits.

---

## Demo

Check out the shortcut in action in the demo video [here](#).

<a href="https://www.instagram.com/reel/DDovUYfBv2z/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==">
  <img width="441" alt="Screenshot 2024-12-17 at 14 54 47" src="https://github.com/user-attachments/assets/2e7f5d11-6648-4724-b5a9-a5033a18a550" />

</a>


---

