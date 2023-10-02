# Check List to write an awesome tech documents

## Words

### Define new or unfamiliar terms

If your document is introducing the term, define the term. If your document is introducing many terms, collect the
definitions into a glossary.

### Use terms consistently

If you change the name of a variable midway through a method, your code won’t compile. Similarly, if you rename a
term in the middle of a document, your ideas won’t compile (in your users’ heads).

```
The moral: apply the same unambiguous word or term consistently throughout your document. 
Once you've named a component thingy, don't rename it thingamabob. 
For example, the following paragraph mistakenly renames Protocol Buffers to protobufs.
```

### Use acronyms properly

On the initial use of an unfamiliar acronym within a document or a section, spell out the full term, and then put
the acronym in parentheses. Put both the spelled-out version and the acronym in boldface.

```
If no cache entry exists, the Mixer calls the OttoGroup Server (OGS) to fetch Ottos for the request.
The OGS is a repository that holds all servable Ottos. 
The OGS is organized in a logical tree structure, with a root node and two levels of leaf nodes. 
The OGS root forwards the request to the leaves and collects the responses.
```

### Recognize ambiguous pronouns

* Only use a pronoun after you've introduced the noun; never use the pronoun before you've introduced the noun.
* Place the pronoun as close as possible to the referring noun. In general, if more than five words separate your noun
  from your pronoun, consider repeating the noun instead of using the pronoun.
* If you introduce a second noun between your noun and your pronoun, reuse your noun instead of using a pronoun. \

## Active voice vs. passive voice

Active voice provides the following advantages:

* Most readers mentally convert passive voice to active voice. Why subject your readers to extra processing time? By
  sticking to active voice, you enable readers to skip the preprocessor stage and go straight to compilation.
* Passive voice obfuscates your ideas, turning sentences on their head. Passive voice reports action indirectly.
* Some passive voice sentences omit an actor altogether, which forces the reader to guess the actor's identity.
* Active voice is generally shorter than passive voice. \

## Clear sentences

### Choose strong verbs

Example:

<table>
    <tr>
        <td>
            <strong>Weak Verb <em><a href="https://www.symbolcopy.com/cross-symbols.html">❌</a></em></strong>
        </td>
        <td>
            <strong>Strong Verb <em>✔ </em></strong>
        </td>
    </tr>
    <tr>
        <td>
            The exception occurs when dividing by zero.
        </td>
        <td>
            Dividing by zero raises the exception.
        </td>
    </tr>
    <tr>
        <td>
            This error message happens when...
        </td>
        <td>
            The system generates this error message when...
        </td>
    </tr>
    <tr>
        <td>
            We are very careful to ensure...
        </td>
        <td>
            We carefully ensure...
        </td>
    </tr>
</table>

### Reduce there is / there are

There is a variable called mettrick that stores the current
accuracy. ❌ \
A variable named mettrick stores the current accuracy. The mettrick variable stores the current accuracy. ✔

### Minimize certain adjectives and adverbs (optional)

❌ Setting this flag makes the application run screamingly fast. \
✔ Setting this flag makes the application run 225-250% faster.

## Short sentences

### Focus each sentence on a single idea

Focus each sentence on a single idea, thought, or concept. Just as statements in a program execute a single task,
sentences should execute a single idea. For example, the following very long sentence contains multiple thoughts:

<table>
    <tr>
        <td>
            <em><a href="https://www.symbolcopy.com/cross-symbols.html"> ❌</a> The late 1950s was a key era for programming languages because IBM introduced Fortran in 1957 and John McCarthy introduced Lisp the following year, which gave programmers both an iterative way of solving problems and a recursive way.</em>
        </td>
        <td>
            <em>✔ The late 1950s was a key era for programming languages. IBM introduced Fortran in 1957. John McCarthy invented Lisp the following year. Consequently, by the late 1950s, programmers could solve problems iteratively or recursively.</em>
        </td>
    </tr>
</table>

### Convert some long sentences to lists

When you see the conjunction or in a long sentence, consider refactoring that sentence into a bulleted list. When
you see an embedded list of items or tasks within a long sentence, consider refactoring that sentence into a bulleted
or numbered list.

### Eliminate or reduce extraneous words

❌ An input value greater than 100 causes the triggering of logging. \
✔ An input value greater than 100 triggers logging. \
❌ This design document provides a detailed description of Project
Frambus. \
✔ This design document describes Project Frambus.

### Reduce subordinate clauses (optional)

