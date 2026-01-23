[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/deed.es)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--2819--5157-green?logo=orcid&logoColor=white)](https://orcid.org/0009-0009-2819-5157)

# _Grandes chroniques de France_ de Charles V. Prólogo, índice de contenidos y caps. I-V en formato digital
## Editado por [Carlos Llamedo Gutiérrez](https://orcid.org/0009-0009-2819-5157)

# Presentación del proyecto y del texto

Esta edición del texto se ha creado como trabajo de curso para la asignatura [Tecnologías de la Información y la Comunicación Aplicadas a la Historia](https://www.uniovi.es/estudia/grados/humanidades/historia/-/fof/asignatura/GHISTO01-4-005) del [grado en Historia](https://www.uniovi.es/estudia/grados/humanidades/historia) de la [Universidad de Oviedo](https://www.uniovi.es).

El fragmento editado pertenece a las _Grandes crónicas de Francia_, encargadas originalmente por Luis IX y continuadas por los monjes de Saint-Denis por orden de Carlos V hasta 1379. En ellas se presenta un relato inédito de la historia de la realeza francesa; texto e ilustración contribuyen a reforzar la idea de la legitimidad y el poder de los Valois en el último cuarto del siglo XIV, trazando una historia de los francos que se remonta a los troyanos y que cubre a las dinastías Merovingia, Carolingia y la de los Capeto y, a las que se añaden posteriormente los reinados contemporáneos de los Valois Juan II el Bueno y de Carlos V el Sabio. 

Se ofrece así una rara oportunidad de comprender la génesis y la evolución del pensamiento político real y de la propaganda francesa de época. En esta edición se presentan el prefacio de la crónica, la tabla de contenidos que se hace de ella y sus cinco primeros capítulos, que comienzan en la guerra de Troya y terminan con Clodión, de la dinastía Merovingia.

# Aspectos formales de la transcripción

Transcripción efectuada a partir de la reproducción digital del fragmento del [manuscrito Français 2813](http://gallica.bnf.fr/ark:/12148/btv1b84472995) puesto a disposición del publico por el [Département des Manuscrits](https://www.bnf.fr/fr/departement-des-manuscrits) de la [Bibliothèque nationale de France](https://www.bnf.fr).

Se han intentado respetar las normas de la Comission Internationale de Diplomatique, actualizando al francés moderno normas de acentuación y puntuación. 

Así, en el caso de las palabras que utilizan la diéresis en francés, que marcan un diptongo en la actualidad, se han mantenido también: «païs». De hecho, esta última es una forma arcaica del actual «pays», al que se tuvo que aplicar la diéresis para marcar el diptongo que con «y» es evidente. El acento circunflejo es uno irregular, que marca vocales a las que antiguamente seguía una «s». Tal es el caso de «maître», que en el texto aparece como «maistre». En los casos en los que conserva la «s», se ha optado por no añadir el acento circunflejo, siendo inútil su utilización. Sin embargo, en palabras que ya en el texto han perdido la «s», tales como «îlle» —actualmente «île»— mantengo el acento circunflejo.

Mantengo las grafías del texto: «c» en presuntos sonidos \[s] («me**ç**onge»), e «i» en \[ʒ] («a**j**outer»). Trazar la evolución de cada «c» y cada «i» consonántica podría complicar demasiado el ejercicio. El desarrollo de abreviaturas se hace explícito en cada caso, optándose por modernizar la palabra si cabe. Así, una «q» abreviada y seguida de palabra por vocal no se desarrolla como «que», sino como «qu’». Las coordenadas se expresan en formato decimal.

Durante la edición se ha trabajado sobre un fichero en el que se han respetado los cambios de página, columna y línea, indicándose todos ellos. Al finalizar la edición, se han empleado las funciones de «buscar y reemplazar» de `Notepad++` para eliminar esto y presentar una versión del fichero más legible. 

# Codificación

## Aspectos generales

En el planteamiento de edición de este texto tomé ejemplos de varios sitios. Evidentemente, el primero fue el estándar marcado por el proyecto [Text Encoding Initiative (TEI)](https://tei-c.org/), que puede presumir de tener [una excelente documentación](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html). En las fases preliminares del proyecto fueron de especial ayuda los siguientes tres apartados: [«3 Elements Available in All TEI Documents - The TEI Guidelines»](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/CO.html), [«10 Manuscript Description - The TEI Guidelines»](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/MS.html), [«13 Names, Dates, People, and Places - The TEI Guidelines»](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/ND.html). 

En ella se puede delinear claramente cuál sería la estructura de etiquetado básica, aunque recurrí a más fuentes, ejemplos concretos de codificación de manuscritos medievales realizados con el estándar. Dos proyectos en especial sirvieron en la codificación: [Andrew Dunning, «Transcribing Medieval Manuscripts with TEI»](https://andrewdunning.ca/transcribing-medieval-manuscripts-tei); [«Normas de transcripción», 7 Partidas Digital](https://7partidas.hypotheses.org/normas-de-transcripcion).

Es común en estos proyectos marcar la longitud de línea, columna y página, pero eso hace el texto difícilmente legible. Se opta, finalmente, por presentar dos formatos del texto, uno en el que se mantuviesen estos aspectos y otro en el que no. Para simplificar, trabajo sobre un documento en el que sí se mantienen (_Llamedo Gutiérrez_BnF_Français 2813_) del que se eliminan, una vez hecho, las rupturas (_Llamedo_Gutiérrez_BnF_Français 2813 - sin saltos de línea-columna-página_).

## Etiquetado

### Idioma

La cuestión del idioma ha sido una que ha planteado difíciles decisiones a lo largo del trabajo, y en los atributos de las etiquetas no ha sido distinto. 

Se opta finalmente por utilizar el inglés en ellos por dos motivos principales. El primero de ellos es la mera costumbre: etiquetar en inglés es un estándar en programación, un mundo donde nunca se sabe en manos de quién acabará el código (hay quien argumentaría que el código se hace más accesible, aunque tengo mis reservas en este caso concreto).

Además de ello, las normas TEI P5 dan valores recomendados a varios atributos, todos ellos en inglés, y seguirlo da mayores visos de coherencia y de sistematicidad. «Inglés salvo que sea absolutamente necesario» (véanse casos como `<region type="provincia">`) es de alguna manera una norma más clara que mezclar en los atributos inglés y español.

### Aspectos gráficos

1. Saltos de página (`<pb/>`), columna (`<cb/>`) y línea (`<l/>`). Cada uno de ellos utiliza el atributo `@n` para indicar su número. En el caso de que una palabra se corte al final de la línea, `<l/>` incorpora el atributo `break="no"`.
2. Mayúsculas (`<hi>`). En caso de encontrar una capital decorada, se utiliza el atributo `rend="init#colour"`, donde `#` corresponde al número de líneas que la capital abarca y `colour`, al color de la misma.
3. Daño (`<damage>`). En caso de encontrar una sección del texto dañada de cualquier forma, se encapsula el texto legible afectado en esta etiqueta, utilizando el atributo `@type` para dar alguna concreción si se puede.

### Aspectos textuales

1. División lógica del texto (`<div>`). El prólogo, el índice y cada uno de los capítulos está marcado con esta etiqueta, que utiliza los atributos `@type` (`"prologue"`, `"table of contents"` y `"chapter"`) y `@n` (numeración) para hacer precisiones.
2. Abreviaturas desarrolladas con `<ex>`.
3. Para adiciones de texto (sea en un margen, en la parte superior o directamente encima de otra palabra) se utiliza `<add>` con el atributo `@place`. En caso de que la adición sea encima del propio texto, `<add>` se encapsula dentro de la etiqueta `<subst>`, y se incorpora el atributo `hand="#mano"`, donde `mano` se sustituye por un elemento identificador del corrector (como, por ejemplo, la tinta más oscura que usa `"#black"`).
4. Para elementos de la transcripción dudosas se utiliza la etiqueta `<unclear>`.
5. Para elementos considerados errores en el contexto del texto, se utiliza `<sic>`. Haría falta un conocimiento verdaderamente profundo de la escritura francesa de la época para utilizar esto efectivamente, así que su uso es bastante reducido.
6. Nombres personales codificados con `<persName>`, nombres de organizaciones, con `<orgName>`, topónimos con `<placeName>` y gentilicios con `<rs type="demonym">`. A todos ellos acompaña un atributo `@type` para clasificarlo (`"king"`, `"city"`) y el atributo `ref="#código"`, donde `código` es reemplazado por un identificador único que permite singularizar y referenciar ese elemento en concreto.
	  - En la singularización que se hace de personajes, organizaciones y lugares antes del texto se utilizan `<trait>` para indicar vinculaciones. En los personajes, `<roleName>` con el atributo `ref="#organización"` (donde `organización` se sustituye por el identificador concreto) se utiliza para vincularlos a organizaciones listadas.
7. Fechas y duraciones se etiquetan con `<date>`, añadiendo el atributo `@when` para una fecha concreta, `@notAfter` o `@notBefore` para dataciones _ante quem_ y _post quem_, `@from` y `@to` para un rango concreto y `@dur` para indicar duraciones (se utilizan `YS` para indicar años). Se añadió el atributo `@type` para indicar algún tipo de datación específica, como Ab Urbe Condita (`AUC`). Lo mismo aplica para `<birth>` y `<death>` en el caso de los personajes.

### Miscelánea: comentarios

Los comentarios (`<!-- comentario -->`) se han utilizado a lo largo de todo el texto para marcar elementos que no se consideran merecedores de otro tratamiento pero que sí quiero que queden reseñados, o para singularizar cosas que se suponen descritas a un nivel más general. Consideraciones lingüísticas para la transcripción, símbolos y ornamentos, aclaraciones de la codificación, conjeturas acerca de significados, etc.

# Derechos

Esta obra está bajo una [licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional](LICENCE.md).

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/deed.es)
