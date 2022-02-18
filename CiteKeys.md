# CiteKeys

Las entradas bibliográficas son referenciadas en LaTeX (y en cualquier otro medio y formato)
mediante una clave ("citekey"). Esta clave puede ser cualquier cadena de caracteres siempre y
cuando la relación entre claves y entradas sea biunívoca. Pero si además la clave da información
como para poder identificar el artículo, tanto mejor.

La propuesta para construir la clave de una entrada bibliográfica cualquiera es la siguiente.

## Artículos, proceedings y libros

Artículos, proceedings y capítulos de libro serán nombrados con una clave construida con el primer
apellido del primer autor, el año de publicación, la primera palábra del título, y tras un guión
bajo '_', el primer y último carácter de la cadena tras el último símbolo "/" en el DOI del
documento. Por ejemplo, si el artículo se llama "Why me?", el primer autor es John Doe, y fue
publicado en 2020 con el DOI "10.137/journal.x.30522"... de aquí en adelante este artículo será
referenciado como 'Doe2020Why_j2'.

## Preprints

Los preprints depositados en el arXiv tendrán una clave similar a la del artículo publicado. Pero
esta vez, en lugar de atender al DOI para extraer los dos últimos caracteres de la clave,
acudiremos al arXiv ID con una estrategia similar. En este caso, la clave contendrá el primer y
último carácter del número de ID tras el punto '.'. Por ejemplo, el preprint "Why you?" escrito por
John Doe en 2020 con el ID "arXiv:1501.05235" será referenciado como 'Doe2020Why_05'.

## Tesis

Las tesis tendrán una clave sencilla construida con la cadena "Thesis:" seguida del primer apellido
del autor, el año y la primera palabra del título. Así, la tesis titulada 'Me and my thesis'
escrita por John Doe con el año de registro 2020 tendrá la clave 'Thesis:Doe2020Me'.

