# Netflix-Movie-Recommendation-using-Association Rule Learning

GOAL: To develop a Machine Learning algorithm to predict which movie will the user is likely to watch based on the previously watched movies on the given dataset.

STEPS:
Using ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal) algorithm.
1. Data Pre-Processing:
   1. Installing Apyori
   2. Importing Libraries
   3. Importing Dataset
2. Setting a minimum SUPPORT.
3. Taking all the subsets in transactions having the higher support than minimum support.
4. Sorting these subsets by decreasing support.
5. Diplaying raw results.
6. Displaying results in a better format.
7. Displaying the top 10 movies that users are likely to watch after watching the previous movie they watched.

CONCLUSION:
The top 3 movies that users are likely to watch after the previous movie they watched based on ECLAT are:
1. Interstellar & Inception
2. Kanan Gill Comedy & Comedy nights with Kapil
3. Harry Potter 1 & Harry Potter 2
