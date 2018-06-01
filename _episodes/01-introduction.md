---
title: "Introduction to Markdown"
teaching: 30
exercises: 10
questions:
- "What is Markdown?"
- "How do I create a list?"
- "How do I insert a figure?"
objectives:
- "Know what Markdown is."
- "Know how to insert lists."
- "Know how to insert fiures."
keypoints:
- "Markdown is a markup language that can be converted to HTML."
- "You use `-` to start a list."
- "You use `![Legend](/fig/file.jpg)` to insert a figure."
---

Markdown is a markup language that got very popular in the web.
You can have lists in Markdown.

Lists starts after a empty line
with lines where the first character is `-`, `+` or `*`.
For example,
a list of fruits is

- apple
- banana
- oranges

You can use `+` for list and it does't matter for Jekyll.

+ apple
+ banana
+ oranges

You can have nested lists.
You must start the nested list on the same column as the item.
For example

- food
  - rice
  - beens
  - chicken
- drink
  - water
  - beer
  - wine
- dessert
  - chocolate
  
You can have multi line items.
For multi line items,
all lines must begin at the same column.

- Feedback 1

  CarpentryCon 2108 has been great soo far.
- Feedback 2

  Dinner was very nice but warm.
- Feedback 3

  Three days is not enough to meet everyone.

You can have numbered lists as well.
For numbered lists you start the line with a number followed by a dot.
For example,

1. Allies workshop
1. Library Carpentry workshop
1. Bring your lesson workshop

You can add emphasis on some words or expressions
by using `*` or `**` aroud the word or expression.
`*` makes the text to be in italic,
for example, *this is a italic text*,
and `**` makes the text to be in boldface,
for example, **this is a boldface text**.
For preformarted text, you use backtick.

If you want to use start as a star character
instead of a markup element you should use backslash
before the star,
for example, \*.

{% include links.md %}
