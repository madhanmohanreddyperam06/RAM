<div align="left">

# RAM — Virtual Assistant

![HTML5](https://img.shields.io/badge/HTML-5-E34F26?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/CSS-3-1572B6?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzE1NzJCNiIgZD0iTTEuNSAwaDIxbC0xLjkxIDIxLjU2M0wxMS45NzcgMjRsLTguNTY1LTIuNDM4TDEuNSAwbTcuMDkgNC40MTNMNS40MSA0LjQxbC4yMTMgMi42MjIgMTAuMTI1LjAwMi0uMjU1IDIuNzE2aC02LjY0bC4yNCAyLjU3M2g2LjE4MmwtLjM2NiAzLjUyMy0yLjkxLjgwNC0yLjk1Ni0uODEtLjE4OC0yLjExaC0yLjYxbC4yOSAzLjg1NUwxMiAxOS4yODhsNS4zNzMtMS41M0wxOC41OSA0LjQxNHoiLz48L3N2Zz4=)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript)
![PyTorch](https://img.shields.io/badge/PyTorch-%3E%3D1.7.0-EE4C2C?style=flat-square&logo=pytorch)
![Web Speech API](https://img.shields.io/badge/Web_Speech-API-00BCD4?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzAwQkNENCIgZD0iTTEyIDE0YzEuNjYgMCAzLTEuMzQgMy0zVjVjMC0xLjY2LTEuMzQtMy0zLTNTOSAzLjM0IDkgNXY2YzAgMS42NiAxLjM0IDMgMyAzem01LjkxLTNjLS40OSAwLS45LjM2LS45OC44NUMxNi41MiAxNC4yIDE0LjQ3IDE2IDEyIDE2cy00LjUyLTEuOC00LjkzLTQuMTVjLS4wOC0uNDktLjQ5LS44NS0uOTgtLjg1LS42MSAwLTEuMDkuNTQtMSAxLjE0LjQ5IDMgMi44OSA1LjM1IDUuOTEgNS43OFYyMGMwIC41NS40NSAxIDEgMXMxLS40NSAxLTF2LTIuMDhjMy4wMi0uNDMgNS40Mi0yLjc4IDUuOTEtNS43OC4xLS42LS4zOS0xLjE0LTEtMS4xNHoiLz48L3N2Zz4=)
![SoundFile](https://img.shields.io/badge/SoundFile-Audio_I%2FO-4CAF50?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzRDQUY1MCIgZD0iTTE0IDJINmMtMS4xIDAtMiAuOS0yIDJ2MTZjMCAxLjEuOSAyIDIgMmgxMmMxLjEgMCAyLS45IDItMlY4bC02LTZ6bTIgMTRoLTJ2MmgtMnYtMmgtMnYtMmgydi0yaDJ2MmgydjJ6bS0zLTdWMy41TDE4LjUgOUgxM3oiLz48L3N2Zz4=)
![PyDub](https://img.shields.io/badge/PyDub-Audio_Processing-AB47BC?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0FCNDdCQyIgZD0iTTEyIDN2MTAuNTVjLS41OS0uMzQtMS4yNy0uNTUtMi0uNTUtMi4yMSAwLTQgMS43OS00IDRzMS43OSA0IDQgNCA0LTEuNzkgNC00VjdoNFYzaC02eiIvPjwvc3ZnPg==)
![tqdm](https://img.shields.io/badge/tqdm-Progress_Bar-FFC107?style=flat-square&logo=tqdm)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-5.15.3-538DD7?style=flat-square&logo=fontawesome)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-Roboto_Mono-4285F4?style=flat-square&logo=googlefonts)
</div>

---

## Overview

**RAM** is a browser-based virtual assistant that listens to spoken commands via the Web Speech API (`SpeechRecognition`) and responds audibly using `SpeechSynthesis`. It handles time-aware greetings, quick website launches, Google and Wikipedia queries, date/time announcements, and system calculator access through a dark-themed interface.

---

## Features

| Capability | Description |
| :--- | :--- |
| **Voice Recognition** | Captures spoken input on microphone click via `SpeechRecognition` / `webkitSpeechRecognition` |
| **Speech Synthesis** | Speaks confirmations, answers, time, and date back using `SpeechSynthesisUtterance` |
| **Time-Aware Greetings** | Automatically greets the user on page load based on the current hour |
| **Quick Site Navigation** | Opens Google, YouTube, and Facebook directly in new browser tabs |
| **Web & Wiki Search** | Queries Google (`what is`, `who is`, `what are`, or fallback) and Wikipedia (`wikipedia`) |
| **Built-in Utilities** | Announces local time and date, and launches the OS calculator (`Calculator:///`) |
| **Responsive Dark UI** | Minimalist `#000` canvas with `#00BCD4` accent, animated centerpiece, and `Roboto Mono` typography |

---

## Architecture & Workflow

### Voice Command Routing

```mermaid
flowchart TD
    A["Page Load"] --> B["Initialize SpeechSynthesis"]
    B --> C{"Current Hour (0-23)"}
    C -->|"00:00 - 11:59"| D["Speak: Good Morning Boss"]
    C -->|"12:00 - 16:59"| E["Speak: Good Afternoon Master"]
    C -->|"17:00 - 23:59"| F["Speak: Good Evening Sir"]

    G["Click Mic Button"] --> H["UI Shows Listening..."]
    H --> I["Start SpeechRecognition"]
    I --> J["Capture Transcript & Lowercase"]
    J --> K{"takeCommand(message)"}

    K -->|"hey / hello"| L["Speak Greeting Response"]
    K -->|"open google / youtube / facebook"| M["Open Website in New Tab"]
    K -->|"what is / who is / what are / wikipedia"| N["Open Google or Wikipedia Search"]
    K -->|"time / date / calculator"| O["Announce Time/Date or Open Calculator"]
    K -->|"No Match (Fallback)"| P["Search Query on Google"]
```

### Runtime Interaction Sequence

```mermaid
sequenceDiagram
    actor User
    participant UI as Web UI (index.html / style.css)
    participant JS as App Logic (app.js)
    participant API as Web Speech API
    participant Ext as Browser / OS Target

    User->>UI: Click microphone button
    UI->>JS: Trigger click listener
    JS->>UI: Update label to "Listening..."
    JS->>API: recognition.start()
    User-->>API: Speak voice command
    API-->>JS: Fire onresult(transcript)
    JS->>UI: Display recognized transcript
    JS->>JS: Execute takeCommand(transcript.toLowerCase())
    opt External URL or App Launch
        JS->>Ext: window.open(target)
    end
    JS->>API: speechSynthesis.speak(utterance)
    API-->>User: Play spoken response
```

<details>
<summary><strong>Startup &amp; Time-Based Greeting Rules (<code>wishMe()</code>)</strong></summary>

On page `load`, [`app.js`](app.js) speaks `"Initializing JARVIS..."` and runs `wishMe()` using the local system hour:

| Time Window (24-Hour) | Condition | Period | Spoken Greeting |
| :--- | :--- | :--- | :--- |
| `00:00` – `11:59` | `hour >= 0 && hour < 12` | Morning | `"Good Morning Boss..."` |
| `12:00` – `16:59` | `hour >= 12 && hour < 17` | Afternoon | `"Good Afternoon Master..."` |
| `17:00` – `23:59` | `else` (`hour >= 17`) | Evening | `"Good Evening Sir..."` |

</details>

---

## Supported Commands

| Category | Voice Trigger | Action Performed | Spoken Feedback |
| :--- | :--- | :--- | :--- |
| **Greeting** | `"Hey"` or `"Hello"` | Acknowledges greeting | `"Hello Sir, How May I Help You?"` |
| **Quick Launch** | `"Open Google"` | Opens `https://google.com` in a new tab | `"Opening Google..."` |
| **Quick Launch** | `"Open YouTube"` | Opens `https://youtube.com` in a new tab | `"Opening Youtube..."` |
| **Quick Launch** | `"Open Facebook"` | Opens `https://facebook.com` in a new tab | `"Opening Facebook..."` |
| **Web Search** | `"What is [query]"` / `"Who is [query]"` / `"What are [query]"` | Opens Google Search for the spoken query | `"This is what I found on the internet regarding [message]"` |
| **Knowledge Base** | `"Wikipedia [topic]"` | Opens `https://en.wikipedia.org/wiki/[topic]` | `"This is what I found on Wikipedia regarding [message]"` |
| **Date & Time** | `"Time"` | Reads local time (`hour`, `minute`) | `"The current time is [time]"` |
| **Date & Time** | `"Date"` | Reads current date (`month: short`, `day: numeric`) | `"Today's date is [date]"` |
| **System Utility** | `"Calculator"` | Opens `Calculator:///` URI scheme | `"Opening Calculator"` |
| **Fallback** | Any unrecognized phrase | Searches the phrase on Google in a new tab | `"I found some information for [message] on Google"` |

---

## Tech Stack

### Core Web Stack

| Layer | Technology | Version / Spec | Purpose | Source |
| :--- | :--- | :--- | :--- | :--- |
| **Markup** | HTML5 | HTML5 | Page structure, favicon, and microphone input UI | [`index.html`](index.html) |
| **Styling** | CSS3 | CSS3 | Dark `#000` background, `#00BCD4` theme, Flexbox layout | [`style.css`](style.css) |
| **Logic** | JavaScript | ES6+ | Event handling, date/time formatting, command routing | [`app.js`](app.js) |
| **Voice API** | Web Speech API | `SpeechRecognition` & `SpeechSynthesis` | Speech-to-text capture and text-to-speech playback (`rate: 1`, `volume: 1`, `pitch: 1`) | [`app.js`](app.js) |
| **Icons** | Font Awesome | `5.15.3` | Microphone button icon (`fas fa-microphone-alt`) via CDN | [`index.html`](index.html) |
| **Typography** | Google Fonts | `Roboto Mono` (`100`–`700`) | Monospace font family loaded via `@import` | [`style.css`](style.css) |

### Legacy Audio & ML Dependencies (`requirements.txt`)

> [!NOTE]
> [`requirements.txt`](requirements.txt) lists Python audio and deep-learning packages from an earlier/legacy setup; they are **not** required to run the browser-based assistant in [`index.html`](index.html).

<details>
<summary><strong>View <code>requirements.txt</code> Package Classification</strong></summary>

| Package | Version Constraint | Category | Typical Role |
| :--- | :--- | :--- | :--- |
| `torch` | `>=1.7.0` | Deep Learning | Tensor computation & neural network models |
| `numpy` | Unpinned | Numerical Computing | Array operations & math |
| `scipy` | Unpinned | Scientific Computing | Signal processing & scientific routines |
| `librosa` | Unpinned | Audio Analysis | Feature extraction & spectrogram analysis |
| `soundfile` | Unpinned | Audio I/O | Reading and writing audio files |
| `pydub` | Unpinned | Audio Manipulation | Audio slicing, conversion, and playback helpers |
| `tqdm` | Unpinned | CLI Utility | Progress bars for batch/training loops |

</details>

---

## Requirements & Compatibility

| Requirement | Specification | Notes |
| :--- | :--- | :--- |
| **Web Browser** | Chrome, Edge, or Safari | Requires `SpeechRecognition` / `webkitSpeechRecognition` and `speechSynthesis` support |
| **Microphone** | Active audio input device | Browser microphone permission must be allowed when prompted |
| **Internet Access** | Required | Loads Font Awesome & Google Fonts CDNs and opens external search tabs |

> [!TIP]
> For best speech recognition accuracy, use a quiet environment and speak clearly after the prompt displays `Listening...`.

---

## Installation & Usage

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/madhanmohanreddyperam06/RAM.git
   cd RAM
   ```
2. **Launch the assistant:**
   Open [`index.html`](index.html) directly in a supported browser (or serve the folder with a local static server).
3. **Interact via voice:**
   - Click the microphone button (`Click here to speak`).
   - Grant microphone access if prompted.
   - Speak any command from the [Supported Commands](#supported-commands) table.

<details>
<summary><strong>Troubleshooting &amp; Browser Notes</strong></summary>

- **No voice recognition response:** Check that your browser supports `window.SpeechRecognition` or `window.webkitSpeechRecognition` (Chromium-based browsers like Chrome and Edge provide the most consistent support).
- **No spoken audio on page load:** Some browsers block `speechSynthesis` audio until a user gesture occurs; click the microphone button to trigger active voice interaction.
- **`Calculator` command does nothing:** `Calculator:///` relies on OS URI scheme support (available by default on Windows).

</details>

---

## Project Structure

| File | Type | Description |
| :--- | :--- | :--- |
| [`index.html`](index.html) | HTML5 | Entry page structure, Font Awesome CDN, visual container, and mic button |
| [`style.css`](style.css) | CSS3 | Dark-mode layout (`#000`), `#00bcd4` title styling, and pill input container |
| [`app.js`](app.js) | JavaScript | Startup greetings, speech recognition/synthesis hooks, and `takeCommand()` router |
| [`75lD.gif`](75lD.gif) | GIF Asset | Animated visual displayed in the main interface |
| [`ai-logo-design-vector.jpg`](ai-logo-design-vector.jpg) | Image Asset | Application favicon |
| [`requirements.txt`](requirements.txt) | Pip Spec | Legacy Python audio/ML dependencies (unused by the web runtime) |
| [`LICENSE`](LICENSE) | Legal | MIT License |
| [`README.md`](README.md) | Documentation | Project documentation |

<details>
<summary><strong>Preview Visual Assets</strong></summary>

| Asset | Preview | Usage |
| :--- | :---: | :--- |
| `ai-logo-design-vector.jpg` | <img src="ai-logo-design-vector.jpg" alt="RAM Logo" width="80" /> | Favicon (`index.html`) |
| `75lD.gif` | <img src="75lD.gif" alt="RAM Animation" width="160" /> | Main interface visual (`index.html`) |

</details>

---

## License

This project is licensed under the **MIT License** — see the [`LICENSE`](LICENSE) file for details.

---

## Contact Information

### Madhan Mohan Reddy

- **Email**: <madhanmohanreddyperam06@gmail.com>
- **Mobile**: +91 9110395993

---
<div align="center">
© 2026 RAM. All rights reserved.
</div>
