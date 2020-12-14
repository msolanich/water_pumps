# water_pumps

## 1. Descripció del dataset. Perquè és important i quina pregunta/problema pretén respondre?

l'objecte del següent projecte cosisteix en predir quines de les següents bombes d'aigua són o no defectuoses.

A partir de les dades facilitades per Taarifa i el Ministeri d'Aigua de Tanzània, caldrà predir quines bombes són funcionals, quines necessiten algunes reparacions i quines no funcionen en absolut. Per a fer la classificació del funcionament dels pous caldrà fer-ne l'analisis a partir de les variables facilitades sobre quin tipus de bomba, quan es van instal·lar i com es gestiona.

El següent estudi permetrà coneixer i predir quins punts d'aigua fracassaran i permetrà millorar les operacions de manteniment i assegurar que l'aigua potable i neta estigui disponible per a les comunitats de Tanzània.


El projecte descrit forma part de la competició activa a a la plataforma "DrivenData.org" (DrivenData.org)

Per a realitzar els següent estudi es faciliten 4 fitxers 'csv':
- Submission format: El format per enviar les vostres prediccions
- Test set values: Les variables independents que necessiten prediccions
- Training set labels: La variable dependent (status_group) de cadascuna de les files dels valors del conjunt d'entrenament
- Training set values: Les variables independents del conjunt d'entrenament

Descripció dels camps:

Fitxers 'SubmissionFormat.csv' i 'training_set_lablels.csv' contenten els següents camps:
- **id**: Codi identificador de cada pou
- **status_group**: Estat del funcionament de cada pou

Fitxers 'test_set_values.csv' i 'training_set_lablels.csv' contenten els següents camps:
- **id**: Codi identificador de cada pou
- **amount_tsh**: Quantitat d'aigua disponible a cada pou (Total static head)
- **date_recorded**: Data en que s'ha creat el registre
- **funder**: Qui a financiat el pou
- **gps_height**:  altitud del pou GPS
- **installer**: Organitzacio que va instal·lar el pou
- **longitude**: Coordenada longitud GPS
- **latitude**: Coordenada latitud GPS
- **wpt_name**: Nom del punt d'aigua (si n'hi ha)
- **num_private**: Conca hidrogràfica
- **basin**: Localització conca hidrogràfica
- **subvillage**: Localització geogràfica
- **region**: Ubicació geogràfica de la regió
- **region_code**: Codi ubicació geogràfica de la regió
- **district_code**: Codi ubicació geogràfica del districte
- **lga**: Localització geogràfica
- **ward**: Localització geogràfica
- **population**: Població al voltant del pou
- **public_meeting**: cert / fals
- **recorded_by**: Grup que introdueix aquesta fila de dades
- **scheme_management**: Qui opera el punt d’aigua
- **scheme_name**: Qui opera el punt d’aigua
- **permit**: Si es permet el punt d'aigua
- **construction_year**: Any en què es va construir el punt d'aigua
- **extraction_type**: Tipus d’extracció que fa servir el punt d’aigua
- **extraction_type_group**: Tipus d’extracció que fa servir el punt d’aigua
- **extraction_type_class**: Tipus d’extracció que fa servir el punt d’aigua
- **management**: Com es gestiona el punt d’aigua
- **management_group**: Com es gestiona el punt d’aigua
- **payment**: Què costa l'aigua
- **payment_type**: El que costa l'aigua
- **water_quality**: Qualitat de l'aigua
- **quality_group**: Qualitat de l'aigua
- **quantity**: Quantitat d'aigua
- **quantity_group**: Quantitat d'aigua
- **source**: Font de l'aigua
- **source_type**: Font de l'aigua
- **source_class**: Font de l'aigua
- **waterpoint_type**: Tipus de punt d’aigua
- **waterpoint_type_group**: Tipus de punt d’aigua


## 2. Integració i selecció de les dades d’interès a analitzar.


## 3. Neteja de les dades.
#### 3.1. Les dades contenen zeros o elements buits? Com gestionaries aquests casos?

Com podem observar hi ha camps que contenen zeros i/o elements buits. En aquests casos cal que determinem si aquesta dada es degut a un error en el moment de la obtenció o introducció del camp o en el cas del zero es un valor legitim.
Es per això que cal que entenguem en que consisteix cada camp. 

(FALTA)



#### 3.2. Identificació i tractament de valors extrems.


## 4. Anàlisi de les dades. 

#### 4.1. Selecció dels grups de dades que es volen analitzar/comparar (planificació dels anàlisis a aplicar).


#### 4.2. Comprovació de la normalitat i homogeneïtat de la variància.


#### 4.3. Aplicació de proves estadístiques per comparar els grups de dades. En funció de les dades i de l’objectiu de l’estudi, aplicar proves de contrast d’hipòtesis, correlacions, regressions, etc. Aplicar almenys tres mètodes d’anàlisi diferents.


## 5. Representació dels resultats a partir de taules i gràfiques.


## 6. Resolució del problema. A partir dels resultats obtinguts, quines són les conclusions? Els resultats permeten respondre al problema?


## 7. Codi: Cal adjuntar el codi, preferiblement en R, amb el que s’ha realitzat la neteja, anàlisi i representació de les dades. Si ho preferiu, també podeu treballar en Python. 
