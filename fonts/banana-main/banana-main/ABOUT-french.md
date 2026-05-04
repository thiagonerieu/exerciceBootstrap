

# À PROPOS DE LA BANANA (FRENCH)

La fonte Banana est la reprise et le développement du lettrage dessiné pour le titre de l'édition Banane Flambée - Essais sans suite. Elle a été crée et développée par Clara Bougon à la suite d'un workshop SingleLine mené par Open Source Publishing qui a donné lieu à la fonte Janstroke. La Banana a pu voir le jour grâce aux ressources communiquées avec la Relief SingleLine.

## Metapost et Fontes SingleLine

La Banana est une fonte qui peut être utilisée, comme n'importe quelle fonte, en tant que traitement de texte, sous sa forme Outline.
Cependant, elle possède aussi une version SingleLine, avec un nom de fichier terminant par ".svg".
Le terme SingleLine désigne une fonte qui n'est pas dessinée par le contour mais par le squelette, via une seule ligne, comme l'écriture manuscrite : c'est la nature et l'inclinaison de l'outil/stylo qui donne le résultat final. Cela la rend rapide et pratique à utiliser avec un traceur, une découpeuse laser ou bien une CNC. (voir le specimen SingleLine, dessiné au plotter "banana-singleline-specimen.pdf")

Banana SingleLine est une fonte dessinée grâce à du code Metapost, et destinée à être utilisée par un plotter/traceur, notamment grâce à l'extension "Hershey Text" du logiciel Inkscape. Metapost est un système de création de figures. Ici, Metapost a été utilisé pour générer automatiquement des courbes entre plusieurs points de manière à optimiser le tracé. Les fichiers SVG qui en résultent ont été modifiés/améliorés dans FontLab, puis dans FontForge pour générer un fichier de fonte SVG utilisable par une machine.


## QUNI

Dans sa version Outline, la Banana propose une série de ligatures post-binaires comme proposition d'alternative à l'écriture inclusive par le point médian. Pour utiliser ces glyphes inclusifs, il vous suffit d'ajouter deux points ".." entre les lettres que vous souhaitez ligaturer : vif..ve, franc..he, aimé..e, etc.

Les caractères inclusifs de la Banana sont encodés en accord avec le standard de la Queer Unicode Initiative (QUNI) développé par Bye Bye Binary https://typotheque.genderfluid.space/fr.
Cette fonte est distribuée sous licence CUTE (Conditions d'Utilisation Typographique Engageante), elle aussi développée par Bye Bye Binary. https://typotheque.genderfluid.space/fr/licences


## Contenu

Le projet Banana s'appuie sur un fichier source squelette .ufo et explore différents formats d'exportation de polices :

• Les formats de dessin ouverts, ou Stroke fonte, destinés à l'usinage CNC, au dessin par plotter, traceur, graveuse laser… (voir le dossier "SingleLine"). Ce dessin est le dessin original de la fonte, auquel on peut appliquer n'importe quel outil/brosse, c'est à dire la forme et l'épaisseur que prendra le squelette original. Les formats disponibles sont :

    - SVG pour Inkscape et son extension Hershey Text
    - OTF-SVG pour AdobeIllustrator (au delà de 2019)
    - TTF pour les logiciels comme Rhino3D ou AutoCAD


• Les formats de dessin fermés, destinés à l'usage print et web.
(voir le dossier "OutLine"). Ces dessins sont des aplatissements de certains "strokes" appliqués au dessin squelette. Vous pouvez en générer bien plus en créant vos propres caractéristiques dans le panel "stroke" ou "contour" de votre logiciel de dessin de caractère, lorsque vous utilisez le fichier SingleLine. Les formats disponibles sont :

    - OTF (la version OTF des contours fermés est nécessaire dans les premières étapes du processus de mise en page d'Inkscape)
    - WOFF2
    - TTF
