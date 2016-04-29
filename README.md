#sandal-grid
##a simple responsive grid system with minimalist syntax. Based on bootstrap grid system, but with improvements. Easy to write, to understand and to embed into projects. 

|prefixes | meaning   |
|:--------|:---------|
|   x     | eXtraSmall (<768px) |
|s| 768px < Small < 992px | 
|m| 992px > Medium > 1200px |
|l| 1200px > Large|

example: 
```
<div class=".x-4 .s-4 .m-6 .l-6"> </div>
```
This div has 4 size in displays smaller than 992px and for bigger than this, has 6 size in the grid system. It's basically like how the Bootstrap grid works, but lightweight.

You can use offset too. the syntax is:

```
<div class=".x-4 .x-os-2 .s-4 .s-os-2 .m-6 .l-6"> 
```
Now, when smaller than 992px, the div has size 4 and offset 2. OS is an abbreviation fo OffSet;

####Enjoy the ride with sandal-grid;



