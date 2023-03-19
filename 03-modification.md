# MODIFICATION
```html
<html>
  <head>
    <title>Selector<title>
  </head>
      
  <body>
    <h1>Hello World</h1>
    
    <p>my name is budi<p>
    <p>i live in indonesia</p>
    <p>i am a farmer</p>
    <p>nice to meet you!!!</p>
    
    <div class="container">
      <div class="box">box 1</div>
      <div class="box">box 2</div>
      <div class="box">box 3</div>
      <div class="box">box 4</div>
    </div>
    
    <div class="input">
      <input id="username-input" type="text" placeholder="username">
      <input id="password-input" type="password" placeholder="password">
    <div>   
  </body>
</html>
```
____
### Memodifikasi Style Element
> mengambil value property style element
```html
$("[target]").css("[nama-property]");

<script>
  $(document).ready({
     $("h1").css("color");      // rgb(0,0,0)
     $("h1").css("font-size");  // 32px
  });
</script>
```
> mengatur style element
```html
$("[target]").css("[nama-property]","[value]");

<script>
  $(document).ready({
     $("h1").css("color","red");      
     $("h1").css("background-color","blue");  
  });
</script>
```
____
### Memodifikasi Attribute Element

> mengambil value attribute element
```html
$("[target]").attr("[nama-attribute]");

<script>
  $(document).ready({
     $(".input #username-input").attr("type");    // text      
     $(".input #password-input").attr("placeholder");    // password
  });
</script>
```
> mengatur value attribute element

```html
$("[target]").attr("[nama-attribute]","[value]");

<script>
  $(document).ready({
     $("h1").attr("id","judul");      
     $(".input #username-input").attr("readonly","");  
  });
</script>
```
> memodifikasi text element

> memodifikasi inner html element
