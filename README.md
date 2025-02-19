# Sp25Proj2
Project 2 for Spring '25 Data Structures

Question 1: If you were not already running at 60 fps, how much improvement did you get?

 My framerate got 59-60 after implementing the changes in the code.(we can see the improfment)

Question 2: What is the time-complexity of your algorithm as it depends on the number of nodes?

The sorting step runs in O(n log n), while the optimized for-loop runs in O(n). This makes the total time roughly n log n + 20n(about 20 elements per node). Since Big-O notation ignores smaller terms, the overall complexity is simply O(n log n).