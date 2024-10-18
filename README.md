This project is related to chemical engineering and petroleum refining, The main goal is to convert Mazot(fuel oil) to Diesel and try to maximize its production to raise its value from the economic prespective.
conversion process (aka reaction) occurs inside a reactor called hydrocracker with average conditions of 130 bar and 360 degree celesius and this reactor is non isothermal catalytic reactor which means there're all sorts of complications inside this reactor
and there's a complicated reaction network that connects all of these reactions happened inside the reactor together so the main goal is to solve the system first and try to optimize it using machine learning algorithms
I have used python and machine learning to model the system and optimize it to find the optimum operating parameters for the Hydro cracker to maximize the diesel

Step1 : Solving the system of differential equations using Scipy Library and drawing the profiles
Step2 : Solving the system iteratively by trying different operating parameters and store all the results in a data frame in order to analyze it later
Step3 : finding the correlation between the variables and constructing the features and target
Step4 : Training and Evaluating the model accuracy 
