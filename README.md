# Finding Features that Has Important Effect on Streamers Revenue

This project was conducted for my technical test at MainGames as a Data Scientist. [MainGames](https://maingames.com/) is a leading Facebook Gaming creator agency (official partner) that originated in Indonesia. They were opening a job application for Data Scientist and I was able to proceed into the technical test for that position. Unfortunately, I was unable to finish my assignment at the scheduled time. So, I took the initiative to post this project on my GitHub repository as you can see right now. It was a fun project and it is really challenging for me to solve the main problem statement effectively using a comprehensive analytics technique from descriptive to prescriptive analytics.

Please, check out the notebook that called **Notebook_for_Data_Analysis.ipynb**. I also created a streamlit web app to showcase my model to predict PaidStarPerWathcedHour as the metrics of streamers revenue. Click [**here**](https://share.streamlit.io/ayusufalba25/streamrevapp/StreamRevApp.py) to check the web app.

## Problem Statement

At MainGames we are committed to help streamers increase their revenues by leveraging the rich source of streaming data to provide actionable insights. In this problem, we want to learn whether certain features of streamers will make them more or less likely to receive stars from their audience, in this case **PaidStarPerWatchedHour** is our dependent variable (target variable).

## Conclusion

Here are our conclusions to answer the main problem statement:

1. There are 7 features that has important effect on PaidStarPerWatchedHour which are: 
    - Gender_Female,
    - Country_PH,
    - Game_Free Fire - Battlegrounds,
    - Game_PUBG,
    - Character_Facet_Cont_Dutifulness,
    - Character_Facet_Cont_Morality, and
    - Self_Esteem_Cont_SEDiscrepancyIntelligence.
2. Features that has positive effect on PaidStarPerWatchedHour are:
    - Gender_Female,
    - Country_PH,
    - Game_PUBG, and
    - Self_Esteem_Cont_SEDiscrepancyIntellgigence.
3. Features that has negative effect on PaidStarPerWatchedHour are:
    - Character_Facet_Cont_Dutifulness, and
    - Game_Free Fire - Battlegrounds.
4. Last but not least, Character_Facet_Cont_Morality has highly fluctuating patterns and is somewhat quadratic.

## Recommendation

For the overall streamers, we can only give recommendations based on the features beside Gender_Female and Country_PH. Below are the recommendations:

1. Game_Free Fire - Battlegrounds and Game_PUBG: Streamers should consider to play games other than Free Fire - Battlegrounds in their streaming. It is also better to play PUBG in their streaming because it has positive effect on their chances to get more PaidStarPerWatchedHour.
2. Self_Esteem_Cont_SEDiscrepancyIntellgigence: Streamers should give "big-brain-move" and high self-esteem while they are playing games in their streaming to confidently show their intelligence to the audience. It will also make the audience more entertained when streamers gave them "wow" moments and they will be amazed at the task that streamers did in the game. Therefore, audience will likely to give streamers more PaidStarPerWatchedHour.
3. Character_Facet_Cont_Dutifulness: Streamers should be more creative in their playing while streaming the game and make it more joyful. This particular approach will make their character facet to be less dutiful (too serious) and make them get more PaidStarPerWatchedHour.
4. Character_Facet_Cont_Morality: Streamers should decide whether they want to act like a bad guy or a good guy in the game to make it more interesting. It will also affect their character facet to support their chances to get more PaidStarPerWatchedHour.

MainGames should give those recommendations to its streamers effectively by elaborating and considering all the 9 clusters that have been generated using K-means clustering as their target. MainGames could also provide platforms for daily recommendations and stats for their streamers based on those features (except for Gender_Female and Country_PH) and tract their effect on the increase of their PaidStarPerWatchedHour. Streamers will use these platforms to evaluate their performance and strategy to make effective streaming gameplay.