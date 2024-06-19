# Descripció del Joc de Dades

Aquest projecte estudia les dades meteorològiques de diverses estacions de Barcelona a partir de tres sets de dades extrets del portal de dades obertes de la Generalitat de Catalunya.

## Sets de Dades Utilitzats

1. **Metadades variables meteorològiques**
   - Proporciona informació sobre les variables meteorològiques registrades a les estacions de la XEMA (Xarxa d’Estacions Meteorològiques Automàtiques).
   - Conté el nom de la variable, unitats de mesura, codi de la variable, etc.

2. **Metadades estacions meteorològiques automàtiques**
   - Ofereix informació sobre les estacions meteorològiques automàtiques de la XEMA.
   - Inclou el codi de l’estació, nom, ubicació, latitud, longitud, altitud, etc.

3. **Dades meteorològiques de la XEMA**
   - Proporciona registres de les lectures meteorològiques des de 2009 fins a l’actualitat.
   - Inclou les lectures de diferents variables a diverses estacions meteorològiques.

## Transformació del Joc de Dades

Per adaptar aquests sets de dades a les necessitats del projecte, s'ha realitzat el següent:

1. **Creació de Columnes per Variables Meteorològiques**:
   - Cada variable meteorològica (26 en total) es troba en una columna separada.
   - Cada fila representa el registre d'aquestes variables en una data i estació concreta.

2. **Informació Addicional de les Estacions**:
   - S'han afegit columnes amb informació rellevant de les estacions meteorològiques, com ara el nom, la latitud, la longitud, i l'altitud.

3. **Filtrat de Dades**:
   - S'han seleccionat les lectures i registres des de 2019 fins a l’actualitat.
   - Només s'han considerat les dades de les estacions meteorològiques situades a Barcelona, que estiguessin operatives des d'abans de 2019.

## Estacions Seleccionades

S'han seleccionat 4 estacions meteorològiques de la XEMA a Barcelona que compleixen les característiques esmentades. S'han obtingut les dades des de 2019 fins a l'actualitat d'aquestes estacions.

## Fitxers Descarregats

1. **Metadades variables meteorològiques**:
   - Conté informació sobre totes les variables.

2. **Metadades estacions meteorològiques**:
   - Fitxer filtrat per les 4 estacions d'interès.

3. **Dades meteorològiques**:
   - Conté les dades i lectures des de 2019 fins a l'actualitat de les 4 estacions seleccionades.

## Indicadors Addicionals

Per aprofundir en l'anàlisi, s'han creat diversos indicadors:

1. **Indicador de Temperatura Extrema**:
   - Detecta temperatures menors a 5 graus o majors a 35 graus.

2. **Índex de Confort Tèrmic (ITH)**:
   - Relaciona la temperatura amb la humitat relativa.

3. **Sensació Tèrmica**:
   - Basada en el valor de l'ITH obtingut, es divideix en 4 categories:
     - Còmode (ITH menor a 50)
     - Incòmode (ITH superior a 50 i menor a 60)
     - Molt Incòmode (ITH major a 60 i menor a 70)
     - Extremadament Incòmode (ITH major a 70)



# Fitxer final

El dataset generat resultant per a generar la visualització es pot trobar a la carpeta de data dins el següent enllaç: https://drive.google.com/drive/folders/108umHzyg7XmEC1YrIiyi1T15thpJMNhv?usp=sharing 
