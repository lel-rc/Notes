---
title: Deduction
categories: notetheme
tags: [notetheme, jekyll, theme]
maths: 1
comment: 1
---

### The limits of logical form

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

The premises doesn't acutally guarantee the conclusion. We may think they do due to biased evaluation. We accept the conclusion which makes us inclined find the whole argument good. (Think: does the fact that some healthy things are brightly coloured support the fact that *some blueberries* are healthy?)

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



