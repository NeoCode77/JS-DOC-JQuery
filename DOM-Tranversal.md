# DOM TRANVERSAL

> DOM tranversal digunakan untuk penelusuran element bedasarkan hubungan element tertentu.
```html
<body>
  
  <div class="container">
    
    <div class="box1"></div>
    <div class="box2"></div>
    <div class="box4"></div>
    
  </div>
  
</body>
```

**A. penelusuran parent element**
> dalam menelusuri perent dari elemet tertentu menggunakan method **parent()**.
```javascript
$(".box1").parent();      // <div class="container"></div>
```

**B. penelusuran child element**
> dalam menelusuri child dari elemet tertentu menggunakan method **children()**.
```javascript
$(".container").children();      
// <div class="box1"></div>
// <div class="box2"></div>
// <div class="box3"></div>

$(".container").children("box1");
// <div class="box1"></div>
```

**C. penelusuran after sibling element**
> dalam menelusuri element setelahnya dari sebuah element tertentu menggunakan method **next()**
```javascript
$(".container .box1").next();      
// <div class="box2"></div>
```

**D. penelusuran before sibling element**
> dalam menelusuri element sebelumnya dari sebuah element tertentu menggunakan method **prev()**
```javascript
$(".container .box2").prev();      
// <div class="box1"></div>
```
