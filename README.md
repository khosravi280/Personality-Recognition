# Personality Recognition in Social Networks Using Topic Modeling of User Opinions
In this research project, an attempt has been made to identify their personality using the text that users share on the Instagram social network. 
First, the standard personality questionnaire was filled by a number of volunteers, then their Instagram account was flowed and all the texts they shared were extracted.
then by matching their personality type with the texts they share using machine learning algorithms. A personality prediction model is obtained that can predict the personality of new people.
# Project file and how to implement them
The project is in c# language and uses the pysharp library, the project is a console application.
In order to run, you must have visual studio and build the project in it and then run it.
The script.sql file is the data of the project, which is in the sql server database (the data is included with the database tables).
The Program.cs file is the main executable file of the program.
The EFDB folder is the database model or entity framework.
The DataPreProcess.cs file is written for text preprocessing and uses the NHazm library.
The ClassificationReport.py file is written in Python and called in the process due to the lack of proper support in C#.
The NeuralNetworkHandler.cs file is for modeling and executing the algorithm using the neural network and Keras.
The SVMHandler.cs file is for modeling and executing the algorithm with SVM.
