# Cursor Mini - AI-Powered CLI Assistant

An intelligent Node.js command-line application powered by Google's Generative AI that assists users by executing terminal commands and automating project workflows through natural language conversation.

## 📋 Project Overview

Cursor Mini is an AI-powered CLI assistant that understands your requests and executes them automatically. Describe what you want to do in plain English, and the AI will handle the terminal commands, file operations, and project management tasks.

## ✨ Features

- 🤖 AI-powered command execution and project management
- 💬 Interactive CLI interface with conversation history
- 🛠️ Dynamic tool integration with Google GenAI
- 📝 Terminal command automation
- 🔧 File and folder management capabilities
- ⚡ Cross-platform support (Windows, macOS, Linux)

## 🛠️ Prerequisites

Before you begin, ensure you have installed:
- **Node.js** (v14 or higher) - [Download](https://nodejs.org/)
- **npm** (comes with Node.js)
- A text editor (VS Code, Sublime Text, etc.)
- A web browser (Chrome, Firefox, Safari, etc.)
- **Google GenAI API Key** - [Get your API key](https://ai.google.dev)

## 📦 Installation & Setup

### Step 1: Clone or Extract the Project
```bash
# Navigate to the project directory
cd /path/to/Cursor-Mini
```

### Step 2: Install Dependencies
```bash
# Install npm packages
npm install
```

### Step 3: Create Environment Variables

Create a `.env` file in the root directory:

```bash
# Create .env file
touch .env
```

Add your Google GenAI API key to the `.env` file:
```
apiKey=your_google_genai_api_key_here
```

**How to get your API key:**
1. Visit [Google AI Studio](https://ai.google.dev)
2. Click "Get API Key"
3. Create a new API key
4. Copy and paste it in your `.env` file

### Step 4: Project Structure
```
Cursor-Mini/
├── app.js                    # Main AI assistant application
├── package.json             # Node.js dependencies
├── .env                     # Environment variables (create this)
└── readme.md               # This file
```

## 🚀 Running the Project Locally

### Start the AI Assistant

```bash
# Start the AI-powered CLI application
node app.js
```

Once running, you can interact with the AI by typing your requests. The assistant will execute commands and manage your project based on your instructions.

**Example interactions:**
- "Create a new folder called projects"
- "Create a JavaScript file with a hello world function"
- "Generate a README for my project"
- "List all files in the current directory"

The AI will execute the commands and provide feedback on the results.

## 📝 Environment Configuration

The project requires the following environment variables in your `.env` file:

| Variable | Description | Required |
|----------|-------------|----------|
| `apiKey` | Your Google GenAI API Key | ✅ Yes |

### Example .env file:
```
apiKey=AIzaSyB5U9w7gKl_abcdefghijklmnopqrst1234
```

## 🎯 Usage Guide

### Using the AI Assistant
1. Run `node app.js`
2. The AI will prompt you for input
3. Describe tasks in natural language, such as:
   - "Create a new folder called projects"
   - "Create a JavaScript file with a hello world function"
   - "Generate a README for my project"
   - "Delete the temporary files"
4. The AI will execute the commands and provide feedback

## 🔧 Troubleshooting

### Issue: `apiKey is not defined`
**Solution:** Make sure your `.env` file exists in the root directory and contains `apiKey=your_key_here`

### Issue: `Module not found`
**Solution:** Run `npm install` to install all dependencies from `package.json`

### Issue: Port already in use
**Solution:** Change the port number when starting the server:
```bash
python3 -m http.server 9000
```

### Issue: GenAI API errors
**Solution:** 
- Verify your API key is valid and active
- Check your internet connection
- Ensure the API key has proper permissions

## 📦 Dependencies

### Node.js Backend
- **dotenv** - Environment variable management
- **@google/genai** - Google's Generative AI SDK
- **readline-sync** - Synchronous readline for CLI
- **Built-in modules**: child_process, util, os

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Improve documentation
- Submit pull requests

## 📄 License

This project is provided as-is for educational and development purposes.

## 🎓 Learning Resources

- [Google Generative AI Documentation](https://ai.google.dev/docs)
- [Node.js Documentation](https://nodejs.org/docs/)
- [HTML/CSS/JavaScript Basics](https://developer.mozilla.org/en-US/docs/Web/)
- [Web APIs Documentation](https://developer.mozilla.org/en-US/docs/Web/API)

## 📞 Support

For issues or questions:
1. Check the troubleshooting section
2. Review the code comments
3. Check the official documentation links above

---

**Status:** 🚀 Ready to use - v1.0
**Last Updated:** May 2026