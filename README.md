# Assessment-NVIDIA-FUNDAMENTALS-OF-DEEP-LEARNING-FOR-COMPUTER-VISION-Certification

At this point, you've worked through a full deep learning workflow. You've loaded a dataset, trained a model, and deployed your model into a simple application. Validate your learning by attempting to replicate that workflow with a new problem.

We've included a dataset which consists of two classes:  

1) Face: Contains images which include the face of a whale  
2) Not Face: Contains images which do not include the face of a whale.  

The dataset is located at ```/dli/data/whale/data/train```.

Your challenge is:

1) Use [DIGITS](/digits) to train a model to identify *new* whale faces with an accuracy of more than 80%.   

2) Deploy your model by modifying and saving the python application [submission.py](../../../../edit/tasks/task-assessment/task/submission.py) to return the word "whale" if the image contains a whale's face and "not whale" if the image does not.  

Resources:

1) [Train a model](../../task1/task/Train%20a%20Model.ipynb)  
2) [New Data as a goal](../../task2/task/New%20Data%20as%20a%20Goal.ipynb)  
3) [Deployment](../../task3/task/Deployment.ipynb)  

Suggestions: 

- Use empty code blocks to find out any informantion necessary to solve this problem: eg: ```!ls [directorypath] prints the files in a given directory``` 
- Executing the first two cells below will run your python script with test images, the first should return "whale" and the second should return "not whale" 
