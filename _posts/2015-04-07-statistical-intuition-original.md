---
title: Statistical intuition
isOriginal: true
tags: [statistics, A/B testing, statistical intuition]
---

# Statistical intuition

Statistical phenomena are notoriously difficult to get a good grasp of intuitively. Most people don't have the ability to evaluate risks given in percent, nor given as probabilities. I myself am quite aware of the intricacies and pitfalls involved in comparing probabilities, having always been fascinated by probabilities, so I'll quickly resort to a calculator or pen and paper when comparing probabilities.

What I *can't* deal with satisfactionally, even though I've taken a university course in statistics, is statistical testing. I would like to be able to create an A/B testing calculator (such as [ABBA]), and I'd *certainly* like to immediately know under what conditions it's safe to use:

* Can I continuously check results? (and upon "95% confidence" of the result, stop the test)
* How tightly coupled with the number of conversions?
* What are the pitfalls when testing multiple versions at the same time?
* Is it possible to make small changes to the library to support multivariate testing? (i.e. testing multiple factors simultaneously)

And that's just the beginning. When should I use a [student's *t*-test]? What is [regression analysis] used for? How do I calculate confidence intervals? Which distributions should I use in which situations? Are any statistics "easy" to calculate (can I write a program to do it somewhat efficiently), or will I need dedicated programming libraries for that? Which libraries and tools should I use for my programming and everyday needs?

To me, statistical intuition means knowing what techniques to use in what situations, not only having a correct hunch about what probabilities mean. If I ever take another course in statistics, my goal will be to confidently be able to respond to all of the above questions, and also others that I'm not yet knowledgeable enough to know to ask.



[ABBA]: http://www.thumbtack.com/labs/abba/
[student's *t*-test]: https://en.wikipedia.org/wiki/Student%27s_t-test
[regression analysis]: https://en.wikipedia.org/wiki/Regression_analysis
