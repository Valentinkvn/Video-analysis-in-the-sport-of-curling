# Video-analysis-in-the-sport-of-curling

This project is part of the assignments presented by professor Bogdan Alexe (Faculty of Mathematics and Computer Science, University of Bucharest) for the Computer Vision course.

The project was structured having four tasks:
1. Correctly count how many stones are on the ice surface and how many of these stones are red and yellow.
2. Correctly calculate the potential score based on the configuration of stones on the ice in videos in the constrained scenario showing
the ice surface from above.
3. Track the stone thrown by a player in a constrained scenario showing the ice surface from above and given the first location of the stone.
4. Track the stone thrown by a player in a unconstrained scenario showing the ice surface from different viewpoints.

More details on the implementation are present in the [Jupyter notebook containing the code of the project](Video-analysis-in-the-sport-of-curling.ipynb)

The final results (accuracy) on the train and test data were:
| Task | Train | Test |
|------|:-----:|:----:|
| 1    |  96%  |  80% |
| 2    |  93%  |  93% |
| 3    |  93%  |  93% |
| 4    |  70%  |  70% |
