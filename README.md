# units of measure demo

Nothing is located in the master branch. Instead, [switch to the other branches](https://github.com/saulbaizman-massart/units-of-measure/branches/stale) and view the commit history for annotations.

## demo index

+ [point (pt)](https://github.com/saulbaizman-massart/units-of-measure/commits/pt)
+ [pixel (px)](https://github.com/saulbaizman-massart/units-of-measure/commits/px)
+ [percent (%)](https://github.com/saulbaizman-massart/units-of-measure/commits/%25)
+ [em](https://github.com/saulbaizman-massart/units-of-measure/commits/em)
+ [root em (rem)](https://github.com/saulbaizman-massart/units-of-measure/commits/rem)
+ [viewport width (vw)](https://github.com/saulbaizman-massart/units-of-measure/commits/vw)
+ [viewport height (vh)](https://github.com/saulbaizman-massart/units-of-measure/commits/vh)
+ [vw or vh, whichever is smaller (vmin)](https://github.com/saulbaizman-massart/units-of-measure/commits/vmin)
+ [vw or vh, whichever is greater (vmax)](https://github.com/saulbaizman-massart/units-of-measure/commits/vmax)


## default type measurements

+ default typographic sizes are based on a scale of 16px body copy.

| element | px      | %    | em     |
|---------|---------|------|--------|
| h1      | 32px    | 200% | 2em    |
| h2      | 24px    | 150% | 1.5em  |
| h3      | 18.72px | 117% | 1.17em |
| h4      | 16px    | 100% | 1em    |
| h5      | 13.28px | 83%  | 0.83em |
| h6      | 10.72px | 67%  | 0.67em |
| body    | 16px    | 100% | 1em    |

## absolute units

### fonts

+ **pt.** Points are 1/72 of an inch. 
+ **px.** Pixels are 1/96th of an inch. According to the CSS specification, "The reference pixel is the visual angle of one pixel on a device with a pixel density of 96dpi and a distance from the reader of an arm’s length." With high-DPI devices, such as the 2x or even 3x Retina screens on iPhones, iPads, and some Macs, we need to understand the difference between a hardware pixel and the CSS reference pixel. For details, see [The CSS Layout Workshop](https://thecssworkshop.com/lessons/absolute-units) by Rachel Andrew. 

**Go deeper:** [view the W3C specification for absolute units](https://www.w3.org/TR/css3-values/#absolute-lengths).

## relative units

### fonts

+ **em.** The width of a letter "m." `em` is relative to the font size of its nearest ancestor.
+ **rem.** The "root em" is relative to the `font-size` of the `html`, or root, element. 
+ **%.** Percents are always relative to another value.

**Go deeper:** [view the W3C specification for relative units](https://www.w3.org/TR/css3-values/#relative-lengths).

### the viewport

The units below are relative to the viewport—not to a reader's default font size.

+ **vw.** 1% of the width of the [initial containing block](https://www.w3.org/TR/CSS21/visudet.html#containing-block-details).
+ **vh.** 1% of the height of the [initial containing block](https://www.w3.org/TR/CSS21/visudet.html#containing-block-details).
+ **vmin.** The smaller of `vw` or `vh`.
+ **vmax.** The larger of `vw` or `vh`.

**Go deeper:** [view the W3C specification for viewport relative units](https://www.w3.org/TR/css3-values/#viewport-relative-lengths).
