# Video Game Recommendation Model

This recommendation model utilizes a content-based filtering approach to suggest games related to a user-entered title.

1. It caluclates a weighted score using the IMDB formula for each title
2. Get's the genre/tags of user-entered title
3. Finds games with similar tags
4. Gives recommendation based on the best weighted score.

The final usage is based on a GUI created through Gradio with multiple options including minimum year, maximum number of recommendations, platform choice etc.
