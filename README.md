# Git Learning

The following are some text for test.

## Markdown for `README.md`

**Markdown** is a lightweight markup language, which is usually used to write documents. (And this document is written in Markdown, too!)

This is an incomplete guide for Markdown.

### Relationship between Markdown and HTML

Markdown is directly converted to HTML (HyperText Markup Language), and it is possible to insert HTML directly to Markdown documents. And Markdown works only in some ways as a subset of HTML. So HTML code insertion also helps to expand the functions of a Markdown document.

### Basic Syntax of Markdown

#### Headings

Add `#`s to mark a heading. The number of `#` (1-6) indicates the level of the heading.

``````markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
``````

The effects are as below:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

#### Format Applied to Sections of Text

Add `**`s to a section of text to make it **bold**.

Add `*`s to a section of text to make it *italic*.

``````markdown
**bold text** and *italic text*
``````

The effects are as below:

**bold text** and *italic text*

#### Quotes

Add a `>` to a paragraph to make it a quote.

``````markdown
> To be or not to be, that is a question.  
> *Hemlet*, Shakespeare
``````

The effects are as below:

> To be or not to be, that is a question.  
> *Hemlet*, Shakespeare

#### Sections and Blocks of Code

``````
`
``````

Add the character above to a section of text to make it a section of `code`.

``````markdown
`code`
``````

The effects are as below:

`code`

Use six characters of this in a line to mark a block of code. Use an (optional) word after the characters to specify the language of the section of code.

``````markdown
​``````markdown
# Git Learning
...
​``````
``````

The effects are as below:

``````markdown
# Git Learning
...
``````

#### Lists

In Markdown there are two types of lists: Ordered lists and unordered lists.

##### Unordered Lists

Put a symbol, which is usually `-`, before an item to make it an item in an unordered list.

``````markdown
- Item
  - Item
  - Item
- Item
  - Item
  - Item
- Item
``````

The effects are as below:

- Item
  - Item
  - Item
- Item
  - Item
  - Item
- Item

##### Ordered Lists

Put a number and a dot (`.`) before an item to make it a item in an ordered list.

**Note: The value of the number does not affect the value number before each item.**

``````markdown
1. Item 1
2. Item 2
   1. Item 1,1
   2. Item 1.2
3. Item 3



2. Item 1
0. Item 2
9. Item 3
``````

The effects are as below:

1. Item 1
2. Item 2
   1. Item 1.1
   2. Item 1.2
3. Item 3



1. Item 1
2. Item 2
3. Item 3

#### To be continued