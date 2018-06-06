# Dice-Roll-Experiment
Jupyter Notebook experiments to show my friend:

1) that rolling at least one 6 in 3 rolls only has a chance of roughly 42% of happening not 50% like they assumed. This is because each time you have a 1 in 6 chance of rolling a 6. Two ways to prove this mathematically are 1 - (5/6) or (5/6)^2*(1/6)*3 + (5/6)*(1/6)^2*3 + (1/6)^3. The second way is the probability of exactly 1 6 rolled plus the probability of exactly 2 sixes rolled plus the probability of exactly 3 sixes rolled.

2) that rolling at least one 6 in 6 rolls has a chance of 66.51% of happening and that getting them back to back has only a 44% chance of happening. They thought this would basically happen every time. The reason it is roughly 44% is because the chance of any given dice roll is a 6 is 1/6, meaning a chance that no dice rolled out of 6 was a 6 is (5/6)^6 because the chance a dice roll isn't a 6 is 5/6 and to the power of 6 because you rolled 6 times. Now 1-(5/6)^6 is .6651 or 66.51% and to do it twice would be .6651 * .6651 = 44.23%