When editing, scrutinize subordinate clauses. Keep the one sentence = one idea, single-responsibility principle in
mind. Do the subordinate clauses in a sentence extend the single idea or do they branch off into a separate idea? If
the latter, consider dividing the offending subordinate clause(s) into separate sentences.

❌ “Bash is a modern shell scripting language that takes many of its
features from KornShell 88, which was developed at Bell Labs.”  \
The first subordinate clause extends the main idea, but the second subordinate clause goes in another direction. Divide
this sentence in two.

### Distinguish that from which

In the United States, reserve which for nonessential subordinate clauses, and use that for an essential subordinate
clause that the sentence can't live without. \
✔ Python is an interpreted language, which Guido van Rossum invented. \
✔ Fortran is perfect for mathematical calculations that don't involve linear algebra.

## Lists and tables

### Choose the correct type of list

Use a bulleted list for unordered items; use a numbered list for ordered items. \
An embedded list (sometimes called a run-in list) contains items stuffed within a sentence.

<table>
    <tr>
        <td>
            The llamacatcher API enables callers to create and query llamas, analyze alpacas, delete vicunas, and track dromedaries.
        </td>
        <td> The llamacatcher API enables callers to do the following:
        <ul>
            <li>Create and query llamas.</li>
            <li>Analyze alpacas.</li>
            <li>Delete vicunas.</li>
            <li>Track dromedaries.</li>
        </ul>
        </td>
    </tr>
</table>

### Keep list items parallel

Effective lists are parallel; defective lists tend to be nonparallel. All items in a parallel list look like they "
belong" together.

### Start numbered list items with imperative verbs

Consider starting all items in a numbered list with an imperative verb. An imperative verb is a command, such as open or
start. For example, notice how all of the items in the following parallel numbered list begin with an imperative verb:

<ol>
    <li>Download the Frambus app from Google Play or iTunes.</li>
    <li>Configure the Frambus app's settings.</li>
    <li>Start the Frambus app</li>
</ol>

### Punctuate items appropriately

If the list item is a sentence, use sentence capitalization and punctuation. Otherwise, do not use sentence
capitalization and punctuation. For example, the following list item is a sentence, so we capitalized the M in Most and
put a period at the end of the sentence:
> Most carambolas have five ridges. ✔

However, the following list item is not a sentence, so we left the t in the in lowercase and omitted a period: \
> the color of lemons ✔

### Create useful tables

Consider the following guidelines when creating tables:
<ul>
    <li>Label each column with a meaningful header. Don't make readers guess what each column holds.</li>
    <li>Avoid putting too much text into a table cell. If a table cell holds more than two sentences, ask yourself whether that information belongs in some other format.</li>
    <li>Although different columns can hold different types of data, strive for parallelism within individual columns. For instance, the cells within a particular table column should not be a mixture of numerical data and famous circus performers.</li>
</ul>

### Introduce each list and table

We recommend introducing each list and table with a sentence that tells readers what the list or table represents. In
other words, give the list or table context. Terminate the introductory sentence with a colon rather than a period.
For example, consider the following introductory sentences:

> The following list identifies key performance parameters:

> Take the following steps to install the Frambus package:

> The following table summarizes our product's features against our key competitors' features:

## Paragraphs

### Write a great opening sentence

Good opening sentences establish the paragraph's central point.

### Focus each paragraph on a single topic

A paragraph should represent an independent unit of logic. Restrict each paragraph to the current topic. Don't describe
what will happen in a future topic or what happened in a past topic. When revising, ruthlessly delete (or move to
another paragraph) any sentence that doesn't directly relate to the current topic.

> The Pythagorean Theorem states that the sum of the squares of both legs of a right triangle is equal to the square of
> the hypotenuse. ~~The perimeter of a triangle is equal to the sum of the three sides.~~ You can use the Pythagorean
> Theorem to measure diagonal distances. For example, if you know the length and width of a ping-pong table, you can use
> the Pythagorean Theorem to determine the diagonal distance. ~~To calculate the perimeter of the ping-pong table, sum
the
length and the width, and then multiply that sum by 2.~~

### Don't make paragraphs too long or too short

Readers generally welcome paragraphs containing three to five sentences, but will avoid paragraphs containing more than
about seven sentences.

### Answer what, why, and how

Good paragraphs answer the following three questions:
<ul>
<li>What are you trying to tell your reader?</li>
<li>Why is it important for the reader to know this?</li>
<li>How should the reader use this knowledge? Alternatively, how should the reader know your point to be true?</li></ul>

