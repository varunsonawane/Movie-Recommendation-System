# 🎬 Movie Recommendation System

## 📝 Table of Contents
- [📚 Introduction](#📚-introduction)
- [🔧 Features](#🔧-features)
- [👨‍💻 Installation](#👨‍💻-installation)
- [🔍 Usage](#🔍-usage)
- [🛠️ Technologies Used](#🛠️-technologies-used)
- [📊 Dataset](#📊-dataset)
- [💡 Future Enhancements](#💡-future-enhancements)

## 📚 Introduction
The **Movie Recommendation System** suggests personalized movie recommendations to users based on their past ratings and preferences. It employs a **Content-Based Filtering** approach, analyzing movie attributes such as genre, cast, and director to find similarities and recommend movies that align with user interests.

## 🔧 Features
- 👤 **Personalized Recommendations**: Suggests movies tailored to individual user preferences.
- 🔍 **Content-Based Filtering**: Analyzes movie attributes to recommend related movies.
- 📊 **Scalability**: Capable of handling large datasets of movies and user interactions.

## 👨‍💻 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/varunsonawane/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```
2. **Install the required Python packages**:
   ```bash
   pip install -r requirements.txt
   ```

## 🔍 Usage
1. **Prepare the dataset**: Ensure `movies.csv` and `ratings.csv` are present in the project directory.
2. **Run the recommendation script**:
   ```bash
   python main.py
   ```
3. **Interact with the system**: Follow the on-screen instructions to input preferences and receive movie recommendations.

## 🛠️ Technologies Used
- 🐉 **Python**: Core programming language.
- 📊 **Pandas**: Data manipulation and analysis.
- 💻 **Scikit-learn**: Machine learning algorithms.

## 📊 Dataset
Utilizes the **MovieLens** dataset, containing user ratings, movie titles, and genres for training the recommendation model.

## 💡 Future Enhancements
- 🧰 **Collaborative Filtering**: Combine user interaction data for improved recommendations.
- 💻 **Enhanced User Interface**: Develop a GUI for better user experience.
- 🛠️ **Real-time Data Integration**: Fetch live movie data and ratings from online APIs.

