# Dave Farley - Software engineering in an AI world

[Synopsis](https://leanagile.scot/programme/software-engineering-ai-world)

## Context

It's all about flow (still).

Iteratively identify and reduce the constraints on getting value into the hands of users. This requires systemic thinking.

AI specs is likely to be the 5th evolution of abstracting our use of programming languages to deliver value. Programming Languages have three goals:

1. Help us organise our thinking about a problem.
2. Communicate understanding to other humans.
3. Tell a compute what to do.

They achieve this via three techniques:

1. Simple, consistent "formal" grammar
2. Unambiguous expression of intent
3. Repeatable, deterministic execution

## The problems with AI

1. How do we specify something with precision - AI is not precision.
2. How do we confirm we've achieved our goal?
3. How can we work to build our learning _incrementally_?

Solving these, particularly 2 & 3, are critical to incremental software development.

## Solutions

Specify the constraints and target really well - encode this as specifications. This can be translated into executable code by the AI.

This still requires engineering thinking. Programming becomes:

1. Designing DSLs and then using them to specify (feature by feature, BDD style) precisely what we want to achieve.
2. Have AI use the specification to implement and verify it has met our goal (using tests it generates).
3. With these in place, we can still apply an incremental approach to development, along with:
   1. Version control of specifications.
   2. Run the tests yourself, not by the AI.
   3. Stop the AI gaming the tests.

BDD and Evolutionary architecture are existing foundations that enable the above.

## Constraints humans still need to solve

1. Understanding the problem.
2. Business context.
3. Product ideas.
4. Architectural context.
5. Verifying the solution.
6. Making the solution maintainable at an affordable cost.

## Things to try

1. Use BDD when I specify to an AI the outcome I want.
2. Work incrementally with AI.
