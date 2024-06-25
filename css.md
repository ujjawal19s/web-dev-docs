## Setting the css styles in 3 ways
### 1. External Styles
```
<link href="style.css" rel="stylesheet">
```
### 2. Inline Styles
```
<p style='color: red;'>I'm learning to code!</p>
```
### 3. Internal Styles
```
<head>
  <style>
    p {
      color: red;
      font-size: 20px;
    }
  </style>
</head>
```

## Selectors
selector {
  attribute : value ;
}
```
h1 {
  color: maroon;
}
```
### Universal Selector
```
* {
  border: 1px solid red;
}
```
### Class Selector
```
<p class='brand'>Sole Shoe Company</p>

.brand {

}
```
### Multiple Classes
```
<h1 class='green bold'> ... </h1>

.green {
  color: green;
}

.bold {
  font-weight: bold;
}
```
### Id Selector
```
<h1 id='large-title'> ... </h1>

#large-title {

}
```
### Attribute Selector
```
[href]{
   color: magenta;
}

img[src*='winter'] {
  height: 50px;
}
```
### Pseudo-class

```
p:hover {
  background-color: lime;
}

```
### Specificity

id > class > html element

### Combining Selector
### 1.Chaining
```
h1.special {

}
```
### 2.Descendant Combinator
```
<ul class='main-list'>
  <li> ... </li>
  <li> ... </li>
  <li> ... </li>
</ul>

.main-list li {

}
```
### 3. Multiple Selector
```
h1, h2{
  font-family: Georgia;
}
```
