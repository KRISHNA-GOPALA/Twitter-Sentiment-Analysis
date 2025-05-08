# Twitter-Sentiment-Analysis

A Python-based web application that performs sentiment analysis on Twitter data using keywords or hashtags. This project utilizes Flask for the web framework, Tweepy for accessing the Twitter API, and NLTK for natural language processing tasks.

## 🚀 Features

- Fetches real-time tweets based on user-defined keywords or hashtags.
- Analyzes the sentiment of each tweet (e.g., positive, negative, neutral).
- Visualizes sentiment distribution through graphical representations.
- Simple and intuitive web interface for user interaction.

## 🛠️ Technologies Used

- **Python 3.7+**
- **Flask**: Web framework
- **Tweepy**: Accessing Twitter API
- **NLTK**: Natural Language Processing
- **Matplotlib**: Data visualization
- **Pickle**: Model serialization

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KRISHNA-GOPALA/Twitter-Sentiment-Analysis.git
   cd Twitter-Sentiment-Analysis
   ```
2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```
  
4. **Set up Twitter API credentials:**
   - Create a config.py file in the project root directory.
   - Add your Twitter API credentials:
       ```bash
       consumer_key = 'YOUR_CONSUMER_KEY'
       consumer_secret = 'YOUR_CONSUMER_SECRET'
       access_token = 'YOUR_ACCESS_TOKEN'
       access_token_secret = 'YOUR_ACCESS_TOKEN_SECRET'
       ```

## 🧪 Usage
1. **Run the application:**
```bash
python app.py
```

2. **Access the web interface:**
   - Open your web browser and navigate to http://localhost:5000.

3. **Perform sentiment analysis:**
   - Enter a keyword or hashtag in the search bar.
   - View the analyzed sentiments and visualizations.


## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
