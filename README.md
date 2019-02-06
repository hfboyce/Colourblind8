# DSCI-524-Colourblind8

A Python package for DSCI 524

### Authors

* [Ian Flores](https://github.com/ian-flores)
* [Sabrina Tse](https://github.com/sabrinatkk)
* [Hayley Boyce](https://github.com/hfboyce)


### Project

**Overview**

Colourblind8 will be a brand new theme package deployable in Python matplotlib and R ggplot2 to optimize graphs into a more colourblind-friendly presentation - more interpretable by people with colourblindness. Colourblindness, also known as colour vision deficiency, is a condition that affects individuals how they perceive colours visually. According to colourblindawareness.org, colourblindness affects 1 in every 12 men and 1 in every 200 women globally. The package is inspired by the fact that the impact of data visualization will be protected and further enhanced if proper colours are used so that the graphs are perceived correctly by all readers as intended.

**Scope**

At this stage, Colourblind8 will focus on developing settings for the three most prevalent colourblind perspectives - protanopia, deuteranopes and tritanopes (see Appendix for more information on the types of colourblindness). 


### Functions Included In This Package

- `set_deutera()`:
  - This function implements a theme that makes plots accesible to people with deuteranopia. It modifies the colour of geometric objects (points, lines, etc) and the layout of the plot.
- `set_prota()`
  - This function implements a theme that makes plots accesible to people with protanopia. It modifies the colour of geometric objects (points, lines, etc) and the layout of the plot.
- `set_trita()`
  - This function implements a theme that makes plots accesible to people with tritanopia. It modifies the colour of geometric objects (points, lines, etc) and the layout of the plot.




### Our Package in the Python Ecosystem 




### Appendix

Protanopia

Protanopes are more likely to confuse:-
1. Black with many shades of red
2. Dark brown with dark green, dark orange and dark red
2. Some blues with some reds, purples and dark pinks
3. Mid-greens with some oranges

Deuteranopes

Deuteranopes are more likely to confuse:-
1. Mid-reds with mid-greens
2. Blue-greens with grey and mid-pinks
3. Bright greens with yellows
4. Pale pinks with light grey
5. Mid-reds with mid-brown
6. Light blues with lilac

Tritanopes

The most common colour confusions for tritanopes are light blues with greys, dark purples with black, mid-greens with blues and oranges with reds. 

source:http://www.colourblindawareness.org/colour-blindness/types-of-colour-blindness/

-------------------------------------------------------
http://www.colourblindawareness.org/colour-blindness/

