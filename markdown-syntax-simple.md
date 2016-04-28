## Markdown - basic syntax
(In this document I use the following format: heading \> Markdown syntax \> how this is then rendered)

---

#### Headings
```
# heading 1 (largest)
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6 (smallest)
```
# heading 1 (largest)
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6 (smallest)

---

#### Paragraphs / line breaks
```
Paragraphs are separated by a blank line.

Like this.

Two spaces at the end of a line - like here:  
result in a line break.
```
Paragraphs are separated by a blank line.

Like this.

Two spaces at the end of a line - like here:  
result in a line break.

---

#### Text attributes
```
_italic_ (or *italic*)  
**bold** (or __bold__)  
`monospace`  
~~strikethrough~~
```
_italic_ (or *italic*)  
**bold** (or __bold__)  
`monospace`  
~~strikethrough~~

---

#### Bullet list
You can use dashes or asterisks. 
```
  - apples 
  - oranges
  - pears
  * bananas
  * plums
  * grapes
```
  - apples 
  - oranges
  - pears
  * bananas
  * plums
  * grapes

---

#### Numbered list
```
  1. get up
  2. get dressed
  3. brush teeth
```
  1. get up
  2. get dressed
  3. brush teeth

Any list can also contain sub-levels. For example:
```
  1. First ordered list item
  2. Another item
    * Unordered sub-list
  3. And another item
    1. Ordered sub-list
  15. And another item
```
  1. First ordered list item
  2. Another item
    * Unordered sub-list
  3. And another item
    1. Ordered sub-list
  15. And another item

(Note that in the syntax you don't even have to use the "correct" numbers - any number will do.)

---

#### Links
```
Here is a [link](http://bbc.co.uk/news) to the BBC News web site.
```
Here is a [link](http://bbc.co.uk/news) to the BBC News web site.

For relative links (i.e. to other files in your GitHub repo) you can use the following shorthand:
Instead of using the standard absolute link syntax, for example:
```
[a link](https://github.com/user/repo/blob/branch/other_file.md)
```
you can use the following relative link syntax:
```
[a link](other_file.md)
```
and GitHub will ensure the link resolves to `user/repo/blob/branch/other_file.md`.

---

#### Code blocks
```
Surround the contents of the code block with 3 back ticks (i.e. 3x` at the beginning and end)
to create a code block
Blah, blah, blah
etc.
```

---

#### Code phrase
```
Surround the code phrase in back ticks (e.g. `i_love_cake`)
```
Enter `i_love_cake` into the command line. 

---

#### Comments
You can add comments to the source by surrounding the comment text with a `<!--` and a `-->` (just like in HTML).

---

#### Escape character
You can tell GitHub to ignore (or escape) Markdown formatting by using `\` before the Markdown character.
