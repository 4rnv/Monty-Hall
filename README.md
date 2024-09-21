# Monty Hall Problem
The Monty Hall problem is a brain teaser, in the form of a probability puzzle, based nominally on the American television game show Let's Make a Deal and named after its original host, Monty Hall.
The original statement of the problem goes as thus:

*Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the
doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" Is it to your advantage to switch your choice?*

Although intuition would suggest that switching the door would have no effect on the probablity of winning a car ( 1/2 probability of success either by switching or retaining), the truth is that
switching the door would result in a 2/3 chance of success, while retaining the original door would only result in 1/3 chances of success.

The chances of success after switching approach (N-1/N) where N represents the number of doors. For large values of N, the probability of success P(S) by switching is ~1 (near certainity). The
problem is a paradox of the veridical type, because the solution is so counterintuitive it can seem absurd but is nevertheless demonstrably true. 

In this python notebook you can specify the number of simulations as well as doors. For simulations with 3 doors, P(S) will be around 66%, for 5 doors around 80% and for 20 doors around 95%. Thus,
the claim that switching doors is more likely to lead to positive outcomes is demonstrably proven.

Web version available at https://huggingface.co/spaces/0xarnav/MontyHall.
