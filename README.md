# CSS : 

***CSS Selectors*** : 

- Universal Selector : 
```css
* {
    margin: 0;
    padding: 0;
}
```
- Element Type Selectors : 
```css
p {
    color: blue;
}
```
- id Type Selectors : 
```css
#Test {
    color: red;
}
```
- Class Type Selectors : 
```css
.blue {
    color: blue;
}
```

***CSS BackGround*** : 
- BackGround Color : 
```css
body {
    background-color: #f0e68c;
}
```

- BackGround image : 
```css
body {
    background-image: url("something/smth.png");
}
```

- BackGround Reapeat : 
```css
body {
    background-image: url("images/texture.png");
    background-repeat: no-repeat;
}
```
> background-repeat : no-repeat / repeat
> background-repeat : repeat-x / repeat-y


- BackGround Position : 
```css
body {
    background-image: url("images/robot.png");
    background-repeat: no-repeat;
    background-position: right top;
}
```
> background-position : right top, left top...

- BackGround attachement: 
```css
body {
    background-image: url("images/smth.png");
    background-repeat: no-repeat;
    background-attachment: fixed;
}
```

***CSS Fonts*** : 
> font family 
```css
body {
    font-family: Arial, Helvetica, sans-serif;
}
```

> font family : serif, sans-serif, monospace, cursive, fantasy.

- font style : 
```css
p.normal {
  font-style: normal;
}
p.italic {
  font-style: italic;
}
p.oblique {
  font-style: oblique;
}
```

- font seize : 
```css
h1 {
    font-size: 24px;
}
p {
    font-size: 14px;
}
```

> font-size : px, Large/medium...



***CSS Text*** :

- Text Color : 
```css
body {
    color: #434343;
}
```

- Text alligement : 
```css
h1 {
    text-align: center;
}
p {
    text-align: justify;
}
```

***CSS Links*** : 

- Links : 

```css
a:link {
    color: #1ebba3;
}
a:visited {
    color: #ff00f4;
}
a:hover {
    color: #a766ff;
}
a:active {
    color: #ff9800;
}
```

***CSS Lists*** : 

- Lists : 
```css
ul {
    list-style-type: square;
}
ol {
    list-style-type: upper-roman;
}
```