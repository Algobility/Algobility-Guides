# What is this

A github repository to allow collaborative work on the guides at [algobility.dev](https://www.algobility.dev/). To edit the guides, submit a pull request. The latest version of guides should get updated on the website within 24 hours.

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
Guides are written in markdown and so all markdown formatting rules apply.  For example, You can prefix a line with a hash symbol to denote a heading. Use these to seperate different parts of the guide. This text is currently under the 'Motivation Heading'.
For many guides 'Motivation' is the first heading. This is because giving the motivation for why an idea is needed is generally a good way to start a guide. Under this heading you can talk about an example of a problem where the naive solution would be too costly.

# This is another heading
This is some more text. Markdown also allows you to write words in bold by surrounding them with asteriks *like so*. To write some text in italics, surround the text with two asteriks **like so**.


## This is an example subheading
By prefixing a line with two hashes, you can denote a subheading (level 2 heading). You can technically go further with three hashes to denote a sub-sub heading however this is strongly discouraged for Algobility guides as it makes the guide look messy and level 3 headings have a small enough size that they look almost identical to normal text. 
To insert code blocks, enclose all code with three backticks like so:
\`\`\`cpp
int main(){
  cout << "this is an example of a code block";
}
\`\`\`

ALWAYS MAKE SURE THE OPENING THREE BACKTICKS ARE FOLLOWED WITH THE LANGUAGE CODE OF THE CODE BLOCK. Here are the options for language codes
- cpp for C++ code
- python for python
- text for any text that you want to keep in a code block but is not program code. A goood example of this is the input and output of a program. 


```
