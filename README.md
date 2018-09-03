# markdown

What is Markdown?

Markdown is a way to style text on the web. 
It uses # or *

File names with .md or .markdown extention

**bold** it will be bold
*italic* it will be italic

List
1. One
2. Two
3. Three

Sometimes you want bullet points
* start a line with a star // it will show bullet point

Alternatievely - dashes work just as well
- it will indent one tab
  - it will indent two tab
  
Images - If you want to embed images, this is how you do it
![Image of Yaktocat] //image name
(https://octodex.github.com/images/yaktocat.png) //address is needed

Headers & Quotes
```
# Structured Documents

By using number of #, it changes the size of the font
#Structured Documents
### This is a third-tier heading
###### This is the minimum

```
# Structured Documents
### This is a third-tier heading
###### This is the minimum

Code
```
Github allows code to be inline code blocks.
One is the indent with four spaces:
    if (isAwesome) {
      return true
     }
     
The other way is use of " ``` "
If we start  and close with " ``` " it will do the same thing
```

```javascript
if (isAwesome){
  return true
}
```
Tables can be use with  - and |:
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

would become: 

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

SHA reference
it will auto convert into link to that commit on github

Issue reference within a repository
any number that refers to an issue or pull request will be automatically converted
into a link

```
#1
mojombo#1
mojombo/github-flavored-markdown#1
```

*Username @mentions*

Typying @ symbol, follow by a username, will notify that person to come and view that comment.

*Automatic linking for URLs"
any URL (like http://www.github.com/) will be automatically converted into a clickable link

*Strikethrough*

Any word wrapped with two tildes (like ```~~this~~```~~this~~) will appear crossed out.


Emoji
Github supports emoji!!!




