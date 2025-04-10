# Beluga Focus Timer Chat Bot

A modern, interactive focus timer application that combines the power of focused work sessions with an intelligent chat bot assistant. This project implements the innovative Beluga Technique for time management, offering a more flexible and engaging alternative to traditional Pomodoro timers.

## Features

### Focus Sessions
- **Regular Focus**: 30-minute focused work sessions
- **Deep Focus**: 45-minute sessions (unlocked after consecutive completions)
- **Break Types**:
  - Short breaks: 7 minutes
  - Micro-breaks: 2 minutes (for quick refreshes)
  - Long breaks: 20 minutes (after 3 completed cycles)

### Interactive Interface
- Clean, modern UI with beautiful animations
- Real-time timer display
- Task input and tracking
- Session statistics and progress visualization
- Motivational quotes on demand

### Beluga Chat Bot
- Interactive AI assistant
- Command-based interaction
- Real-time responses
- Motivational support
- Session management help

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Focus-timer.Chat-Bot.git
cd Focus-timer.Chat-Bot
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
Create a `.env` file in the root directory with your configuration:
```env
SECRET_KEY=your_secret_key_here
```

## Usage

1. Start the application:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

### Available Commands
In the chat interface, type:
- `help` - View all available commands
- `start` - Start a focus session
- `pause` - Pause current session
- `resume` - Resume paused session
- `stop` - Stop current session
- `stats` - View your focus statistics

## Technical Stack

- **Backend**: Python with Flask
- **Frontend**: HTML5, CSS3 (Tailwind CSS), JavaScript
- **Real-time Communication**: Socket.IO
- **UI Components**: Custom components with Tailwind CSS
- **Animations**: Three.js for brain animation

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Developed by Team Members (Registration numbers: 12323420, 12310364, 12315099)
- Inspired by modern focus techniques and productivity research
- Built with love for the developer community#
