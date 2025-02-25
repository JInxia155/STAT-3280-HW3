Download Link : https://programming.engineering/product/stat-3280-hw3/

# STAT-3280-HW3
STAT 3280 HW3


    (4 pts) You worked on the data set of face images last time. The data set contains only 4 faces in HW2. It is a subset of a larger data set with 698 images. This time, we will work on the full data set and use PCA/MDS to deal with the data. In the le \Full Faces Data.Rda”, there is a matrix object face, in the dimension of 698 4096. You can use the R command

load(“Full Faces Data.Rda‘”)

to load it into your R environment. Each row of the matrix is a 4096 dimensional vector, representing the 64 64 image, as you have tried last time. For this problem, rst embed all the 698 images into a two-dimensional space by either PCA or MDS (up to your choice). After doing this, you will have a two-dimensional coordinate for each image. Let’s call them Coord1 and Coord2. Now, calculate the min, 25% quantile, median, 75% quantile, and max of the Coord1 values, and locate which images correspond to these ve values (if you have ties, pick any one with the same value). Now visualize these ve images as you did last time, but arrange them in one row with the increasing order of their Coord1. The uniform variation pattern of them will give you a sense of what is the feature captured by your Coord1 (e.g. from facing-left to facing right, or from facing-down to facing-up, whatever pattern you could observe). Summarize the pattern. Then do the same thing, but this time focus on Coord2. (Visualization 1.5 pts for each of Coord1 and Coord 2. 0.5 pt for summarizing pattern in each of Coord1 and Coord2)

    (6 pts) We would introduce the data set about diving competition judgement in class. The target for the analysis will be evaluating the nationality bias from the judges. Are the judges tend to be biased towards divers from their own countries? Who are more

biased in this setting? Answer these question and potentially explore other patterns by a one-page visualization results. Only brief descriptions by plain language are allowed. (2 pts for informative answer to each of the two questions. 2 pts for insightful analysis beyond the two questions.)

    (7 bonus pts). Challenge: About the face data again. Still use the same 2-dimensional coordinates. Pick the rst 20 of them (row 1 to row 20). Generate a gure similar to the gure below: For each of the 20 images, visualize the image at the same location as their two-dimensional coordinates, up to tiny rounding errors for the position. For this problem, you have to completely rely on R. You can use di erent packages, but cannot us other softwares. (Any successfully generated gures that satisfy the basic requirements would earn 2 bonus points and an invitation to presentation in class. The audience will wait for up to 5 bonus points for the presenter team.)

2
