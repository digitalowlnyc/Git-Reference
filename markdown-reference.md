Links: 

1. [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
    * [Code: supported languages](https://highlightjs.org/static/demo).

# Lists

1. Remember spacing before the list!
* I was created with an asterisk, not a number
3. Unordered sublist coming up
    * A sub list: use four indents and then asterisk
3. Ordered sublist coming up
    1. A sub list: use four indents and then a number, it becomes "i"
    2. Should be two i's here

# Escaping
- Markdown: Wrap text in html, from beginning of line "&lt;div&gt;Some text&lt;/div&gt;"
- HTML tags: You can use `&lt;div&gt;`... note it was used in the line above to escape the div tags, very meta!

# Code

### Template: 
<pre>``` javascript
code goes here
```
</pre>

### Example: block (wrap in three backticks)
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

### Example: inline (wrap in one backtick)
`php echo('hello world')`

# Styling

### Headings 1-6
<div>use '### heading' for h3, etc</div> 
# H1
## H2
### H3
#### H4
##### H5
###### H6
