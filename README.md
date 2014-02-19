Greg
====
## (G)reat (r)esponsive (e)asy (g)rids.

This is a boilerplate responsive grid and we encourage you to extend it as necessary.

Greg will take the number of columns you need and the gutter spacing you require and create a fluid grid based on those parameters.

For example you could make a 12 column grid with 2% gutters using the following code;
```
.myClass {
    width:100%;
    @include greg(12,2%);
}
```

This will generate the following CSS
```
.col_10 { width:100%; margin-left:2%; float:left; }
.col_9 { width:89.8%; margin-left:2%; float:left; }
.col_8 { width:79.6%; margin-left:2%; float:left; }
.col_7 { width:69.4%; margin-left:2%; float:left; }
.col_6 { width:59.2%; margin-left:2%; float:left; }
.col_5 { width:49.0%; margin-left:2%; float:left; }
.col_4 { width:38.8%; margin-left:2%; float:left; }
.col_3 { width:28.6%; margin-left:2%; float:left; }
.col_2 { width:18.4%; margin-left:2%; float:left; }
.col_1 { width:8.2%; margin-left:2%; float:left; }
```

And the HTML could go a little something along these lines
```
<ul class="myClass">
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
    <li class="col col_1"></li>
</ul>
<ul class="myClass">
    <li class="col col_3"></li>
    <li class="col col_7"></li>
</ul>
```