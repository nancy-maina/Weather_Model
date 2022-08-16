# Weather_Model

Represent a cold day with 0 and a hot day with 1.
Suppose the first day of a sequence has a 0.8 chance of being cold.We can model this using the categorical distribution.
Suppose a cold day has a 30% chance of being followed by a hot day and a hot day has a 20% chance of being followed by a cold day.
Suppose additionally that on each day the temperature is normally distributed with mean and standard deviation 0 and 5 on a cold day and mean and standard deviation 15 and 10 on a hot day.

We can combine these distributions into a single week long hidden Markov model:
