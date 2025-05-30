# ⚔️ Syntax Sentry

**Track. Detect. Analyze.**  
Syntax Sentry is a powerful Chromium-based extension designed to **monitor coding activity** on competitive programming platforms like LeetCode, HackerRank, and Codeforces. It is built to support academic integrity, performance analysis, and behavioral insights during coding sessions.

---

## 📦 Installation (Manually from `.crx`)

To use this extension outside the Chrome Web Store, you can manually install it in your Chromium-based browser (Chrome, Brave, Edge, etc.):

### Step-by-Step:

1. **Download the `.crx` file** from the [Releases](https://github.com/officialSyntaxSentry/packed-extension-chrome/blob/main/final-core.crx) section.
2. Go to `chrome://extensions/` in your browser.
3. **Enable Developer Mode** (toggle in the top-right corner).
4. Drag and drop the `.crx` file onto the extensions page.
5. Confirm installation when prompted.

> ✅ That’s it! You’ll now see the Syntax Sentry icon in your browser’s toolbar.

---

## 🔍 What It Does

Once installed, Syntax Sentry runs silently in the background and:

- ⌨️ Logs keystrokes while solving coding problems.
- 🖱 Tracks mouse movements and interactions.
- 📋 Monitors copy-paste behavior.
- 🚀 Detects and logs code submissions.
- 📊 Sends data securely to a backend (if configured) for dashboard analysis.

---

## 🧠 Supported Websites

Syntax Sentry is tailored to work with the following platforms:

- [LeetCode](https://leetcode.com/)
- [HackerRank](https://hackerrank.com/)
- [Codeforces](https://codeforces.com/)

> You can easily extend support for additional platforms in the source.

---

## 🔧 Developer Setup (Unpacked Mode)

If you're a developer or want to inspect or modify the extension:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/syntax-sentry.git
   ```
2. Open `chrome://extensions/`
3. Enable **Developer Mode**
4. Click **"Load Unpacked"**
5. Select the project root folder (that contains `manifest.json`)

Now you're running Syntax Sentry in development mode.


## 🔐 Privacy & Data Usage

Syntax Sentry **does not store data locally** unless configured. All tracked data is sent to a secure backend endpoint (e.g., Vercel, MongoDB Atlas) defined in `config.js`.

- ✅ No third-party tracking
- ✅ Code only runs on supported domains
- ✅ Transparent open-source tracking logic

You’re in full control of what’s collected and where it goes.

---

## 🚀 Features Roadmap

- [x] Activity logging (keystrokes, mouse, clipboard, submissions)
- [x] Realtime database integration
- [x] Dashboard support
- [ ] AI-based cheating detection (in progress)
- [ ] Community tracking & leaderboard (premium feature)
- [ ] Integration with other platforms (e.g., GeeksforGeeks, CodeChef)

---

---

## ✉️ Contact

For questions, bug reports, or collaborations:  
📧 **syntaxsentry99@gmail.com**  
🌐 [syntax-sentry.prodijee.in](https://syntax-sentry.prodijee.in)

---

> Made with 🧠 and ☕ by passionate developers for a fairer coding world.
```
