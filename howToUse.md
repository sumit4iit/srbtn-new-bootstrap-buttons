How to use srbtn.css?
======================
[A] srbtn is css styling framework hence it is mainly a css file that you might want to add in your webpage head
I will recommend you to use `srbtn.min.css` file which is low-size minified css file contain srbtn styling css codes OR you can go ahead with `srbtn.css` file in which you can edit code easily if you needed.

So your head will look like
`<head> <link href="srbtn.min.css" rel="stylesheet" type="text/css"> ... </head>`

OR you can use cdn link, which will minimise your efforts to store css file
`<head> <link href="//cdn.squarect.com/srbtn.css" rel="stylesheet" type="text/css"> ... </head>`


[B] Now we are going to learn about sizes, colors and active class
Basically, `srbtn` buttons works same as bootstrap buttons. There are many color schemes that are added in css files to give buttons different look. All are listed at http://www.squarect.com/buttons

Let's take `red` color scheme for an example. There are primary 4 classes viz. `.srbtn` , `.srbtn-r5` , `.srbtn-xs` , `.active`. First two are sufficient while last two used to change button size and clicked look. `.srbtn` class must be added to give button basic css style. `srbtn-r5` which can be represented as `srbtn-colN` where 'col' is color and 'N' is fading quotient. In given example 'col'=r (which is red) and 'N'=5 which means button is faded up to 50%. 'N' runs from [0,9] where 0 is least faded condition and 9 is most faded condition. 'col' run over all spectral band which you can explore at http://www.squarect.com/buttons

[C] Supplementary class `srbtn-xs` which can be represented as `srbtn-size` in which 'size' runs in [xs,xm,lg,block]. Where 'xs' means 'extra-small' button, 'sm' means 'small' button, 'lg' means 'large' button and 'block' means 'block or full width' button. If you don't add this class, then 'srbtn' will take default size.

[D] Supplementary class `active` is added to display button 'activated' or 'clicked'.

So our final button html will look like this
`<button class="srbtn srtbn-r4 srbtn-lg active"></button>` OR Simply `<button class="srbtn srtbn-r4"></button>` 



