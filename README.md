📺 YouTube API Data Extraction Project
This project is designed to extract, analyze, and export YouTube video data using the YouTube Data API v3. With a focus on retrieving and processing metadata such as video titles, views, likes, and more, this project provides a clear snapshot of the top-performing videos from a given channel or search query.

🔍 Features
Uses the YouTube Data API to fetch video details (title, ID, views, likes, etc.).

Extracts and filters top videos based on like count.

Provides outputs in both Excel (.xlsx) and JSON (.json) formats.

Fully documented and executable via a Jupyter Notebook.

📂 Project Structure
├── youtube_data_extraction.ipynb      # Jupyter notebook with code & visualizations
├── top_videos_by_likes.xlsx           # Excel file containing top liked videos
├── top_videos_by_likes.json           # Same data as JSON format
├── README.md                          # Project description

🛠️ Technologies Used
Python 3.x
Jupyter Notebook
YouTube Data API v3
Pandas
JSON

📊 Sample Output
The extracted data includes:

Video Title

Video ID

Published Date

View Count

Like Count

Comment Count (optional)

📌 How to Use
Get your YouTube API key from Google Developer Console.

Insert the API key in the notebook where indicated.

Run the notebook to fetch, process, and export data.

✅ Output Examples
Excel File: top_videos_by_likes.xlsx – neatly formatted table for analysis or reporting.

JSON File: top_videos_by_likes.json – useful for downstream processing or APIs.
