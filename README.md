# ``codigos_cr``

Esta es una colección de códigos postales, electorales y otras
ontologías de uso común u oficial para ordenar las regiones geográficas de Costa
Rica. Todos se encuentran en formato CSV. En el directorio ``ASCII/`` se encontrarán los 
mismos archivos, pero en una codificación sin tildes ni eñes. 

## Códigos postales (``postal.csv``)

Códigos de cada distrito en Costa Rica, de acuerdo a la clasificación
utilizada por Correos de Costa Rica. En el directorio ``postal_full_inec/`` se encuentra una 
versión de esta nomenclatura dividido en varios archivos y con información de las regiones
socioeconómicas utilizadas por el INEC para cada distrito. 

**NOTAS IMPORTANTES**:

  - Existen un desfase temporal entre los cambios en las divisiones políticas del país y 
la nomenclatura utilizada por Correos de Costa Rica; por ejemplo, Río Cuarto sigue siendo tratado como un 
distrito del cantón de Grecia, a pesar de que desde 2017 se considera un nuevo cantón.

## Códigos electorales (``electoral.csv``)

Códigos de cada distrito electoral en Costa Rica, de acuerdo a la clasificación
utilizada por el Tribunal Supremo de Elecciones.

**NOTAS IMPORTANTES**: 

  - Los distritos electorales son muchos más que los oficiales ya que cuentan ciertos centros de votación 
importantes como si fueran distritos separados. En general, la clasificación de Correos
de Costa Rica es mucho más consistente con el ordenamiento oficial que los distritos electorales.

  - Existe una provincia adicional ("provincia número ``8``") que
 denota los consulados costarricenses alrededor del mundo. En tal
 caso, la provincia es ``CONSULADO``, el cantón es el país
 correspondiente, y el distrito es la ciudad en la cual se encuentra
 dicho consulado.
