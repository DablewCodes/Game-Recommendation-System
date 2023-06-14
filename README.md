# Video Game Recommendation Model

This recommendation model utilizes a content-based filtering approach to suggest games related to a user-entered title.

### Working Mechanism

1. It caluclates a weighted score using the IMDB formula for each title
2. Get's the genre/tags of user-entered title
3. Finds games with similar tags
4. Gives recommendation based on the best weighted score.

### Usage

The final usage is based on a GUI created through Gradio with multiple options including minimum year, maximum number of recommendations, platform choice etc.

![Screenshot 2023-06-14 170438](https://github.com/DablewCodes/Game_Recommendation_System/assets/77541950/1e3509fb-8acb-4861-b0fc-6cff88cd903f)

Run the notebook `main.ipynb` for usage
