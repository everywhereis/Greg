Greg
====
## (G)reat (r)esponsive (e)asy (g)rids.

This is a boilerplate responsive grid. We encourage you to extend it as you need. Greg will take the number of columns you need and the gutter spacing you require and create a fluid grid based on those parameters.

For example you could make a 12 column grid with 2% gutters using the following code;
```
.myClass {
    width:100%;
    @include greg(12,2%);
}
```

This will generate the following CSS
```
.col_1 { ... }
.col_2 { ... }
.col_3 { ... }
.col_4 { ... }
.col_5 { ... }
.col_6 { ... }
.col_7 { ... }
.col_8 { ... }
.col_9 { ... }
.col_10 { ... }
.col_12 { ... }
.col_12 { ... }
```