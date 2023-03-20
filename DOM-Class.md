# DOM - CLASS MANIPULATION
> **DOM Class** digunakan untuk memanipulasi class yang ada pada element html.
```
<body>
  <div class="container">
    <div class="box1 merah"></div>
    <div class="box2 biru"></div>
    <div class="box3 hijau"></div>
    <div class="box4 kuning"></div>
  <div>
</body>
```

**A. menambahkan class**

> untuk menambahkan class pada sebuah element harus menggunakan method **addClass()**
```javascript
$(".container").addClass("kotak");
// <div class="container kotak"></div>

$(".container .box1").addClass("item-1");
// <div class="box1 merah item-1"></div>
```

**B. menghapus class**

> untuk menghapus class pada sebuah element harus menggunakan method **removeClass()**
```javascript
$(".container .box2").addClass("biru");
// <div class="box2"></div>
```

**C. pengecekan class**
> untuk pengecekan class pada sebuah element harus menggunakan method **hasClass()**
```javascript
$(".container .box3").addClass("hijau");
// true

$(".container .box2").addClass("coklat");
// false
```

**D. toggle class**
> toggle akan menambahkan class jika class tersebut tidak ada dalam element dan menghapus class jika class tersebut ada dalam element.
```javascript
$(".container .box4").toggleClass("item-4");
// <div class="box4 kuning item-4"></div>

$(".container .box2").toggleClass("biru");
// <div class="box2"></div>
```