## Audience

> good documentation = knowledge and skills your audience needs to do a task − your audience's current knowledge and
> skills

<ol>
<li>Define your audience.</li>
<li>Determine what your audience needs to learn.</li>
<li>Fit documentation to your audience.</li>
</ol>

### Define your audience

The target audience for Project Zylmon falls into the following roles:

> software engineers \
> technical product managers

The target audience has the following proximity to the knowledge:

> My target audience already knows the Zyljeune APIs, which are somewhat similar to the Zylmon APIs. \
> My target audience knows C++, but has not typically built C++ programs in the new Winged Victory development
> environment. \
> My target audience took linear algebra in university, but many members of the team need a refresher on matrix
> multiplication.

### Determine what your audience needs to learn
Example1: \
After reading the documentation, the audience will know how to do the following tasks:
<ul>
<li>Use the Zylmon API to list hotels by price.</li>
<li>Use the Zylmon API to list hotels by location.</li>
<li>Use the Zylmon API to list hotels by user ratings.</li>
</ul>

Example2: \
After reading the design spec, the audience will learn the following:
<ul>
<li>Three reasons why Zylmon outperforms Zyljeune.</li>
<li>Five reasons why Zylmon consumed 5.25 engineering years to develop.</li>
</ul>

### Fit documentation to your audience
- [X] Vocabulary and concepts
- [X] Curse of knowledge
- [X] Simple words
- [X] Cultural neutrality and idioms

## Documents
### State your document's scope
A good document begins by defining its scope. For example:

>This document describes the design of Project Frambus.

A better document additionally defines its non-scope.
>This document does not describe the design for the related technology, Project Froobus.

### State your audience
A good document explicitly specifies its audience. For example:
> This document is aimed at the following audiences: <ul><li>software engineers</li> <li>program managers</li></ul>

### Summarize key points at the start
Engineers and scientists are busy people who won't necessarily read all 76 pages of your design document. Imagine that your peers might only read the first paragraph of your document. Therefore, ensure that the start of your document answers your readers' essential questions.

### Compare and contrast
Compare and contrast your ideas with concepts that your audience already understands. For example:
>This new app is similar to the Frambus app, except with much better graphics.

> The Froobus API handles the same use cases as the Frambus API, except that the Froobus API is much easier to use.

### Write for your audience
Define your audience's needs
Answering the following questions helps you determine what your document should contain:
```
Who is your target audience?
What is your target audience's goal? Why are they reading this document? 
What do your readers already know before they read your document? 
What should your readers know or be able to do after they read your document?
``` 

## Punctuation
### Commas
As a guideline, insert a comma wherever a reader would naturally pause somewhere within a sentence.

>C behaves as a mid-level language, just a couple of steps up in abstraction from assembly language.

### Semicolons
A period separates distinct thoughts; a semicolon unites highly related thoughts. For example, notice how the semicolon in the following sentence unites the first and second thoughts:

> Rerun Frambus after updating your configuration file; don't rerun Frambus after updating existing source code.

Before using a semicolon, ask yourself whether the sentence would still make sense if you flipped the thoughts to opposite sides of the semicolon. For example, reversing the earlier example still yields a valid sentence:

>Don't rerun Frambus after updating existing source code; rerun Frambus after updating your configuration file.

### Parentheses
Use parentheses to hold minor points and digressions.
For example:
```
(Incidentally, Protocol Buffers make great birthday gifts.)
Binary mode relies on the more compact native form (described later in this document).
```


### Summary
<ol>
<li>Use terms consistently.</li>
<li>Avoid ambiguous pronouns.</li>
<li>Prefer active voice to passive voice.</li>
<li>Pick specific verbs over vague ones.</li>
<li>Focus each sentence on a single idea.</li>
<li>Convert some long sentences to lists.</li>
<li>Eliminate unneeded words.</li>
<li>Use a numbered list when ordering is important and a bulleted list when ordering is irrelevant.</li>
<li>Keep list items parallel.</li>
<li>Start numbered list items with imperative words.</li>
<li>Introduce lists and tables appropriately.</li>
<li>Create great opening sentences that establish a paragraph's central point.</li>
<li>Focus each paragraph on a single topic.</li>
<li>Determine what your audience needs to learn.</li>
<li>Fit documentation to your audience.</li>
<li>Establish your document's key points at the start of the document.</li>
</ol>