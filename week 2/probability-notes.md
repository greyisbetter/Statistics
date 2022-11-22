# Probability 

# Introduction
## The Interpretation of Probability

### What is Probability?
- In 2015 there were about 4 million babies born in the US, and 48.8% of the newborns were girls.
	- P(newborn is a girl) = 48.8%
- The probability of an event is defined as the proportion of times this event occurs in many repetitions (standard definition of probability). Possible to repeat this chance experiment many times. 

- The long-run interpretation of probability can make it difficult to interpret it for single event:
	- 'What I was wrong about this year' by David Leonhardt (12/24/2017)
- Sometimes people use a different interpretation:
	- 'The probability that my best friend calls today is 30%
	-  this statement clearly cannot be interpreted as a long-run frequency because today, the particular circumstances of today happened only once.
- Such a 'subjective probability' is not based on experiments, and different people may assign different subjective probabilities to the same event.

# Four Basic Rules
## Complement, Equally Likely Outcomes, Addition, and Multiplication

### Four basic rules
- Probabilities are always between 0 and 1. Computing probabilities comes down to applying a few basic rules repeatedly:
- A for an event, such as A = 'newborn is a girl'
- **Complement rule**: P(A does not occur) = 1-P(A)
- Complement: a number or quantity of something, especially that required to make a group complete.

- a different chance experiment: Rolling a die.
- Each of it's six faces is equally likely to come up, each has probability 1/6.
- **Rule for equally likely outcomes**: If there are *n* possible outcomes and they are equally likely, then P(A) = (number of outcomes in A)/n

- **express probabilities of multiple events as those of the individual events.**

- A and B are *mutually exclusive* if they cannot occur at the same time.
- As an example, we roll a die twice.
	- A = 1 on first roll, B = 6 on first roll, C = 1 on second roll
	- A and B are mutually exclusive: because when have 1 on first roll then we cannot have 6 on first roll
	- A and C are not. Because if we have 1 on first roll, then we can also have 1 on second roll.
	- **Addition rule**: If A and B are mutually exclusive, then
		- P(A or B) = P(A) + P(B)

	- Two events are *independent* if knowing that one occurs does not change the probability that the other occurs.
	- B and C are independent, because B concerns the first roll, and C concerns the second roll, and the outcome of the second roll doesn't depend on the outcome of the first roll.
	- A and B are not independent, because if you have a 1 on the first roll, then we cannot have a 6 on the first roll.
	- A will affect the outcome of B.
	- **Multiplicatin rule**: If A and B are independent, then
		- P(A and B) = P(A) x P(B)

## Four Rules Example: How to Deal with "At Least One"
- Roll a die 3 times. What is P(at least one 6)?
- We could write at least one 6 as follows:
- 6 on the first roll or 6 on the second roll or 6 on the third roll
- But these three events are **not** mutually exclusive, so we can't use the addition rule.
- Better way: Start with the complement rule.
- P(at least one 6 in three rolls)
- = 1-P(no 6 in 3 rolls)
- = 1-P((no 6 in 1st roll) and (no 6 in 2nd roll) and (no 6 in 3rd roll))
- = 1-P(no 6 in 1st roll)x P(no 6 in 2nd roll)x P(no 6 in 3rd roll)
- = 1- (5\6) x (5\6) x (5\6) = 41.4%

## Solving Problems by Total Enumeration
### Conditional Probability
- Spam e-mail has a higher chance to contain the word 'money' than ham e-mail:
- P('money' in e-mail | spam) = 8%, P('money' in e-mail | ham) = 1%