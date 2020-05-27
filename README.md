# mlops3
# Job 1
Once Machine Learning Code is created and committed to Git Repository, then Jenkins job will be monitoring the repository, as soon as code is committed.
once it pull’s the code and trigger another job to train the model.
# Job 2
Model is trained to identify the images of cat and dog. Once model is trained it will provide accuracy.
# Job 3
Once Job2 is completed, it will check accuracy of the model. If desired accuracy is met then training of the model will be completed else it will trigger  another job, which will tune the model.
# Job 4
This job will tune the model i.e. adds extra layers or modify the pool size etc. Post it tune the model, then again model will be trained i.e. job 2 will be triggered automatically.
