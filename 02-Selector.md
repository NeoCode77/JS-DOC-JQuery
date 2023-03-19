# SELECTOR
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

> selector tag html

```html
<script>
  $(document).ready({
      $("h1");
      $("p");
      $("div");
  });
</script>
```
> selector id html

```html
<script>
  $(document).ready({
      $("#username-input");
      $("#password-input");
  });
</script>
```
> selector class html

```html
<script>
  $(document).ready({
      $(".container");
      $(".box");
      $(".input");
  
      // first element
      $(".box:first");
      // second element
      $(".box:eq(1)");
      // third element
      $(".box:eq(2)");
      // last element
      $(".box:last");
  });
</script>
```
