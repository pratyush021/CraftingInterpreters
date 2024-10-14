# CraftingInterpreters
Writing an interpreter in java! 

these notes are from the book <b>crafting interpreters by Robert Nystrom </b>


## Scanner 
A Scanner takes the linear stream of characters and turns them into words called tokens. 
e.g. <br>
<b>input: </b>
```javascript
var average = (min + max) / 2;
```
 <br>
<b>output: </b>

```javascript 
scanner_response = ["var", "average", "=", "(", "min", "+", "max", ")", "/", "2", ";"]
```

## Parsing 
1. The Parser takes the sequence of tokens and builds a tree i.e. Syntax Tree. 
2. Parser reports Syntax error made by the programmer. 



