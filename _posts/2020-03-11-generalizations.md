---
title: Generalizations
categories: notetheme
tags: [philosophy, critical-thinking]
---

# Generalizations

## Introduction

A **statistical inference** uses specific observations as evidence for general claims of which they are instances. If we have a pool of facts, we can check different areas of the pool and draw conclusions about the pool as a whole.

A **statistical generalization** is an inference of facts about a sample that lead us to a conclusion about the group at large. In constrast, a **statistical instantiation** is the opposite; we can infer facts about a group to lead us to a conclusion about a sample. Given a fact such as a probability of a feature in a group, this could guide our degrees of confidence that a random sample will have the same feature.

## Samples as evidence

If we want to observe what proportion of cars in the USA are red, we can take a sample of cars and see what proportion of those cars are red. In this case, we have:

> E = N percent of cars in sample are red
>
> H = roughly N percent of cars in the USA are red

We have to ask how much more likely are observation is if the hypothesis is strue than if it is false. It will depend on:

- Size of our sample
- Whether the sample is subject to any selection effects

If our sample is a **convenience sample**, as in, carelessly selected - this doesn't tell us much about the hypothesis at all.

### Selection effects

We could have only been looking at cars on the road, or in a wealthy section of town. When we create a selection effect due to the way we sample the population, we are creating what is known as a **sampling bias**. Remember the strength test. If we have:

> E = 6% of cars in sample are read
>
> H = roughly 6% of cars in the USA are red

It could be that there is a very different percentage of red cars in my sample than there are in the country. E bears little relationship to whether H is true since E could be true even if H is false, and vice versa. P(E\|~H) and P(E\|H) are too close.

### Sample size

Our probabilities of P(E\|H ) and P(E\|~H) need to be very different to each other for E to be strong evidence for H. We want to design tests where this is true.

Enter sample size. With a greater sample size, we can have many more opportunities to find evidence against and for our hypothesis due to the way probabilities in larger samples work (working out these probabilities will not be needed this chapter).

### The law of large numbers

The larger our sample, the more likely it is that is proportions closely reflect those of the population as a whole - this is the **law of large numbers**.

Consider tossing a coin. The more you do it, you get closer and closer to a 1/2 proportion of getting either heads or tails. Generally, the most extreme proportions will tend to be from the smallest samples. chance. Consider a disease in the USA. If 1 in 1000 people have it, then we should expect every county in the country to have the same percentage of people in the disease, right? No! Some counties are much larger than others. Given the law of large numbers, we can expect the very highest *and* very lowest rates of the disease to come from small counties.

### Big enough

How big is big enough? This depends on how narrow our **margin of error** needs to be. Consider a study where exactly 65% of our sample agrees with a certain policy. We can have two different hypothesis stemming from this:

- Exactly 65% of the US population approves of the policy
- Between 60% and 70% of the US population approves of the policy

Our evidence supports the second hypothesis much more strongly due to how the strength test works. 

It's easier to get strong evidence for wider ranges. The more precise our conclusion, the larger sample size we need to support it. An arbitrary convention states that surveys aim for *95% confidence interval with a 3% margin of error*. 

### Sampling methods

We can try to ensure our sample is as **representative** of a given population as possible, with the same sort of *variety*. For example, if convertibles are more likely to be red, we can structure our sample so that it ends up with the same proportion of convertibles. If 2% of cars are convertibles, we can sample convertibles until we have 2% of our sample consisting of convertibles. This is called **stratefying** a sample, which can help eliminate sources of sampling bias. Remember that stratification supplements but does not substitute for randomness - we still need to sample a random population of convertibles.

### Survey pitfalls

Voluntary surveys are prone to **participation biases** as even a random sample may not be representative of the population even if the initial selection was completely random.

People may even respond in a way that systematically skews the study - called a **response bias**. People may want to avoid answering in a way that is embarrassing or to avoid saying that they don't know.

## The big picture

We need to communicate our data effectively so we can understand the *general shape* of things. This calls for **summary statistics**.

- What are the most important features of the data?
- What is the clearest way to present those features?

These questions can be answered differently, so it can be easy to summarize data that is *technically correct* but misleading.

### Measures of centrality

We can get the **arithmetic mean** by dividing all the values by the number of values. We get the **median** by ranking the objects and taking the one halfway. And the **mode** is the value which shows up most often.

**Outliers** are data points that skew the man heavily. We can use the **truncated mean** to avoid this: this is just the mean of all values that are not outliers.

There is also another measure of centrality that takes into account the *proportion* at which values can be taken from data points called the **geometric mean**. We multiply the values and use the number of values as a root in this calculation.

### The shape of the data

We can quantify how far away each data point is from the overall mean using the **standard deviation**. This also refines the idea of an outlier: we can say that outliers are two or three standard deviations away form the mean.

### Misleading presentations

Sometimes data is presented in a way that presents facts that are *technically true* but presented in a misleading fashion.

A bar graph can be *truncated* - meaning some of its y-axis is cut away - so we can see the difference between each data points. This skews our perception of the data, since depending on where the creator truncates the graph, it can seem like some data points are *much bigger* than others! It's not always wrong to truncate an axis - if we were looking at small changes, then it would make sense. However, unlabeled axes or deliberately truncated graphs can be highly misleading. In the same vein, we can extend the y-axis more than necessary to show something as less extreme.

Most egregiously, news networks can cherry-pick data and use inconsistent scales on the x-axis to make downward trends look like upward trends and vice versa! This misleads millions of people while *technically* not lying.

## Thinking proportionally

We are constantly making generalizations that are often poorly supported or unclear.  We even have a hard time keeping track of the difference between *Most Fs are Gs* and *Most Gs are F*!

### Loose generalizations

Suppose we associate being American with being rude. But we aren't sure if a majority of Americans are rude or if a surprising number of them are rude, and so on. This is a **loose generalization** we can express by saying that "Americans are rude" or "Many Americans are rude"

We call loose generalizations about social groups **stereotypes**. Accuracy of stereotypes is a complex manner - it can be influenced by in-group bias, or even simultaneously convey *some* truths as well as *some* falsehoods.

"Americans are rude" is just too loose to nail down exactly what it means. Does it mean that a majority of Americans are rude or that a small percentage of Americans are rude?

Sometimes people slimply use this muddled language to express a muddled thinking. But some use it as a rhetorical trick to smuggle false beliefs for which they have no clear evidence into people's minds.

### Representativeness heuristic

The **representativeness heuristic** is an important pitfall discovered by cognitive scientists. Suppose we can ask these two different questions:

- What proportion of F things are G?
- What proportion of G things are F?

But we have the tendency to replace both questions with:

- How closely do I associate the two features?

We end up using a *symmetric* mental association to answer a non-symmetric question that has to do with proportions.

