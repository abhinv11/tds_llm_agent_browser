# AI Agent - Advanced AI Assistant

A sophisticated web-based AI assistant with multi-tool capabilities, voice interface, and real-time collaboration features.

![AI Agent](https://img.shields.io/badge/Version-2.8.0-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)

## 🚀 Features

### Core Capabilities
- **Multi-LLM Support**: Compatible with OpenAI GPT, Anthropic Claude, Google Gemini, and AI Pipe
- **Intelligent Conversations**: Context-aware chat with conversation management
- **Voice Interface**: Voice input and output with multiple language support
- **Real-time Processing**: Fast response times with performance monitoring
- **Progressive Web App**: Installable on any device with offline capabilities

### Advanced Features
- **Smart Search Integration**: Real-time web search capabilities
- **Code Execution**: Safe JavaScript execution with syntax highlighting
- **File Processing**: Drag & drop file analysis and processing
- **Export/Import**: Conversation and settings backup/restore
- **Theme Support**: Auto, light, and dark themes with system detection
- **Performance Analytics**: Built-in performance monitoring and metrics

### User Experience
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Accessibility**: Full keyboard navigation and screen reader support
- **Customizable Interface**: Adjustable font sizes, animations, and sound effects
- **Conversation History**: Persistent conversation storage with search
- **Quick Actions**: Pre-defined prompts for common tasks

## 🛠️ Installation

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-agent.git
   cd ai-agent
   ```

2. Start a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open your browser and navigate to `http://localhost:8000`

### Configuration
1. Click the settings icon (⚙️) in the top navigation
2. Configure your preferred LLM provider:
   - **AI Pipe**: Enter your AI Pipe token (recommended for easy setup)
   - **OpenAI**: Enter your OpenAI API key
   - **Anthropic**: Enter your Anthropic API key
   - **Google**: Enter your Google AI API key
3. Select your preferred model and adjust settings
4. Save your configuration

## 🔧 API Configuration

### AI Pipe (Recommended)
AI Pipe provides easy access to multiple LLM providers through a single API:
1. Visit [aipipe.org](https://aipipe.org) to get your token
2. Select "AI Pipe" as your provider in settings
3. Enter your token in the API Key field

### Direct Provider Setup
For direct API access, you'll need API keys from:
- **OpenAI**: [platform.openai.com](https://platform.openai.com)
- **Anthropic**: [console.anthropic.com](https://console.anthropic.com)
- **Google AI**: [ai.google.dev](https://ai.google.dev)

## 📱 Usage

### Basic Chat
1. Type your message in the input area
2. Press Enter or click the send button
3. The AI will respond with helpful information

### Voice Commands
1. Click the microphone button or press the voice toggle
2. Speak your question clearly
3. The AI will process your speech and respond

### File Analysis
1. Drag and drop files onto the chat area
2. Or click the paperclip icon to select files
3. The AI will analyze and provide insights about your files

### Advanced Features
- **Code Execution**: Ask the AI to write and run JavaScript code
- **Web Search**: Request real-time information from the web
- **Data Visualization**: Create charts and graphs from your data
- **Multi-step Workflows**: Complex tasks broken down into manageable steps

## 🎨 Customization

### Themes
- **Auto**: Follows your system theme preference
- **Light**: Clean, bright interface for daytime use
- **Dark**: Easy on the eyes for low-light environments

### Voice Settings
- Multiple language support (English, Spanish, French, German)
- Adjustable speech rate and voice selection
- Enable/disable voice input and output independently

### Interface Options
- Font size adjustment (Small, Medium, Large)
- Animation controls for performance optimization
- Sound effects toggle
- Conversation auto-save settings

## 🔧 Troubleshooting

### Common Issues

#### API Connection Problems
- Verify your API key is entered correctly
- Check your internet connection
- Ensure the selected provider is accessible in your region

#### Performance Issues
- Clear browser cache and reload
- Check the Performance Monitor for bottlenecks
- Reduce animation settings for older devices

#### Conversation Cleanup
If you experience corrupted conversation data:
1. Go to Settings → Advanced
2. Click "Clean Up Conversations" to remove error messages
3. Or use "Clear All Data" for a fresh start

### Browser Compatibility
- **Chrome**: Full support (recommended)
- **Firefox**: Full support
- **Safari**: Full support with minor limitations
- **Edge**: Full support

## 🏗️ Technical Architecture

### Core Technologies
- **Frontend**: Vanilla JavaScript (ES6+), HTML5, CSS3
- **Styling**: Bootstrap 5.3.2, Font Awesome 6.5.0
- **Markdown**: Marked.js for rich text rendering
- **Code Highlighting**: Highlight.js for syntax highlighting
- **PWA**: Service Worker for offline capabilities

### File Structure
```
ai-agent/
├── index.html          # Main application interface
├── agent.js           # Core application logic
├── styles.css         # Custom styling and themes
├── LICENSE           # MIT license
└── README.md         # This file
```

### Key Components
- **AIAgent Class**: Main application controller with Proxy-based state management
- **Conversation Manager**: Handles chat history and persistence
- **API Controller**: Manages multiple LLM provider integrations
- **Voice Interface**: Speech recognition and synthesis
- **Performance Monitor**: Real-time metrics and optimization

## 🤝 Contributing

We welcome contributions! Please feel free to submit pull requests or open issues for:
- Bug fixes and improvements
- New LLM provider integrations
- UI/UX enhancements
- Documentation updates
- Performance optimizations

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and test thoroughly
4. Commit with clear messages: `git commit -m "Add feature description"`
5. Push to your fork: `git push origin feature-name`
6. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Abhinav Jaswal**

## 🚀 Version History

### v2.8.0 (Current)
- Enhanced API error handling and recovery
- Improved conversation cleanup functionality
- Better message filtering and validation
- Performance optimizations
- Updated branding and documentation

### Previous Versions
- Multi-provider API support
- Voice interface implementation
- PWA capabilities
- Performance monitoring
- Theme system implementation

## 🆘 Support

If you encounter any issues or have questions:
1. Check the troubleshooting section above
2. Review existing GitHub issues
3. Create a new issue with detailed information about your problem
4. Include browser version, OS, and steps to reproduce

---

**Built with ❤️ for the AI community**