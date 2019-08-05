# CSS

## Übung 1

Wenn du mit CSS noch nicht vertraut bist, dann lies dir Folgendes durch bevor du mit der nächsten Anweisung beginnst:

<a href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics">CSS-Grundlagen</a>

Danach solltest du wissen was ruleset/rule, selector, property und ein property-value im Zusammenhang mit CSS bedeutet.

Desweiteren solltest du wissen, was das Box-Model ist (https://www.w3schools.com/css/css_boxmodel.asp, https://wiki.selfhtml.org/wiki/Box-Modell) und wie es sich auf die Dimensionen eine Elementes auswirken.

Öffne die in den HTML-Übungen angelegte CSS-Datei unter css/styles.css und beginne damit die ungeordnete Liste innerhalb des `nav`-Elements zu stylen. Bei der Gestaltung der Liste hast du freie Wahl. Vielleicht hast du dir schon ein paar Farben o.ä. ausgesucht, mit denen du die Seite gestalten möchtest.  
Du kannst für die Liste entweder Element-Selektoren, Klassen-Selektoren oder auch Ids verwenden (https://www.w3schools.com/cssref/css_selectors.asp). Dabei solltest du beachten, dass es Unterschiede der Selektoren gibt und du solltest nicht vergessen, dass bei Klassen- und Id-Selektoren auch entsprechende Attribute im Markup vergeben werden müssen.

Beim Styling der Navigation solltest du dich auch mit der Spezifizität der CSS-Selektoren vertraut machen (https://developer.mozilla.org/de/docs/Web/CSS/Spezifit%C3%A4t, https://little-boxes.de/lb1/6.5-spezifitaet-punktesystem-fuer-selektoren.html, https://css-tricks.com/specifics-on-css-specificity/). Das hilft dir z.B. dabei dass properties nur auf die Liste innerhalt des `nav`-Elementes angewendet werden.

## Übung 2

Jetzt solltest du dich mit der Positionierung von Elementen auseinandersetzen. Füge deinem Markup ein neues Element (z.B. ein `div`) hinzu das zwei Kind-Element hat. Mittels CSS fügst du dem Container einen sichtbaren Rahmen hinzu und für die Kind-Elemente rules hinzu. Die beiden Kind-Elemente sollten die gleiche Größe haben und du solltest für jedes Element jeweils eine eigene Hintergundfarbe definieren. Darüber hinaus gebe den Kind-Elementen unterschiedliche properties bzgl. der Positionierung (https://www.w3schools.com/css/css_positioning.asp) und sieh dir an, wie sich die Elemente verhalten.
Danach solltest du unbedingt ausprobieren, was passiert, wenn du die Positionierung des Eltern-Elementes änderst.

## Übung 3

In dieser Übung geht es um die display-Properties (https://www.w3schools.com/cssref/pr_class_display.asp). In den Übungen zu HTML hast du schon einige Elemente kennen gelernt, die ein unterscheidliches Anzeigeverhalten aufweisen (https://www.w3schools.com/html/html_blocks.asp) Dazu füge in dein Markup ein `<span>`, ein `<a>`, ein `<div>` und ein `<p>` hinzu. Füge im CSS mittels eines Selektors deiner Wahl für alle diese Elemente die properties `height`, `width`, `margin` und `padding` mit entsprechenden property-values ein. Öffne die Seite im Browser und untersuche die Element mit den Developer-Tools (im Chrome und Firefox mit der Tastenkombination `STRG` + `Shift` + `I` anzuzeigen). Wie werden die Element gerendert? Was kann man für properties an den Elementen setzen, um das Anzeigeverhalten zu ändern?

