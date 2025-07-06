

🤖 **Fast, light & open-source**—Glass lives on your desktop, sees what you see, listens in real time, understands your context, and turns every moment into structured knowledge.

💬 **Proactive in meetings**—it surfaces action items, summaries, and answers the instant you need them.

🫥️ **Truly invisible**—never shows up in screen recordings, screenshots, or your dock; no always-on capture or hidden sharing.


## Instant Launch

⚡️  Skip the setup—launch instantly with our ready-to-run macOS app.  [[Download Here]](https://www.dropbox.com/scl/fi/znid09apxiwtwvxer6oc9/Glass_latest.dmg?rlkey=gwvvyb3bizkl25frhs4k1zwds&st=37q31b4w&dl=1)

## Quick Start (Local Build)

### Prerequisites

First download & install [Python](https://www.python.org/downloads/) and [Node](https://nodejs.org/en/download).
If you are using Windows, you need to also install [Build Tools for Visual Studio](https://visualstudio.microsoft.com/downloads/)

Ensure you're using Node.js version 20.x.x to avoid build errors with native dependencies.

```bash
# Check your Node.js version
node --version

# If you need to install Node.js 20.x.x, we recommend using nvm:
# curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
# nvm install 20
# nvm use 20
```

### Installation

```bash
npm run setup
```

## Highlights


### Ask: get answers based on all your previous screen actions & audio

<img width="100%" alt="booking-screen" src="./public/assets/00.gif">

### Meetings: real-time meeting notes, live summaries, session records

<img width="100%" alt="booking-screen" src="./public/assets/01.gif">

### Use your own OpenAI API key, or sign up to use ours (free)

<img width="100%" alt="booking-screen" src="./public/assets/02.gif">

You can visit [here](https://platform.openai.com/api-keys) to get your OpenAI API Key.

### Liquid Glass Design (coming soon)

<img width="100%" alt="booking-screen" src="./public/assets/03.gif">

<p>
  for a more detailed guide, please refer to this <a href="https://www.youtube.com/watch?v=qHg3_4bU1Dw">video.</a>
  <i style="color:gray; font-weight:300;">
    we don't waste money on fancy vids; we just code.
  </i>
</p>


## Keyboard Shortcuts

`Ctrl/Cmd + \` : show and hide main window

`Ctrl/Cmd + Enter` : ask AI using all your previous screen and audio

`Ctrl/Cmd + Arrows` : move main window position

## Contributing

We love contributions! Feel free to open issues for bugs or feature requests.

## 🛠 Current Issues & Improvements

| Status | Issue                          | Description                                       |
|--------|--------------------------------|---------------------------------------------------|
| 🚧 WIP     | AEC Improvement                | Transcription is not working occasionally |
| 🚧 WIP     | Code Refactoring               | Refactoring the entire codebase for better maintainability. |
| 🚧 WIP      | Firebase Data Storage Issue    | Session & ask should be saved in firebase for signup users |
| 🚧 WIP      | Login Issue                    | Currently breaking when switching between local and sign-in mode |
| 🚧 WIP      | Liquid Glass                    | Liquid Glass UI for MacOS 26 |
| 🚧 WIP      | Permission Issue           | Mic & system audio & display capture permission sometimes not working|



## About Pickle

**Our mission is to build a living digital clone for everyone.** Glass is part of Step 1—a trusted pipeline that transforms your daily data into a scalable clone. Visit [pickle.com](https://pickle.com) to learn more.

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=pickle-com/glass&type=Date)](https://www.star-history.com/#pickle-com/glass&Date)
