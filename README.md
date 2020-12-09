# machine_vision_cw1
I establish a model using MOG to distinguish red and green apples.

o	Trained 2 mixtures of Gaussians (MOG) models for apple pixels as there are two kinds of color (red and green) and trained 3 MOG models for non-apple pixels to prevent from falling into a local maximum since the starting point is random.

o	I applied a thresholds to the posterior to produce set of true positive rate(TPR) and false positive rate (TPR) to obtain an receiver operating characteristic curve(ROC). 

o	The generated graphs include original, posterior, ground truth and threshold images

