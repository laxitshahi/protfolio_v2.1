---
layout: '@layouts/Layout.astro'
title: 'Bayes Theorem'
---

## The Equation

The formula for Bayes Theorem is as follows:
```latex
$$P(H|E) = \frac{P(H)*P(E|H)}{P(E)} $$
```

The value for the denominator is general broken down into:
$$P(H)*P(E|H)+P(!H)*P(E|!H)$$

Great, we now have an equation, so what?

## When is it useful?
Consider the following example:

>Steve is very *==shy and withdrawn==* invariably helpful but with very little interest in people or in the world of reality. A *==meek and tidy soul==*, he has a need of order and structure, and a passion for detail.

```ad-question
If I were to ask you if Steve was a farmer, or a librarian, which one would you choose?
```

The reality is, many people tend to match the obvious characteristics, and simply just match it to a librarian. The psychologists whom underwent this study argue that this is illogical.

Why? 
- Because you do not consider that in the US the proportion of librarians to farmers is roughly 1:20
- Even if we were to say that roughly 40 percent of libraries fit this description, we would only have a 16.67 percent chance of Steve being a librarian

## Graphically + Mathematically
Lets consider the ratio of lib:farm in the quantity of 10:200
- Given this, let's quantify our belief

Lets estimate that roughly 40 percent of the librarians (you can pick more, this is just an percentage on your intuition) fit the description above, and only 10 percent fit the description for a farmer.

```ad-question
What would be the graphical representation of the number of farmers to librarians?
```


![[bayes theorem 2024-08-18 16.49.54.excalidraw]]
- Given this subset, what is the chance that 'librarian' is the correct choice?
- Well, in the librarian block there are 4 and in the farmers block there are 20
	- Although it is a smaller percent of he total population of farmers, we still get 5 times more farmers!
- So numerically we *ONLY have a 16.68 percent chance of being correct!* 
	- If we choose farmer we have a *83.34 percent* chance of being correct!!

$$\frac{P(H)*P(E|H)}{P(E)} =\frac{4}{4+20}=0.1678$$

```ad-missing
Note, some people do argue that the initial prompt is too ambiguous, so it may not be sensible to start thinking about the number of farmers vs librarians. What do you think?
```


As stated in the video, this can be argued by the psychologists. What is arguably more important for everyone to consider is the powerful mindset this brings. You beliefs should be a spectrum that is updated based on new belief, not black and white.

```ad-question
- If more people in the world adoptted the 'Bayes Mindset', would the world be a objectively better place?

- Would this reduce the number of people that overthink and misunderstand in the world?
```

# References
- https://www.youtube.com/watch?v=HZGCoVF3YvM
