# LaTeX-template

### Disclaimers
Few years back when I started learning LaTeX, I kept to already-made templates as I did not have the expertise to make my own.
This template was originally the [Lachaise Assignment](https://www.latextemplates.com/template/lachaise-assignment), however the current template has diverged so much
that I think it would be fair to say it is an entirely different template at this point. You can see artifacts of the original template in some of the organizational comments.

Most workarounds and some snippets of code (like the cancel slope fix or the augmented matrices trick) within the `structure.tex` file were not written by me 
and are gathered from all over the internet, primarily the TeX stackexchange. Back when I was taking these bits of code for my own use, 
I did not think I would be uploading this template to the internet, and hence I did not write down credits for the aforementioned snippets.
I currently do not have the time to go back digging the source of these snippets to cite them, but I will cite the rest of the codes I add
properly. I will eventually get around to finding the sources of the prior snippets as well, but I am too busy to do that right now.

Having said all this, if you wanted to modify and/or use this template, you can go ahead and do so no citations needed, as I don't think this is an original enough template.

### Problems with the template
Currently, I think there a few more noticeable issues with the template.
One is the listings package configuration, which I think is pretty hideous and I will certainly change later, whenever the next project that requires embedding code rolls around.

Second area of improvement is probably the title page, although I intentionally made it simple-looking, as I do not use this template for larger projects and such, and I didn't think
a grandiose title page would fit the theme of the small assignments it is used for.

Also, there are some patchwork fixes to various problems throughout the template that I tried to avoid but alas could not fix through the 'official' and 'intended' way.
One such fix is the head rule separation distance (distance from header text to header rule), which is set by redefining the `\headruleskip` macro. However, maybe due to
incompatibilities with XePersian or some naive mistake/misunderstanding of mine, redefining this macro does nothing and instead I had to opt for adding `\vspace` to the header directly.