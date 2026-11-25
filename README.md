# RAM - Virtual Assistant

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

This project is a web-based virtual assistant named RAM that uses speech recognition and synthesis to interact with users. It allows voice commands to perform various tasks like opening websites, searching the internet, and providing information.

## Features

- Voice-activated interaction using Web Speech API
- Personalized greetings based on time of day
- Open popular websites (Google, YouTube, Facebook)
- Search Google or Wikipedia for queries
- Tell current time and date
- Open system calculator
- Responsive web interface with modern design

## Requirements

- Modern web browser with Web Speech API support (Chrome, Edge, Safari recommended)
- Microphone access for voice input
- Internet connection for web searches

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/madhanmohanreddyperam06/RAM.git
   cd ram-virtual-assistant
   ```

2. Open `index.html` in your web browser.

## Usage

1. Click the microphone button to start voice recognition.
2. Speak your command clearly.
3. RAM will respond with voice synthesis and perform the requested action.

### Supported Commands

- "Hey" or "Hello" - Greeting response
- "Open Google" - Opens Google in new tab
- "Open YouTube" - Opens YouTube in new tab
- "Open Facebook" - Opens Facebook in new tab
- "What is [query]" or "Who is [query]" - Searches Google for the query
- "Wikipedia [topic]" - Opens Wikipedia page for the topic
- "Time" - Announces current time
- "Date" - Announces today's date
- "Calculator" - Opens system calculator

## File Structure

- `index.html` - Main HTML structure and layout
- `style.css` - CSS styles for the interface
- `app.js` - JavaScript logic for speech recognition and commands
- `75lD.gif` - Animated background image
- `ai-logo-design-vector.jpg` - Favicon/logo image
- `requirements.txt` - (Legacy file, not used in this project)

## Notes

- Ensure microphone permissions are granted in your browser.
- For best speech recognition, use a quiet environment and speak clearly.
- The assistant initializes with a greeting when the page loads.

## License

This project is licensed under the MIT License.
