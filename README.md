# Steam Spotlight

My app helps Steam’s store team decide which titles it should feature on the website landing page by analyzing the critic reviews, required age, and average playtime hours of each title.

> A course project for **MIST 4600: Computer Programming in Business** at the University of Georgia's Terry College of Business (Fall 2026).

## Problem

Steam’s store team needs to decide which games to feature on the website’s landing page. Comparing titles consistently is difficult when critic feedback, playtime within each genre, and age suitability must be evaluated separately. The team also needs to consider whether featured games are appropriate for users whose ages have not been verified.

## What it does

My app answers three questions:

1. **Critic reviews:** What do critics say about the game? An LLM will be used to evaluate the review contents.
2. **Playtime:** How long do users typically spend on each game compared with other games in the same genre?
3. **Age suitability:** Is the game family-friendly enough to feature to users whose ages have not been verified? Games with a required-age value of 0 will be flagged for further review.

## Data

The [Steam Games Dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) on Kaggle, collected in March 2025. The dataset is shared under the MIT License by its creator, artermiloff. This repo uses `steam_games.csv`, a smaller file made for the course: the 1,000 games with the most reviews.

## Built with

- Python and pandas, in Google Colab
- Coming soon: my outside tool

## How to run it

Coming soon

## Example output

Coming soon

## AI Use Disclosure

Coming soon

## Author

David Sustana
