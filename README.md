# Markdown
Markdown is the styling language used by GitHub, Discord, and Slack to style the content of a post, such as this one
### Headers
Headers are easy. Use between one and six pound (#) symbols to create a header. One # is the same as h1, except in markdown you dont need to close an element
# # h1
## ## h2
### ### h3
#### #### h4 etc,.
## Markdown Text Styles
* italics, *italics* or _italics_
* bold, **bold**
* bold italics, ***bold italics***
* underline, __underline__
* underline italics, __*underline italics*__
* underline bold, __*underline bold*__
* underline bold italics, ___***underline bold italics***___
* strikethrough, ~~strikethrough~~
### Lists
Lists are pretty straight-forward. You can simply number your list with 1
1. Hello
You can dot it, using * instead of 1.
* World
And you can dot sub-lists as well, by using -
- Hello World
### Code Blocks
Inline code blocks can be created by wrapping your line of text in backticks (`)
You can also make multiline code blocks using 3 back ticks (```)
<html>
  <head>
    <title>Jinkies!</title>
  </head>
  <body>\
  </body>
</html>

#### Syntax Highlighting
Now the fun stuff. Just like in GitHub, all you do is tag the language onto the end of your opening backticks, like this:
```html
[content]
```
Here's a live example:
const helloWorld = 'Hello World!'
console.log(helloWorld)

### Links
The syntax for writing a link in markdown is [name](address). The name can be whatever you want, really
[Google](https://www.google.com/)
[Google](https://www.google.com/)
### Quotes
You can create a quote using >.
>Hello World!

You can also create block quotes by stacking > and formatting manually as needed

>Hello all!
>Thanks for checking out my post!

>Hello all!
>Thanks for checking out my post!

You can also nest a quote within a quote.
>Hello
>>World

>Hello
>>World
