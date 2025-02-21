# SQLGenius - Advanced Database Query Assistant 🚀

SQLGenius is an elegant, AI-powered SQL query optimization assistant that helps developers generate, optimize, and understand complex SQL queries through an intuitive chat interface.

![SQLGenius Interface](https://raw.githubusercontent.com/your-username/sqlgenius/main/screenshots/demo.png)

## Features ✨

- **AI-Powered Query Optimization**: Leverages advanced AI to generate optimized SQL queries
- **Interactive Chat Interface**: User-friendly chat-based interface for query assistance
- **Syntax Highlighting**: Beautiful SQL syntax highlighting for better readability
- **Copy to Clipboard**: One-click code copying functionality
- **Dark/Light Theme**: Toggle between dark and light modes for comfortable viewing
- **Responsive Design**: Fully responsive layout that works on all devices
- **Markdown Support**: Rich text formatting with markdown for clear explanations

## Getting Started 🛠️

### Prerequisites

- Modern web browser
- Internet connection
- OpenRouter API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/sqlgenius.git
```

2. Navigate to the project directory:
```bash
cd sqlgenius
```

3. Open `app.js` and replace the API key with your OpenRouter API key:
```javascript
this.apiKey = 'your-openrouter-api-key';
```

4. Open `index.html` in your web browser or serve using a local server.

### Usage

1. Enter your SQL query requirements in natural language
2. SQLGenius will generate an optimized query with detailed explanations
3. Each response includes:
   - Query purpose explanation
   - Optimized SQL query
   - Detailed explanation of the approach
   - Performance optimization notes

## Technology Stack 💻

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript (ES6+)
- [OpenRouter AI API](https://openrouter.ai/)
- [Font Awesome](https://fontawesome.com/) for icons
- [highlight.js](https://highlightjs.org/) for syntax highlighting

## Project Structure 📁

```
sqlgenius/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── app.js             # Core application logic
└── README.md          # Documentation
```

## Features in Detail 🔍

### AI Query Generation
- Utilizes Qwen 2.5 VL 72B model for query optimization
- Provides structured responses with query purpose, SQL code, and explanations
- Includes performance optimization notes

### User Interface
- Clean, modern design with intuitive chat interface
- Smooth animations and transitions
- Neumorphic design elements
- Responsive layout for all screen sizes

### Theme Support
- Dark/light mode toggle
- Persistent theme preference storage
- System theme preference detection
- High contrast accessibility

### Code Handling
- Syntax highlighted SQL code blocks
- Copy-to-clipboard functionality
- Auto-expanding input field
- Support for multi-line queries
- Graceful error handling with user-friendly messages
- Automatic retry mechanisms for API failures

### SEO Optimization
- Semantic HTML5 structure for better indexing
- Meta tags for improved search engine visibility
- Descriptive titles and headings
- Mobile-friendly and responsive design (SEO ranking factor)
- Fast loading performance with optimized assets

### Error Handling 🛡️
- User-friendly error messages: "Sorry, I encountered an error. Please try again."
- Automatic retry for API connection failures
- Network connectivity monitoring
- Detailed error logging for debugging
- Graceful degradation during service disruptions

### Troubleshooting Common Errors 🔧
If you encounter the error message "Sorry, I encountered an error. Please try again", check the following:
1. **API Key Configuration**
   - Ensure your OpenRouter API key is correctly set in `app.js`
   - Verify the API key is valid and has sufficient credits
   - Check that the API key format matches: `sk-or-v1-...`

2. **Network Connectivity**
   - Check your internet connection
   - Ensure no firewall rules are blocking API requests
   - Verify you can access openrouter.ai in your browser

3. **API Rate Limits**
   - Check if you've exceeded API rate limits
   - Consider implementing request throttling
   - Monitor your API usage on OpenRouter dashboard

4. **Browser Console**
   - Open browser developer tools (F12)
   - Check console for detailed error messages
   - Look for specific HTTP error codes

5. **Server Response**
   - Verify the model name in the API request
   - Ensure request payload format is correct
   - Check if the API endpoint URL is correct

For persistent issues, try:
- Clearing browser cache and cookies
- Using a different browser
- Checking OpenRouter service status
- Implementing exponential backoff for retries

## Contributing 🤝

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- [OpenRouter](https://openrouter.ai/) for providing the AI API
- [highlight.js](https://highlightjs.org/) for code syntax highlighting
- [Font Awesome](https://fontawesome.com/) for the iconic icons

## Support 💬

If you encounter any issues or have questions, please [open an issue](https://github.com/your-username/sqlgenius/issues) on GitHub.
