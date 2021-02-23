# Domain background : Image recognition attacks

Problem statement: 
In this competition, you'll write an algorithm to classify whether images contain either a dog or a cat.  This is easy for humans, dogs, and cats. Your computer will find it a bit more difficult.
In this competition, you'll write an algorithm to classify whether images contain either a dog or a cat.  This is easy for humans, dogs, and cats. Your computer will find it a bit more difficult.
 
Deep Blue beat Kasparov at chess in 1997.
Watson beat the brightest trivia minds at Jeopardy in 2011.


#Datasets and inputs:
Web services are often protected with a challenge that's supposed to be easy for people to solve, but difficult for computers. Such a challenge is often called a CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart) or HIP (Human Interactive Proof). HIPs are used for many purposes, such as to reduce email and blog spam and prevent brute-force attacks on web site passwords.
Asirra (Animal Species Image Recognition for Restricting Access) is a HIP that works by asking users to identify photographs of cats and dogs. This task is difficult for computers, but studies have shown that people can accomplish it quickly and accurately. Many even think it's fun! Here is an example of the Asirra interface:
Asirra is unique because of its partnership with Petfinder.com, the world's largest site devoted to finding homes for homeless pets. They've provided Microsoft Research with over three million images of cats and dogs, manually classified by people at thousands of animal shelters across the United States. Kaggle is fortunate to offer a subset of this data for fun and research. 

#Solution statement:
The propose solution is provide the model based on CNN to distinguish Dogs VS Cats images. I used Pandas to load and explore data .

#Benchmark model:
The current literature suggests machine classifiers can score above 80% accuracy on this task. Therfore, Asirra is no longer considered safe from attack.  We have created this contest to benchmark the latest computer vision and deep learning approaches to this problem. Can you crack the CAPTCHA? Can you improve the state of the art? Can you create lasting peace between cats and dogs?

#Evaluation metrics:
Performance is evaluated on the percentage of correctly labeled images. To determine your odds of breaking the Asirra CAPTCHA, raise your percentage to the 12th power.
"But classification accuracy is a flawed metric!" you scream at your monitor in fury, "my genius requires you accept the posterior probability of my predictions!"  That may be true, but sometimes simplicity is just nice. Here there are only dogs and cats... no 0.5 dog-cat hybrid guesses allowed!
    
#Project design:
-   Programming language: Python 3.6, 
-   Library: Keras, Pandas, Numpy, 
-   Workflow:
-   The project will be separate on 
-	Data understanding
-	Data exploration and visualisation 
-	Split data in train and test.
-	Define the model (train and test file) 
-   Training the model
-	Evaluating the model
