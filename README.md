# When-Was-the-Golden-Era-of-Video-Games
Project Description
According to Mordor Intelligence, video games are big business: the global gaming market is projected to be worth more than $300 billion by 2027. With so much money at stake, the major game publishers are hugely incentivized to create the next big hit. But are games getting better, or has the golden age of video games already passed?

In this project, I have analyzed video game critic and user scores, in addition to sales data for the top 400 video games released since 1977. I have searched for a golden age of video games by identifying release years that users and critics liked best, and also explored the business side of gaming by looking at game sales data.

My search involved joining datasets and comparing results with set theory. I have also filter, group, and order data. The database contains two tables. Each table has been limited to 400 rows for this project, but you can find the complete dataset with over 13,000 games on Kaggle.

Here I have done these tasks:
1. Find the ten best-selling games. The output should contain all the columns in the game_sales table and be sorted by the games_sold column in descending order. Save the output as best_selling_games.

2. Find the ten years with the highest average critic score, where at least four games were released (to ensure a good sample size). Return an output with the columns year, num_games released, and avg_critic_score. The avg_critic_score should be rounded to 2 decimal places. The table should be ordered by avg_critic_score in descending order. Save the output as critics_top_ten_years. Do not use the critics_avg_year_rating table provided, this is has been provided for your third query.

3. Find the years where critics and users broadly agreed that games released were highly rated. Specifically, return the years where the average critic score was over 9 OR the average user score was over 9. The pre-computed average critic and user scores per year are stored in users_avg_year_rating and critics_avg_year_rating tables respectively. The query should return the following columns: year, num_games, avg_critic_score, avg_user_score, and diff. The diff column should be the difference between the avg_critic_score and avg_user_score, it should be a positive float. The table should be ordered by the diff column in ascending order, save this as a dataframe named golden_years.
