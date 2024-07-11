# GenAI-Hackathon-
The YouTube Title Generator Using Real-Time Trend Data API and gpt-3.5-turbo for GenAI Hackathon 

# YouTube Trend Title Generator

## Description
YouTube Trend Title Generator is an AI-powered web application designed to help content creators and businesses in Taiwan generate trending, SEO-optimized video titles. By leveraging real-time trend analysis and localized data, this tool addresses the challenges of content creation in the competitive digital landscape.

## Features
- Real-time trend analysis using Google Trends API and YouTube API
- AI-driven title generation with OpenAI's GPT model
- Localized content focusing on the Taiwanese market
- Comprehensive analysis of trending YouTube titles
- User-friendly interface built with Streamlit
- Multi-title generation with user selection option

## Installation

### Prerequisites
- Python 3.7+
- pip

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/your-username/youtube-trend-title-generator.git
   cd youtube-trend-title-generator
   ```

2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   Create a `.env` file in the project root and add your API keys:
   ```
   YOUTUBE_API_KEY=your_youtube_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Usage
1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open the provided URL in your web browser.

3. Enter your industry and preferred title style.

4. Select a trending topic from the Google Trends list.

5. The app will generate multiple title options. Choose your favorite.

6. Copy the selected title to use for your YouTube video.

## Contributing
Contributions to improve YouTube Trend Title Generator are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
5. Push to the branch (`git push origin feature/AmazingFeature`).
6. Open a Pull Request.

## Acknowledgements
- [OpenAI](https://openai.com)
- [Google Trends API](https://trends.google.com/trends/)
- [YouTube Data API](https://developers.google.com/youtube/v3)
- [Streamlit](https://streamlit.io)
- [NLTK](https://www.nltk.org)
- [jieba](https://github.com/fxsjy/jieba)
