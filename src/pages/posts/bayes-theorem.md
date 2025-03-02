---
layout: '@layouts/PostLayout.astro'
title: 'Bayes Theorem'
date: '2024-08-18'
time: '16:10'
tags: 'statistics, ML basics, overthinking'
---

# The Equation

The formula for Bayes Theorem is as follows:
$$P(H|E) = \frac{P(H)*P(E|H)}{P(E)}$$

The value for the denominator is general broken down into:
$$P(H)*P(E|H)+P(!H)*P(E|!H)$$

## Great, we now have an equation, so what?

Consider the following example: 

> Steve is very *shy and withdrawn* invariably helpful but with very little interest in people or in the world of reality. A *meek and tidy soul*, he has a need of order and structure, and a passion for detail.

Which profession do you believe Steve holds? Let's narrow it down even further, is Steve a **librarian or a farmer**? Instinctually, many people tend to match the very obvious characteristics, leading to simple conclusion: Steve is a librarian. However, the psychologists whom underwent this study argue that this is illogical.

Why? 
1. Because you do not consider that in the US the proportion of librarians to farmers is roughly 1:20
2. Even if we were to say that roughly 40 percent of libraries fit this description, we would only have a 16.67 percent chance of Steve being a librarian

## Graphically + Mathematically
Lets consider the ratio of lib:farm in the quantity of 10:200
- Given this, let's quantify our belief

Lets estimate that roughly 40 percent of the librarians (you can pick more, this is just an percentage on your intuition) fit the description above, and only 10 percent fit the description for a farmer.

> [!Question]  
> What would be the graphical representation of the number of farmers to librarians?


![A local image](@assets/blog/bayes-theorem-diagram.svg)

- Given this subset, what is the chance that 'librarian' is the correct choice?
- Well, in the librarian block there are 4 and in the farmers block there are 20
	- Although the percentage of framers is 4x lower, the total population of farmers means that we still get 5 times more farmers!
- So numerically we ONLY have a *16.68%* chance of being correct
	- If we choose farmer we have a *83.34%* chance of being correct!!

$$\frac{P(H)*P(E|H)}{P(E)} = \frac{4}{4+20}=0.1678$$


> [!NOTE]  
> Some people do argue that the initial prompt is too ambiguous, so it may not be sensible to start thinking about the number of farmers vs librarians. What do you think?


As stated in the video, this can be argued by the psychologists. What is arguably more important for everyone to consider is the powerful mindset this brings. Beliefs should be a spectrum that is updated, and fine tuned, based on new belief, not a rigid binary system.

- If more people in the world adoptted the 'Bayes Mindset', would the world be a objectively better place?
- Would this reduce the number of people that overthink and misunderstand in the world?

<!-- > [!Insight]   -->
<!-- > Highlights information that users should take into account, even when skimming. -->

# References
- https://www.youtube.com/watch?v=HZGCoVF3YvM
