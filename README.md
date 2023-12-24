# league_prediction

This notebook is inspired by the book "Soccermatics" by David Sumpter.

The model is a raw version prediction of the future outcome of a league given the previous one. Many functionalities are provided:
- n number of iterations to see many possible final results
- access to every final table is possible
- number of successes recapped at the end
- preprocessing on the data due to some inconsistencies
- the results are modelled based on a poisson distribution based on the average number of goals that a team performed at home (away respectively) + the average number of goals the other team conceded away (home respectively), and viceversa

Final remarks:
- the model works but results are way too close to last year's final table
- in some cases the average number of goals scored and conceded is not a good indicator
- the poisson distribution captures effectively what I wanted to test
- more accurate techniques are crucial to get more meaningul results

![Example of final Outcome](relative_path_to_image)
