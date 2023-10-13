# Einstein CV Template
## How to write your CV with this template
This template requires [LaTeX](https://www.latex-project.org/). IF you don't know what this means, then you should probably not invest your time learning it now[^1].

## How to customize the CV to your taste
### Colors
To start with, you'll most certainly want to chose different colors for the backgrounds (header, contact band and left column). It all happens in [cv_einstein.cls](cv_einstein.cls). Thanks to tools such as [HSB Color Picker](https://codepen.io/HunorMarton/details/eWvewo) finding a suitable hue, saturation and brightness should be pretty easy. The only caveat is that the template takes hue values between [0;1] while most online color pickers display hues in [0; 255] or [0; 360] ranges. You'll have to do some maths.

### Icons
All icons come from Font Awesome for LaTeX, whose documentation is available at [doc/fontawesome.pdf](doc/fontawesome.pdf).

### Layout
Rearranging the layout and the visual elements should also be pretty straightforward. If you experience any problem, as the template doesn't use any fancy package beyond [paracol](https://www.ctan.org/pkg/paracol) and [tikz](https://tikz.net/).

Although you'll see some negative `\hspace{}` and `\vspace{}` here and there to keep things aligned, resizing and moving things around shouldn't give you any headache.

Having said that...

## Request
This template can be improved in many ways, from code quality to its visual design. If you make a fork with your own ideas, please be kind and share your version back on [Overleaf](https://www.overleaf.com/), where I drew most of my inspiration from, as a way to thank the community.

I hope this template will make your job search successful!

ML

[^1]: Still, if you are new to LaTeX and want to give it a try, I recommend using [Overleaf](https://www.overleaf.com) with a free plan. This CV template is available in [Overleaf's public gallery](https://www.overleaf.com/latex/templates?q=CV+einstein) among many other templates I drew inspiration from.
