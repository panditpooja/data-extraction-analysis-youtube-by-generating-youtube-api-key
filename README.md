# Data extraction and analysis from YouTube
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Tool-Jupyter%20Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![CSV](https://img.shields.io/badge/Data-CSV-brightgreen?logo=read-the-docs)](https://datatracker.ietf.org/doc/html/rfc4180)
[![JSON](https://img.shields.io/badge/Data-JSON-lightgrey?logo=json)](https://www.json.org/json-en.html)

The data collection is performed by generating and using the YouTube API key.

## 🚀 Unlocking Insights: Harnessing the Power of YouTube's Data with API-driven Extraction and Analysis
The landscape of digital content creation has evolved rapidly, with videos emerging as a dynamic medium for communication, knowledge-sharing, and skill demonstration. Among the plethora of platforms, YouTube stands out as a global hub, hosting a diverse array of content spanning professions, arts, and cultures.

Within this vibrant ecosystem, user interaction plays a pivotal role.



---

## ✨ Features

- ✅ Programmatic data extraction from YouTube using the YouTube API key.
- 📊 In-depth analysis of video attributes such as likes, dislikes, and comments.
- 📈 Uncover trends, preferences, and audience engagement metrics.

---

## 📁 Repository Structure

```
📂 data-extraction-analysis-youtube
├── README.md                                # Project overview and documentation
├── YoutubeAPIGeneration_DataAnalysisExtraction.ipynb  # Main Jupyter Notebook
├── pooja_avatar_movie.csv                   # CSV file with cleaned YouTube video data after analysis
├── pooja_avatar_movie_comments.json         # JSON file with raw data extracted from YouTube API
├── requirements.txt                         # Project dependencies
```

---

## ⚙️ Setup and Installation

### Prerequisites
- Python 3.8+
- A YouTube API key (obtainable from [Google Developers Console](https://developers.google.com/youtube/v3/getting-started))
- Git

### Install dependencies

1. **Clone the repository**
```bash
git clone https://github.com/panditpooja/data-extraction-analysis-youtube-by-generating-youtube-api-key.git
cd data-extraction-analysis-youtube-by-generating-youtube-api-key
```

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required Python libraries**
```bash
pip install -r requirements.txt
```

4. **Add your YouTube API key**
   - Open the Jupyter notebook (`YoutubeAPIGeneration_DataAnalysisExtraction.ipynb`)
   - Replace `<YOUR_API_KEY>` in the notebook with your actual API key.

5. **Run the notebook**
```bash
jupyter notebook
```

---

## 📌 Conclusion
This project utilizes the YouTube API through Python for data extraction related to the "Avatar movie." It involves:

- Setting up the API key
- Extracting video details
- Obtaining statistics for the top 50 videos in the US
- Sorting videos by top comments
- Exporting data in JSON and CSV formats
- Calculating likes vs views ratio for videos

By leveraging programmatic data extraction, insights are uncovered to understand trends, preferences, and audience engagement.

---

## ✍️ Author

**Pooja Pandit**
Master’s Student in Information Science (Machine Learning)
The University of Arizona

[![GitHub](https://img.shields.io/badge/GitHub-panditpooja-black?logo=github)](https://github.com/panditpooja)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pooja--pandit-blue?logo=linkedin)](https://www.linkedin.com/in/pooja-pandit-177978135/)
