---
title: Editing Basics
layout: default
parent: Editing Wikipedia
nav_order: 2
---
# Editing Basis

Wikipedia uses a simple markup language called “Wikitext” to format content. You can practice using this markkup language in your user sandbox.

The Wikipedia editing interface also provides some visual editing tools, but taking the time to learn the basics of wikitext will make editing easier for you in the long run.

Wikipedia has a [very useful cheatsheet](https://en.wikipedia.org/wiki/Help:Cheatsheet) that shows you how to do things like format text as bold or italic, link to another Wikipedia page, and link to a website outside Wikipedia.

Below are some wikitext conventions you're likely to use often.

| Wikitext | Result |
| -------- | ------ |
| `''Two single quotes on either side.''` | *Two single quotes on either side.*  (Italic text.)|
|`'''Three single quotes on either side.'''` | **Three single quotes on either side.** (Bold text.)|
| `'''''Five single quotes on either side.'''''` | ***Five single quotes on either side.*** (Italic bold text.)|
|`[[ October 10 ]]` | [October 10](https://en.wikipedia.org/wiki/October_10) (Link to the Wikipedia article named "October 10".) |
| `[[ October 10 | October 10 article ]]` | [October 10 article](https://en.wikipedia.org/wiki/October_10) (Link to the Wikipedia article named "October 10", but make the linked text read, "October 10 article".) |
| `[https://example.com Example website]` | [Example website](https://example.com) (Link to the website `example.com`, but make the linked text read, "Example website").|
| `[[ Not A Page Yet ]]` | <span style="color:red">Not a Page Yet</span> (Link to a Wikipedia article that doesn't yet exist, named "Not A Page Yet". If you create this link on a page and save the page, you can then follow the link to create the new page, "Not A Page Yet". On the cheat sheet, Wikipedia calls this a "red link".) |

## A few other conventions

### Headings

You can add subsections to Wikipedia pages with headings, beginning with a level-two heading. The number of "equals" signs (`=`) on either side of the heading determines the heading level. Thus, to add a level-two heading, you would type,

```
== Name of heading ==
```

You would add a level-three heading by typing,

```
=== Name of heading ===
```

### Bulleted lists

Typing

```
* Cats  
* Dogs  
* Ferrets
```

will result in 

- Cats
- Dogs
- Ferrets

### Numbered lists

Typing

```
# One  
# Two  
# Three
```

will result in

1. One
2. Two
3. Three