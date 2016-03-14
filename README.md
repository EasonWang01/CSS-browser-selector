# CSS-browser-selector
將不同瀏覽器指定不同樣式


1.先include上面的js file

2.新建一個style如下


範例
```
<style type="text/css">
.ie .example {
  background-color: yellow
}
.ie7 .example {
  background-color: orange
}
.gecko .example {
  background-color: gray
}
.win.gecko .example {
  background-color: red
}
.linux.gecko .example {
  background-color: pink
}
.opera .example {
  background-color: green
}
.konqueror .example {
  background-color: blue
}
.webkit .example {
  background-color: black
}
.example {
  width: 100px;
  height: 100px;
}
```
