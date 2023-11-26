# Data Analysis Capstone: An Analysis of Taylor Swift Lyrics 2006-2023

 ![Alt text](image.png)

## About
This project aims to analyize the lyrics from Taylor Swift's first 10 albums, as well as the "vault tracks" on her rerecordings of Fearless, Speak Now, Red, and 1989. We will be looking at which words are most commonly used in her songs, which songs have the highest amount of unique individual words, and what percentage of songs have clean or explicit lyrics.

## Data Sources
- https://www.kaggle.com/datasets/nickpvl/taylor-swift-song-lyrics
- https://www.kaggle.com/datasets/arthurboari/taylor-swift-spotify-data

CSVs:
- taylor_album_songs.csv: contains the names of all Taylor Swift albums, their songs, date of release, etc.
- taylor_lyrics.csv: contains all Taylor Swift lyrics from albums released between 2006 and 2023.

## Installing the Virtual Environment
Please follow these steps to run this project on your local machine:
1. Clone the repository
1. Navigate to the cloned directory
1. Set up a virtual environment using your terminal

    On windows:

        ` python -m venv venv `

    On macOS or Linux:

     ` python3 -m venv venv `

1. Activate the virtual environment

    On Windows:

        ` .\venv\Scripts\activate `
    
    On macOS or Linux:

        ` source venv\bin\activate `

1. Install requirements.txt to ensure that you are running the required packages

    ` pip install -r requirements.txt `

To deactivate the virtual environment, simply type "deactivate" in your terminal


## Data Analysis Capstone Requirements (Spring 2023)
Category 1: Loading Data:
    -Read TWO data files (JSON, CSV, Excel, etc.).

Category 2: Clean and Operate the Data While Combining Them:
    -Clean your data and perform a pandas merge with your data sets, then calculate some new values based on the new data set.

Category 3: Visualize/Present Your Data:
    -Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.

Category 4: Best Practices:
    -Utilize a virtual environment and include instructions in your README on how the user should set one up.

Category 5: Interpretation of Your Data:
    -Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don't have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.