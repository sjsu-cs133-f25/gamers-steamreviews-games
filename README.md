# gamers-steamreviews-games
This is a data visualization project for CS 133, we are analyzing Steam Reviews and game metadata to understand trends in player retention, game enjoyability, player sentiment, and overall Steam trends. We utilize two datasets, Steam Game Reviews (990K rows) and Steam Games Reviews and Rankings (242 rows). These datasets provide game metadata such as genres, user reviews, recommendations, and dates to allow for timescale analysis.

## Team 4 Members
- Jake Johnson
- Nathan Wong
- Lawrence Cuenco
- Sai Vishnumolakala

## Datasets
These are links to dataset downloads to set up the project. These should be placed in the `/data` folder and should not take more than a few minutes.

1. Steam Reviews Dataset - https://www.gigasheet.com/sample-data/steam-game-reviews (~500 MB) (990K rows)

2. Steam Game Metadata - https://www.kaggle.com/datasets/mohamedtarek01234/steam-games-reviews-and-rankings (~1 MB) (242 rows)

The Steam Reviews Dataset contains a significant amount of information surrounding what users value in games and in critiques. This can provide video game companies insight into what types of games players enjoy. With 990K rows over the course of 2014 to 2024, this dataset gives a significant amount of information on trends in user sentiment. The Steam Game Metadata dataset enriches the reviews with information on genre and popularity of games. It gives further insight into what qualities players appreciate in certain types of games.

## Notebooks
*NOTE*: Ensure that the data is properly downloaded and placed in `/data` as instructed in the `/data` README file.

`notebooks/brainstorm.ipynb` - This contains brainstorming and data exploration for ideas regarding the project. Multiple other datasets can be found here that were considered for the project, including the dataset currently being used for this project.

`notebooks/01_explore.ipynb` - Contains exploration of the Steam Reviews Dataset as well as data cleaning and exploratory visualizations.

## Setup Instructions

1. Clone the Repository
```
   git clone https://github.com/<your-username>/Gamers-SteamReviews-Games.git
   cd Gamers-SteamReviews-Games
```

2. Create a Virtual Environment (Optional but Recommended)
   On Mac/Linux:
```
    python3 -m venv venv
    source venv/bin/activate
```
   On Windows:
```
    python -m venv venv
    venv\Scripts\activate
```

3. Install Dependencies
```
   pip install -r requirements.txt
```
4. Run the Notebook!
- Note you will need to download associated datasets and add them to the data folder to run the notebook properly.
