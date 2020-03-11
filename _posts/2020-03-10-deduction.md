---
title: Deduction
categories: notetheme
tags: [philosophy, critical-thinking]
maths: 1
comment: 1
---

# Chapter 4: Deduction

## Deductive validity

When the premises of an argument guarantee the conclusion. For example:

> Every seagull ever encountered by anyone has been white
>
> So the next seagull we see will be white

is not deductively valid. Why? While they can be inferentially strong, but the premises do not guarantee the truth of the conclusion. 

It needs to guarantee them without any additional information. 

This can be tricky. For example,

> Some monkeys are cute
>
> Only friendly animals are eating veggies
>
> No friendly animals are cute
>
> So some monkeys are not eating veggies

We can take the first and third lines and see they guarantee an interim conclusion: some monkeys are not friendly animals. We can consider it with the rest:

> Some monkeys are not friendly animals
>
> Only friendly animals are eating veggies

We can now see how the premises actually guarantee the conclusion.

### Flipping the argument

Going the normal way we consider if the conclusion can be true if the premises are true. But we can start with the conclusion first.

If we suppose the conclusion is false and the premises can be true, the argument isn't deductively valid. If they can't, it is.

## Logical form

We can check if an argument has a certain form to tell us if it is deductively valid or not. This won't work for *every* argument, though.

### Argument recipes

Some argument recipes are split by the **sentential connective** *if/then* to create a **conditional**. (A sentential connective combines two sentences to form a larger sentence.) The sentence following the *if* is the **antecedent** and the sentence following the *then* is the **consequent**.

For these arguments we can present them in **logical form**. We can substitute any sentence into the variables, creating an **instance** of the logical form.

If every instance of a logical form is deductively valid, it is a **valid form**.

#### Valid form: Modens ponens

> If P then Q
>
> P
>
> therefore Q

We can replace Q and P with any sentence we like and it would still be deductively valid. 

#### Valid form: Hypothetical syllogism

>  If P then Q
>
>  If Q then R
>
>  Therefore If P then R

We can see if P is true then we can conclude R is true using two applications of modus ponens. 

> If P then Q
>
> P 
>
> therefore Q
>
> If Q then R
>
> Q
>
> Therefore R
>
> Therefore P and R

Remember that the conditionals need to be *unqualified*: no "probably" or "almost certainly". They need to *guarantee* their outcomes.

#### Valid form: Modus tollens

> If P then Q
>
> Not Q
>
> Therefore not P

*Not* calls for the **negation** of a sentence. The negation of a sentence is true when the original sentence is false, and false when the original sentence is true.

Note that sometimes it's not that simple. "Some poppies are red" cannot be negated to "Not some poppies are red". We need to negate it to "No poppies are red". Modus tollens is calling for a way to negate P.

#### Valid form: Disjunctive syllogism

We've been looking at conditionals, now we can look at **disjunctions**. A disjunction of P and Q is true as long as either P or Q are true and false only when *both* of them are false. We can form this by using the words *either* or *or*.

> Either P or Q
>
> Not P
>
> Therefore Q

This also works if Q is false and the conclusion is P.

> Either P or Q
>
> Not Q
>
> Therefore P

When one component sentence is false, you can conclude the other is true.

#### Predicate forms

We don't need complete sentences in our variables. In fact, we could just have words. 

We can create structures by taking variables and replacing them with nouns, and *n* in place of proper names. Like:

> All F are G
>
> n is an F
>
> Therefore n is a G

Every argument in this form will be deductively valid.

We can change our sentences slightly to have the same meaning but so they fit the mold. For example:

> All dogs bark -> All dogs are barking things
>
> All dogs are happy -> All dogs are happy things

So that we get forms that can count as substitutions in our valid form. They are known as **predicates**. 

There are many valid predicate forms: it would be unreasonable to list them all. Instead, we just assess if the premises guarantee the conclusion.







The limits of logical form

Good news: valid forms can help us identify valid arguments!

Bad news: Not every deductively valid argument is in a valid form

> Bob was killed
>
> So, Bob died

This is deductively valid but not an instance of valid form. With valid forms, you'll never get a false positive, but you can miss some positives.

## Pitfalls in deduction

### Overlooking validity

Three reasons we can overlook valid arguments. First, we see the argument is not in a valid form and falsely assume it is not valid.

Second, the argument has false premises and so is not valid. Remember: an argument can be *deductively valid* but not *true*.

Third, some valid forms are easier to recognize than others. It is sometimes crucial to slow down.

### Biased Evaluation

Is the following an example of valid form?

> All blueberries are brightly coloured
>
> Some healthy things are brightly coloured 
>
> So, some blueberries are healthy

The premises doesn't actually guarantee the conclusion. We may think they do due to biased evaluation. We accept the conclusion which makes us inclined find the whole argument good. (Think: does the fact that some healthy things are brightly coloured support the fact that *some blueberries* are healthy?)

We can replace the words and it will be easier to see how this is invalid.

> All blueberries are brightly colored
>
> Some orange things are brightly colored
>
> So some blueberries are oranges

We can see this argument is *both* false and deductively invalid.

### Some invalid forms

Some logical forms can seem valid even when they are not. For example, **affirming the consequent.**

| Modus ponens | Affirming the consequent |
| :----------- | ------------------------ |
| If P then Q  | If P then Q              |
| P            | Q                        |
| therefore Q  | therefore P              |

Example:

> If this plant is a fern, it has spores
>
> It has spores.
>
> So this plant is a fern.

Another invalid form is **denying the antecedent**.

| Modus tollens | Denying the antecedent |
| ------------- | ---------------------- |
| If P then Q   | If P then Q            |
| Not Q         | Not P                  |
| Not P         | Not Q                  |

> If this plant is a fern, it has spores
>
> It's not a fern
>
> So, it doesn't have spores.



