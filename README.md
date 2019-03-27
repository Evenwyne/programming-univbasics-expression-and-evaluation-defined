# Title

## Learning Goals

* Define Expression
* Identify the Parts of an Expression
* Define Evaluation

## Introduction

So now we've seen that we can have a conversation with Ruby by using the IRB
program. Conversations, we've seen are the things that result when two
individuals &mdash; be they human or machine &mdash; communicate expressions to
one another.

We've been imprecise in defining "expression" while we were getting the hang
of it. Let's propose formal definitions for _expression_ and _evaluation_.

## Define Expression

From Wikipedia, with minor revision for simplicity:

> An expression in a programming language is a combination of one or more
> constants, variables, operators, ... that the programming language
> interprets (according to its particular rules of precedence and of association)
> and computes to produce ("to return", in a stateful environment) another value.
> This process, as for mathematical expressions, is called evaluation.

That's pretty good! That should align with you experience of having a
conversation with IRB from the previous lesson. Think about `255 / 5` which
elements of it are _constants_, _variables_, or _operators_? Let's look
together.

## Identify the Parts of an Expression

Given:

`255 / 5`

There are three things that our definition thinks exists: constants, variables,
and operators. So, which of these 3 things are the following elements?

1. `255`
2. `/`
3. `5`

Think it through for a second.

Here's a deep question: "Is `255` ever _not_ `255`?" Is it ever something else?
If it were a bit greater it'd be `255.0000001` and it it were much greater it'd
be `256`. Same is true for less. The value `255` must always be `255`. It,
therefore must be a _constant_.

The same reasoning is true for `5` so, clearly `5` is a _constant_ as well.

> **WARNING**: If you've written code before you might be thinking about a
> thing that language might have had called a "constant." That's a similar
> concept, but slightly different. _Those_ "constants" are more precisely
> called "symbolic constants." Those "symbolic constants" are like _variables_,
> the last "thing" in an expression. We'll discuss _variables_ in a few
> lessons.

What about `/`? It just so happens that `/` is an easier way of typing `÷`.
That symbol means an "operation." Symbols that refer to a little unit of work
("opera" comes from the Latin word for "work") are called _operators_. In this
case `/` is the _operator_ that means "division."

So, this _expression_ will _evaluate_ to `51`, when "spoken" to Ruby in IRB.
As we see in IRB, Ruby's "return value" to this expression is `51`.

The numbers `255` and `5` are bits of data. We'd call them "constants"

## Define Evaluation

In case you missed it earlier, evaluation is the process of interpreting an
expression, according to rules, to produce a return value.

## Conclusion

## Resources
