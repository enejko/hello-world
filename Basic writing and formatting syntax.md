# The largest heading
## The second largest heading
###### THe smallest heading
**This is bold text**
*This text is italicized*
_italicized too_
~~This was mistaken text(strikethrough)~~
**This text is _extremely_ important**

>Pardon my French (quoting text)

Quoting code -- using single backticks (will not be formatted)

Use `git status` to list to list all new or modified files that haven't yet been committed.


format code into its own distinct block (triple backticks):
```
git status
git add
git commit
```
```golang
import (
    "time"
    "net/http"
    )
main(){
 http.ListenAndServe("localhost:8080), nil);
 }
 ```

[link text in brackets](https://somewhere.com/URL%20in%20parentheses)

[link to section in rendered file](#The-second-largest-heading)
[relative link to Readme](readme.md)

 Unordered list -- preceding by - or * 
 - George WEasshington
 - John Adams
 - Thomas Jefferson
 * with asterix1
 * With asterixs2
 to order your list - precede with a number + dot:
 1. James Madison
 2. James Monroe
 3. John Quincy Adams
 
 Nested lists  by indenting one or more list items below another item
 1. First
    - First nested
      - Second nested  list item

1. First
   1. Sec
      1. Third
- 1
  - 2 
    - 3
       - 4
         - 5
Hi

task list -- preface list items with regular space character followed by [ ]. To mark a task as complete, use [x]
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull reues
h
If a task list item description begins with a parenthesis, you'll needto escap it with \:
- [ ] \(optional) Open a followup issueh  
h
Mentioning people and teams -- by typing @ plus their username or team name. 
This will trigger a notification and bring their attention to the conversation
@github/support What do you think about these updates?

Referencing issues and pull reuest --  by typing #  Type issue or PR number or title to filter the list (then `tab`)
#1

Using emoji --- by typing :EMOJICODE: TYping  : will bring up  alist of suggested emoji (**Tab** or **Enter** to complete)
:+1:

Paragraphs and line breaks -- by leaving a blank line between lines of text.

Ignoring Markdown formatting -- to ignore( or escape) Markdown -- by using \
Let's rename \*our-new-project\* to \*our-old-project\*.

