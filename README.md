# markdown
Markdown syntax manual for GitHub

*****************************************
# 0. Two spaces at the end of a line create a line break
this  
is  
a  
line  
break

*****************************************
# 1. Headings & Emphasis

## 1-1. Headings
```
# this is h1
## this is h2
### this is h3
#### this is h4
##### this is h5
###### this is h6
```
# this is h1
## this is h2
### this is h3
#### this is h4
##### this is h5
###### this is h6

## 1-2. Emphasis
```
Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~
```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

*****************************************
# 2. Horizontal Lines
```
***
```
***

```
---
```
---

```
___  
```
___
  
*****************************************
# 3. Code
## 3-1. Code & Code block
~~~
`This is code`
~~~
`This is code`
```
~~~  
This is a piece of code  
in a block  
~~~
```
~~~
This is a piece of code
in a block
~~~
~~~
```  
This too  
```
~~~
```
This too
```
## 3-2. Syntax Highlighting
~~~
```css
/* CSS syntax highlighting */
#button {
  border: none; 
}
```
~~~
```css
/* CSS syntax highlighting */
#button {
  border: none;
}
```

~~~
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
~~~
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

~~~
```python
s = "Python syntax highlighting"
print s
```
~~~
```python
s = "Python syntax highlighting"
print s
```

*****************************************
# 4. List
**Use 2 tabs or 3 spaces for sublist**

## 4-1. Bullet List
```
* item
  * item
    * item
+ item
  + item
    + item
- item
  - item
    - item
* item
  - item
    + item
```
* item
  * item
    * item

## 4-2. Numbered List
```
1. item
2. item
   1. item
   2. item
3. item
   1. item
      1. item
```
1. item
2. item
   1. item
   2. item
3. item
   1. item
      1. item


## 4-3. Mixed List
```
1. item
    1. item
        - item
* item
    - item
        1. item
```
1. item
    1. item
        - item
* item
    - item
        1. item
        
*****************************************
# 5. BlockQuote
```
> Quoted text
>> Quoted quote
> * Quoted
> * List
```
> Quoted text
>> Quoted quote (Nested BlockQuote)
> * Quoted
> * List


