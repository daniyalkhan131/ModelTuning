# ModelTuning

Model Tuning-
	GridSearchCV 
		we use this when less no. of hyperparameters and also less data as trainig
		takes a lot of time, very time consuming
	RandomizedSearchCV
		this take randomly some combinations out of all and find out best
		value among those, it is less computationally expensive
		we can control how much combinations it should take so can take larger
		value for less time taking models
		in this we can define hyperparameter range with some distribution rather
		than explicitly define values in array and by chance or randomly it can
		opt that value which give best result in model and that is not there in
		list we define.
