# Movie recommendation
Jan Borowski Piotr Fic

The application proposes movies to the user based on his preferences.\
It works basing on item-item collaborative filtering algorithm proposed by Badrul Sarwar, George Karypis, Joseph Konstan, and John Riedl in "Item-Based Collaborative Filtering Recommendation Algorithms" (2001).\
Our implementation allows user to score at least 10 movies from 30 titles which enables calculation of prediction.\
This approach reduces time of calculating the result to unnoticeable, thanks to constant result of one of algorithm steps.

### Data
Data base used to run algorithm is shared by MovieLens (https://grouplens.org/datasets/movielens/). It was reduced and cut to fit the porpouse of recommendation algoritm. The final file is available here: https://drive.google.com/open?id=1sErnGcBDQwrVoEPU-zdJ0uuw7hR87rne \
App should work without it (in our approach it is used only once during algorithm and the result is saved also in files on this repository).
