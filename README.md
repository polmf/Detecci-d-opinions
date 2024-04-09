# Predicció de categories d'opinions - Pràctica

## Descripció del projecte

En aquest projecte, l'objectiu és desenvolupar un sistema de predicció de categories (positives o negatives) per a les opinions sobre pel·lícules utilitzant una combinació de models supervisats i no supervisats. Farem servir dades de WordNet per a les opinions sobre pel·lícules i implementarem diversos models per a la classificació.

## Models Supervisats

### 1. Preprocessament de les dades

Abans de construir els models supervisats, hem de realitzar el preprocessament de les dades. Això inclourà la tokenització, la eliminació de caràcters especials, la lemmatització i la vectorització de les paraules.

### 2. Construcció dels models

Per a aquesta part, implementarem diversos models supervisats com ara:

- **Naive Bayes:** Un model probabilístic simple que utilitza el teorema de Bayes per a la classificació.
- **SVM (Support Vector Machine):** Un algorisme que busca trobar el millor hiperpla que divideixi les dades en les categories desitjades.
- **Logistic Regression:** Un model de regressió que utilitza la funció logística per a la classificació.
- **Decision Tree:** Un model basat en la divisió recursiva de les dades en nodes per a la classificació.

### 3. Avaluació dels models

Avaluarem el rendiment de cada model utilitzant mètriques com ara precisió, recall i F1-score. Això ens ajudarà a seleccionar el millor model per a la nostra tasca de classificació d'opinions.

## Models No Supervisats

### 1. Lesk

El mètode Lesk és una tècnica de desambiguació de sentits de paraules. Farem servir aquest mètode per a la classificació de les opinions, tot intentant identificar el sentit de les paraules clau en el context de la frase.

### 2. TextServer

TextServer és una eina que permet l'anàlisi de text no supervisada. Lamentablement, hem trobat problemes d'accés als resultats degut a un error 401.

### 3. Avaluació dels resultats

Avaluarem els resultats dels models no supervisats utilitzant mètriques com ara la coherència temàtica i la similitud cosinus per a mesurar la qualitat de les agrupacions.

## Conclusió

En aquesta pràctica, hem explorat diversos mètodes tant supervisats com no supervisats per a la classificació d'opinions sobre pel·lícules. Tot i que els models no supervisats ofereixen una perspectiva interessant sobre les dades, els resultats obtinguts amb els models supervisats com Naive Bayes, SVM, Logistic Regression i Decision Tree han estat més precisos i fiables. Això suggereix que, en aquest cas particular, els models supervisats són més adequats per a la tasca de classificació d'opinions.