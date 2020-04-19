"""
Date: 04/19/2020
Class: CS5541
Assignment: Dining Philosophers
Author: Mukesh Viswanathan
"""
The dining philosophers algorithm:

1. Duke always reaches for the chopstick on his left first. If the chopstick is there, Duke takes it and raises his left hand.
2. Duke tries for the right chopstick. If the chopstick is available, Duke picks it up and raises his right hand.
3. When Duke has both chopsticks, he takes a bite of rice and says, Good!
4. He then puts both chopsticks down, thereby allowing either of his two neighbors to get the chopsticks.
5. Duke then starts all over again by trying for the right chopstick. Between each attempt to grab a chopstick, Duke pauses for a random period of time.

How to run:

1. Open the folder on VS Code or a terminal. 
2. Run dining_philosophores.py   - Shows how the Philosophers are free of deadlock and starvation. 
3. Run dining_philosophor(deadlock).py - Shows how the philosophers are prone to deadlock being vulnerable.
4. Run dining_philosophor(starvation).py -Shows how the philosophers are vulnerable to starvation.

IMPORTANT NOTE: 
I have given the break statements to get out of the deadlock but it may not work sometimes. If it works, well and good but if not, give "ctrl+z" on your terminal or IDE.

Further explaination is done in the report. 

There are few existing python libraries but there is no pip install needed. 

As you may know, the dining philosophers problem is meant to solve the deadlock or starvation between the processes in an Operating System or any Multi-threading activities. 


References:
1. https://github.com/angrave/SystemProgramming/wiki/Deadlock,-Part-3:-Dining-Philosophers
2. http://www.montefiore.ulg.ac.be/~pw/cours/psfiles/struct-cours9-e.pdf
3. https://rosettacode.org/wiki/Dining_philosophers
4. https://www.geeksforgeeks.org/dining-philosophers-solution-using-monitors/
5. https://github.com/muks97/dining-philosophers/

