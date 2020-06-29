# uncle_bob_clean_coding_lessons

## Lesson 3 https://youtu.be/Qjywrq2gM8o

Expectations:

What we might profess in our profession as developers.

I Expect...

1. We will not ship shit. (Everything works)
> All users expect a working product, with very few issues. Even yourself! Deliver.

2. We will always be ready. (Always ready to deploy)
> Interation lengths for the Mercury space capsule was 1 day. Write unit tests in the morning and pass in the afternoon.

> We are satisfied today with 1 week or 2 weeks

> We should be READY to deploy in that interation, it may not have enough features to deploy but technically should be ready.

> Docs done, tests done.

> At the end of a iteration, you should have shippable code. If you do not have something ready to deploy you are not doing Agile.

> Burn in periods are false hopes. You should have the tests to prove your system is working and be shippable.

3. Stable Productivity

> The longer the project goes, the slower you DON'T get.

> Features are produced at the same rate at the beginning, middle, and end.

> Example: minimal estimate was 6 months for everything, because the cost of missing an estimate was so high (professionally and personally all items were overly estimated).

4. Inexpesive adaptability

> Cheap and easy to make changes to the system.

> The cost of the change should be proportional to size of the request.

> Software is a compound word meaning 'changeable product'; We want to change our machines and developed software.

> If your software is so hard to change, then you have created hardware and your architecture sucks.

> Software should be changeable.

> Clean code and tests.

5. Continous Improvement

> Of the system, of the code

> Code should improve over time.

> Humans improve situations with time.

> The expectation of the entire world

6. Fearless Competence

> minimalizing your personal risk will cause system rot.

> Why are you afraid to touch the code?

> If it ain't broke, don't fix it.

> You get fearless competence with tests (the green light, that tells you the system works, and you believe it)

> Check the code in a little bit better than you did before, the boy scout rule.

> Write unit tests for code you have written first.

> Code Coverage is NOT a management metric; it is a team isolated metric.

7. Extreme quality

8. We will not dump on QA

> we do not use QA to find bugs in our systems.

9. QA will find nothing

> Why would we invest in a QA that expects the developers did their jobs?

> Developers need to do their jobs.

> QA should be done at the beginning and specifies how the system runs.

10. Nothing Fragile

11. We cover for each other

12. Honest estimates

> The most honest estimate is "I don't know"

> PERT (Project Evalution in Real-time); Estimate given in 3 numbers (best case, average case, worst case)

> No manager wants to hear 3 numbers, Managers will have to manage that type of risk. Do not absorb the risk if you don't know you can make it.

13. You to say, No.

## Lesson 4: Test Driven Development https://youtu.be/58jGpV2Cg50?list=PL1Rabu4aHyrygl3J4XUJbQMjgYoBagBeV&t=1331

Discipline of TDD:

1st Law of TDD:

> You are not allowed to write any production code, until you write a test that fails, because the production code does not exist.

2nd Law of TDD:

> You are not allowed to write more of a test that is sufficient to fail. (stop writing when it does not compile)

3rd Law of TDD:

> You are not allowed to write anymore production code than will pass the failing test.

This creates a loop.
