# What is this

A github repository to allow collaborative work on the guides at [algobility.dev](https://www.algobility.dev/). To edit the guides, submit a pull request. The latest version of guides should get updated on the website within 24 hours.

# To-DO
The main task that we need to knock out before official launch is to 
a) Ensure all explanations are intuitive and easy to understand. If some wording seems ambiguous or generally not well-phrased, it needs to be edited.
b) Fill the guides with more exercises to strengthen conceptual understanding. Generally, the more exercises, the better
c) Fill the guides for ranks above silver/gold with more nuanced example problems. Most example problems given in the guides currently are, to some extent, trivial. Slightly harder problems and their solutions would help make these guides much more valuable.

# Formatting

Guides are written in markdown. The following section explains the format of an example Algobility guide on prefix sums and also covers the main things you need to know to write in markdown.  

```markdown
---
title: Prefix Sums
description: Efficiently find range sums
date: 'YYYY-MM-DD'
practicable: true
credits: John Doe
---


# Motivation
Guides are written in markdown and so all markdown formatting rules apply.
For example, You can prefix a line with a hash symbol to denote a heading.
Use these to seperate different parts of the guide. This text is currently
under the 'Motivation Heading'. For many guides 'Motivation' is the first
heading. This is because giving the motivation for why an idea is needed
is generally a good way to start a guide. Under this heading you can talk
about an example of a problem where the naive solution would be too costly.

# This is another heading
Markdown also allows you to write words in bold by
surrounding them with asteriks *like so*. To write some text in italics,
surround the text with two asteriks **like so**. Use italic text for quoting
problem statements, notes, etc. Optionally use bold text to emphasize ideas
and when introducing new terms. As a general rule of thumb, the less bold
words in a guide, the better. To insert in-line code, surround the text
with single backticks \`like so\`. Use this when refering to a small snippet
 of code (e.g. a function call, a condition, etc. )


## This is an example subheading
By prefixing a line with two hashes, you can denote a subheading (level 2
heading). You can technically go further with three hashes to denote a sub-sub
 heading however this is strongly discouraged for Algobility guides as it
makes the guide look messy and level 3 headings have a small enough size
that they look almost identical to normal text. 

# Code block
To insert code blocks, enclose all code with three backticks like so:
\`\`\`cpp
int main(){
  cout << "this is an example of a code block";
}
\`\`\`

ALWAYS MAKE SURE THE OPENING THREE BACKTICKS ARE FOLLOWED WITH THE LANGUAGE
CODE OF THE CODE BLOCK. Here are the options for language codes
- cpp for C++ code
- python for python
- java for java
- text for anything that you want to keep in a code block but is not program
code. A goood example of this is the input and output of a program or shell
prompts

If you do not write the language code next to the starting three back ticks,
the first line of the code block will be awkwardly indented.

# Exercises
It is generally good practice to include exercises (basically easy problems
for the topic at hand) to keep the guide interactive and strengthen conceputal
understanding.  You can include an exercise with the following syntax:

<Exercise number='1'>
<ExerciseQuestion>
This is the question statement of the exercise.  
</ExerciseQuestion>
<ExerciseAnswer>
And this is the answer. It will only be shown when the user clicks 'Reveal
Answer'. You can write in markdown in here as well. Often times the answer of
an exercise will include solution code which you can put with a code block.
</ExerciseAnswer>
</Exercise>

# Math
Math expressions can be written in-line like so <Math inline>2n + 1</Math> or
on a new line and centered like so
<Math block>n^2 + 2n + 3</Math>

Anything enclosed between math tags is rendered using mathJax. Check the mathjax
documentation to learn more about how to format mathematical expressions. All
mathematical variables should be enclosed in math tags (including common variables
in problems such as n, x, a, b,  etc.). Moreover time complexities in Big-O
notation should also be written in math tags (e.g. write  <Math inline>O(n^2)</Math> )

```
