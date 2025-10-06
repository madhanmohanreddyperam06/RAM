# RAM - Virtual Assistant

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
