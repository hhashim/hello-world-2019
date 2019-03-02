# Markdown test fie

## 1. I'm going to test **HEADING**

# This is Heading No 1
## This is Heading No 2
### This is Heading No 3
#### This is Heading No 4
##### This is Heading No 5
###### This is Heading No 6

## 2. **Styling Text**

This is testing **Bold** *Italic* ~~Strikethrough~~ and **Bold sentence with __italic__ text**

## 3. Quoting Text
I can call out code or a command within a sentence with **single backticks**. The text within the backticks will not be formatted.

I will call out this code: `test command`

To format code ot text within its own distict block, use triple backticks.

Some basic **Git** commands are:
```
git status
git add
git commit
```
## 3.1 Creating and highlighting code blocks
**Share samples of code with fenced code blocks and enable syntax highlighting**
### Fenced code blocks ###
Create it by placing triple backticks `\```\` before and after the code block.

```
function test(){
  console.log("notice the blank line before this function")
 }
 ```
 **Tip:** To preserve your formatting within a list, make sure to indent non-fenced code blocks by eight spaces.
 ### Syntax highlighting
 You can add an optional language identifier to enable syntax highlighting in your fenced code block.
 For example, to syntax highlight *Ruby* code:
 
 ```ruby
 require 'redcarpet'
 markdown = Redcarpet.new("Hello World!")
 puts markdown.to_html
 ```
 ## 4. Links
 
