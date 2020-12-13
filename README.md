# water_pumps

## 1. Descripció del dataset. Perquè és important i quina pregunta/problema pretén respondre?

l'objecte del següent projecte cosisteix en predir quines de les següents bombes d'aigua són o no defectuoses.

A partir de les dades facilitades per Taarifa i el Ministeri d'Aigua de Tanzània, caldrà predir quines bombes són funcionals, quines necessiten algunes reparacions i quines no funcionen en absolut. Per a fer la classificació del funcionament dels pous caldrà fer-ne l'analisis a partir de les variables facilitades sobre quin tipus de bomba, quan es van instal·lar i com es gestiona.

El següent estudi permetrà coneixer i predir quins punts d'aigua fracassaran i permetrà millorar les operacions de manteniment i assegurar que l'aigua potable i neta estigui disponible per a les comunitats de Tanzània.


El projecte descrit forma part de la competició activa a a la plataforma "DrivenData.org" (DrivenData.org)

Per a realitzar els següent estudi es faciliten 4 fitxers 'csv'
a. Submission format: El format per enviar les vostres prediccions
b. Test set values: Les variables independents que necessiten prediccions
c. Training set labels: La variable dependent (status_group) de cadascuna de les files dels valors del conjunt d'entrenament
d. Training set values: Les variables independents del conjunt d'entrenament

Descripció dels camps:

Fitxers 'SubmissionFormat.csv' i 'training_set_lablels.csv' contenten els següents camps:
- **id**: Codi identificador de cada pou
- **status_group**: Estat del funcionament de cada pou

Fitxers 'test_set_values.csv' i 'training_set_lablels.csv' contenten els següents camps:
- **id**: Codi identificador de cada pou
- **amount_tsh**: 
- **date_recorded**: 
- **funder**: 
- **gps_height**: 
- **installer**: 
- **longitude**: 
- **latitude**: 
- **wpt_name**: 
- **num_private**: 
- **basin**: 
- **subvillage**: 
- **region**: 
- **region_code**: 
- **district_code**: 
- **lga**: 
- **ward**: 
- **population**: 
- **public_meeting**: 
- **recorded_by**: 
- **scheme_management**: 
- **scheme_name**: 
- **permit**: 
- **construction_year**: 
- **extraction_type**: 
- **extraction_type_group**: 
- **extraction_type_class**: 
- **management**: 
- **management_group**: 
- **payment**: 
- **payment_type**: 
- **water_quality**: 
- **quality_group**: 
- **quantity**: 
- **quantity_group**: 
- **source**: 
- **source_type**: 
- **source_class**: 
- **waterpoint_type**: 
- **waterpoint_type_group**: 


## 2. Integració i selecció de les dades d’interès a analitzar.


## 3. Neteja de les dades.
#### 3.1. Les dades contenen zeros o elements buits? Com gestionaries aquests casos?

#### 3.2. Identificació i tractament de valors extrems.


## 4. Anàlisi de les dades. 

#### 4.1. Selecció dels grups de dades que es volen analitzar/comparar (planificació dels anàlisis a aplicar).


#### 4.2. Comprovació de la normalitat i homogeneïtat de la variància.


#### 4.3. Aplicació de proves estadístiques per comparar els grups de dades. En funció de les dades i de l’objectiu de l’estudi, aplicar proves de contrast d’hipòtesis, correlacions, regressions, etc. Aplicar almenys tres mètodes d’anàlisi diferents.


## 5. Representació dels resultats a partir de taules i gràfiques.


## 6. Resolució del problema. A partir dels resultats obtinguts, quines són les conclusions? Els resultats permeten respondre al problema?


## 7. Codi: Cal adjuntar el codi, preferiblement en R, amb el que s’ha realitzat la neteja, anàlisi i representació de les dades. Si ho preferiu, també podeu treballar en Python. 
