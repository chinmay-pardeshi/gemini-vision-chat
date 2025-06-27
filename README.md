# 🖼️ Gemini Vision Chat

A powerful Streamlit web application that combines Google's Gemini AI with computer vision capabilities, allowing users to upload images and have interactive conversations about visual content.

## ✨ Features

- **Image Upload & Analysis**: Upload JPG, JPEG, or PNG images for AI analysis
- **Interactive Chat**: Ask questions about uploaded images using natural language
- **Conversation History**: Track your entire chat session with images and responses
- **Real-time Processing**: Get instant AI-powered responses about visual content
- **Clean UI**: Modern, user-friendly interface built with Streamlit
- **Responsive Design**: Works seamlessly across different screen sizes

## 🚀 Live Demo

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](your-app-url-here)

## 🛠️ Technologies Used

- **Frontend**: Streamlit
- **AI Model**: Google Gemini Vision (LearnLM 2.0 Flash Experimental)
- **Image Processing**: PIL (Python Imaging Library)
- **Environment Management**: python-dotenv
- **Language**: Python 3.8+

## 📋 Prerequisites

Before running this application, make sure you have:

- Python 3.8 or higher installed
- A Google AI Studio API key (free at [ai.google.dev](https://ai.google.dev))

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gemini-vision-chat.git
   cd gemini-vision-chat
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   GOOGLE_API_KEY=your_google_api_key_here
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

## 📁 Project Structure

```
gemini-vision-chat/
│
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── .env.example          # Environment variables template
├── .gitignore           # Git ignore file
└── README.md            # Project documentation
```

## 🔑 Getting Your Google API Key

1. Visit [Google AI Studio](https://ai.google.dev)
2. Sign in with your Google account
3. Click "Get API Key" and create a new project
4. Copy your API key and add it to your `.env` file

## 🌐 Deployment on Streamlit Cloud

1. **Fork/Clone this repository** to your GitHub account

2. **Set up Streamlit Cloud**:
   - Go to [share.streamlit.io](https://share.streamlit.io)
   - Connect your GitHub account
   - Select this repository
   - Set the main file path to `app.py`

3. **Add your API key**:
   - In Streamlit Cloud settings, go to "Secrets"
   - Add your Google API key:
     ```toml
     GOOGLE_API_KEY = "your_api_key_here"
     ```

4. **Deploy**: Your app will be live at `https://yourappname.streamlit.app`

## 💡 Usage

1. **Upload an Image**: Click "Browse files" and select an image (JPG, JPEG, or PNG)
2. **Ask Questions**: Type your question about the image in the text input
3. **Get Responses**: Click "Submit" to get AI-powered insights about your image
4. **View History**: Scroll up to see your conversation history
5. **Clear History**: Use the sidebar button to start fresh

## 🎯 Example Use Cases

- **Education**: Analyze diagrams, charts, or educational materials
- **Medical**: Describe symptoms or analyze medical images (not for diagnosis)
- **Art & Design**: Get detailed descriptions of artwork or design elements
- **OCR Tasks**: Extract and explain text from images
- **General Analysis**: Understand any visual content through AI

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Important Notes

- **API Costs**: This app uses Google's Gemini API, which may have usage costs
- **Rate Limits**: Be mindful of API rate limits for heavy usage
- **Privacy**: Images are processed by Google's AI - avoid uploading sensitive content
- **Accuracy**: AI responses are generated and may not always be 100% accurate

## 🙏 Acknowledgments

- Google AI for providing the Gemini Vision API
- Streamlit team for the amazing web framework
- The open-source community for continuous inspiration

## 📧 Contact

If you have any questions or suggestions, feel free to reach out!

---

**Made with ❤️ using Streamlit and Google Gemini AI**
