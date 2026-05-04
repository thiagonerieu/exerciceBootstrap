# ABOUT BANANA

The Banana font is a reworking and development of the lettering designed for the title of the fanzine Banane Flambée - Essais sans suite. It was created and developed by Clara Bougon following a SingleLine workshop run by Open Source Publishing, which resulted in the Janstroke font. Banana was made possible thanks
to the resources communicated with the Relief SingleLine font.

## Metapost and SingleLine fonts

Banana is a font that can be used, like any other font, in any printed or web publication, in its Outline form.
However, it also has a SingleLine version, with a file name ending in ‘.svg’.
The term SingleLine designates a font that is not drawn by the outline but by the skeleton, via a stroke, like handwriting: it is the nature and inclination of the tool/pen that gives the final result. This makes it quick and easy to use with a plotter, laser cutter or CNC. (see SingleLine font specimen attached, which was plotted "banana-singleline-specimen.pdf")

Banana SingleLine is a font drawn using Metapost code, and designed to be used by a plotter/plotter, in particular using the Inkscape ‘Hershey Text’ extension.
Metapost is a system for creating figures. Here, Metapost was used to automatically generate curves between several points in order to optimise the plot. The resulting SVG files were modified in FontLab and then in FontForge to generate a machine-readable SVG font file.

## QUNI

In its Outline version, Banana offers a series of post-binary ligatures as an alternative to inclusive writing using the median point. To use these inclusive glyphs, simply add two dots ‘..’ between the letters you want to ligate: s..he, him..er, etc.

Banana's inclusive characters are encoded in accordance with the Queer Unicode Initiative (QUNI) standard developed by Bye Bye Binary https://typotheque.genderfluid.space/fr.
This font is distributed under the CUTE licence (Conditions d'Utilisation Typographique Engageante), also developed by Bye Bye Binary. https://typotheque.genderfluid.space/fr/licences

## Content

The Banana project is based on a .ufo skeleton source file and explores different font export formats:

•  Open Paths, or Stroke fonts, intended for CNC machining, drawing by plotter, laser engraver... (see the ‘SingleLine’ folder). This drawing is the original drawing of the font, to which any "brush" can be applied, i.e. the shape and thickness that the stroke drawing will take. The formats available are :

    - SVG for Inkscape and its Hershey Text extension
    - OTF-SVG for AdobeIllustrator (beyond 2019)
    - TTF for software such as Rhino3D or AutoCAD


- Closed paths for print and web use.
(see the ‘OutLine’ folder). These drawings are flattened versions of some strokes applied to the skeleton drawing. You can generate more instances by specifying your own characteristics in the ‘stroke’ or ‘contour’ panel of your character design software, when using the SingleLine file. The formats available are :

    - OTF (the OTF version of closed outlines is required in the early stages of the Inkscape layout process)
    - WOFF2
    - TTF
