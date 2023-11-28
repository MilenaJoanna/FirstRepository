- <!-- omit in toc --> [My first repository about Markdown](#my-first-repository-about-markdown)
  - [Types of headings](#types-of-headings)
- [heading level 1](#heading-level-1)
  - [heading level 2](#heading-level-2)
    - [heading level 3](#heading-level-3)
      - [heading level 4](#heading-level-4)
        - [heading level 5](#heading-level-5)
          - [heading level 6](#heading-level-6)
  - [Paragraphs](#paragraphs)
  - [Line break](#line-break)
  - [Emphasis](#emphasis)
  - [Blockquote](#blockquote)
  - [Ordered list](#ordered-list)
  - [Unordered list](#unordered-list)
  - [Code](#code)
  - [Link](#link)
  - [Image](#image)
  - [Table](#table)

# My first repository about Markdown

## Types of headings
In Markdown we have 6 levels of headings:
# heading level 1
## heading level 2
### heading level 3
#### heading level 4
##### heading level 5
###### heading level 6

## Paragraphs
I really like using Markdown.

I will use it to format all my documents.

## Line break

This is the first line.  
This is the second line.

## Emphasis

**This is a bold text.**

*This is an italicized text*

## Blockquote

> This is a blockquote.

## Ordered list

This is an ordered list:
1. one 
2. two
3. three
4. four

## Unordered list

This is an unordered list:
- one 
- two
- three
- four

## Code

This is a fragment of a code:

`entity a is
  port (
    a1 : in std_logic;
    a2 : in std_logic;
    a3 : out std_logic
  );
end entity;`

## Fragment of a code within a paragraph

To create paragraphs in Markdown, use one or more lines of consecutive text followed by one or more blank lines.
 
 This is a fragment of a code:

`from random import randint
ile = int(input("Ile liczb wylosować? "))
lista = []  # pusta lista
for i in range(0, ile):
    lista.append(randint(0, 100))
print(lista) `

 Note: If you don't leave a blank line between blocks of text, they will be collapsed into a single paragraph.

## Link

This is a link: [Prognoza pogody](https://www.meteo.pl)


## Image

This is an image of a dolphin:

![delfin](delfin.png)

## Table

This is a table:

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |




