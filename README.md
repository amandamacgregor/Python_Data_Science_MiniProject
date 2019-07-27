# Python_Data_Science_MiniProject
Given the technological advances in special effects of movies, have average ratings for Horror films gone up over time?

I started by looking at a movie data set, filtering to see those classified as Horror, then looking at a ratings data set and grouping ratings as an average.  With each movie ID now having one average rating instead of mulitple user ratings per movie, I then joined the filtered movie data with the average ratings data.  By breaking out the year of the movie into a new column, I was able to group the data by year, with an average rating for the year.  With the year on the x-axis and the average rating on the y-axis, I used matplotlib to quickly create a line chart to allow for a visual answer to my above question.

The answer is no; average ratings for films classified as Horror have in fact trended down over time.  This seems to make sense - in the silent-film era, the story and characters had to be pretty strong for a film to get made.  More recently, effects are perhaps relied on more to carry a movie and draw an audience - and budget gets spent on those effects over other costs involved in making a movie.

