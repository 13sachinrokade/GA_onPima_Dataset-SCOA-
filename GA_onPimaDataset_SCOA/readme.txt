//Sachin Rokade


In this project we apply genetic algorithm on Pima Indians Diabetes Database.Predict the onset of diabetes based on diagnostic measures.
The datasets consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

GA- is One of the advanced algorithms in the field of computer science is Genetic Algorithm inspired by the Human genetic process of passing genes from one generation to another.It is generally used for optimization purpose and is heuristic in nature and can be used at various places. For eg – solving np problem,game.

Here are quick steps for how the genetic algorithm works:
Initial Population– Initialize the population randomly based on the data.
Fitness function– Find the fitness value of the each of the chromosomes(a chromosome is a set of parameters which define a proposed solution to the problem that the genetic algorithm is trying to solve)
Selection– Select the best fitted chromosomes as parents to pass the genes for the next generation and create a new population
Cross-over– Create new set of chromosome by combining the parents and add them to new population set
Mutation– Perfrom mutation which alters one or more gene values in a chromosome in the new population set generated. Mutation helps in getting more diverse oppourtinity.Obtained population will be used in the next generation
Repeat step 2-5 again for each generation