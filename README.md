# ``codigos_cr``

Esta es una colección de códigos postales, electorales y otras
ontologías de uso común/oficial para ordenar las regiones geográficas de Costa
Rica. Todos se encuentran en formato CSV. En el directorio ``ASCII/`` se encontrarán los 
mismos archivos, pero en una codificación sin tildes ni eñes. 

## Códigos postales (``postal.csv``)

Códigos de cada distrito en Costa Rica, de acuerdo a la clasificación
utilizada por Correos de Costa Rica. En el directorio ``postal_full_inec/`` se encuentra una 
versión de esta nomenclatura dividido en varios archivos y con información de las regiones
socioeconómicas utilizadas por el INEC para cada distrito. 

**NOTA**: Existen un desfase temporal entre los cambios en las divisiones políticas del país y
 la nomenclatura utilizada por Correos de Costa Rica; por ejemplo, Río Cuarto sigue siendo tratado como
 un distrito del Cantón de Grecia, a pesar de que desde 2017 se considera un nuevo cantón

## Códigos electorales (``electoral.csv``)

Códigos de cada distrito en Costa Rica, de acuerdo a la clasificación
utilizada por el Tribunal Supremo de Elecciones.

**NOTA**: Existe una provincia adicional ("número 8") que
 denota los consulados costarricenses alrededor del mundo. En tal
 caso, la provincia es "``CONSULADO``", el cantón es el país
 correspondiente, y el distrito es la ciudad en la cual se encuentra
 dicho consulado.
