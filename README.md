# Apunts_UF1_1

# ENTORNS DE DESENVOLUPAMENT

## Tipus de software
  - de Sistema (S.O, drivers)
  - d’Aplicació (Suite ofimàtica, Navegador, Edició d'imatge, etc..)
  - de Desenvolupament (Editors, compiladors, intèrprets, etc...)

## Relació hardware-software
  - **Disc dur:** Emmagatzema dades de forma permanent.  
  - **RAM:** Emmagatzema temporalment el codi binari dels arxius i arrenca l’ordinador.
  - **CPU:** Llegeix i et permet executar les instruccions emmagatzemades a la RAM.  
  - **Entrada/Sortida (E/S):** Permet ingresar o emetre informació.  
  <img src="https://user-images.githubusercontent.com/74070913/98411287-11b16400-2076-11eb-8ff4-13a1315fd11f.jpg" alt="Img-Disc-Dur" width="50"/><img src="https://user-images.githubusercontent.com/74070913/98577611-7eb63b00-22bc-11eb-8305-dd0d7d896042.jpg" alt="Img-RAM" width="50"/><img src="https://user-images.githubusercontent.com/74070913/98577141-ce483700-22bb-11eb-827d-093e06233815.jpg" alt="Img-CPU" width="50"/><img src="https://user-images.githubusercontent.com/74070913/98577714-a1e0ea80-22bc-11eb-8d9c-b9879711b946.jpg" alt="Img-CPU" width="50"/>  
El disc dur està relacionat amb el emmagatzematge.  
La RAM està relacionada amb el computador i emmagatzematge.  
El CPU està relacionat amb el computador.  
El E/S està relacionat amb l’execució de software  

## Tipus de codi
  - **Codi font:** arxiu de text llegible escrit en un llenguatge de programació. 
    Ex: C, Java, Python...
  - **Codi objecte:** arxiu binari no executable. El codi resultant de la compilació del codi font. Codificat en codi màquina.
  - **Codi executable:** arxiu binari executable. Quan l’ordinador pot realitzar les instruccions compilades.

## Desenvolupament de software
### Fases principals
  - **Anàlisi:** Comprendre i determinar les necessitats del client per especificar els requisits que ha de complir el software.
  - **Disseny:** Organitza el sistema en elements components que poden ser desenvolupats per separat. Es preparen totes les funcionalitats necessàries per a complir els requeriments detectats en l'anàlisi.
  - **Codificació:** S’escriu el codi font de cada component.
  - **Proves:** Sotmetre el programa a diferents situacions per detectar errors.
  - **Manteniment:** Mantenir i millorar el software per enfrontar errors descoberts. S’ha de realitzar canvis.  
  Tipus:
      - Correctiu: es corregeixen defectes
      - Perfectiu: es millora la funcionalitat
      - Evolutiu: s’afegeixen noves funcionalitats
      - Adaptatiu: s’adapta a nous entorns

### Models de desenvolupament de software
 - Models clàsics (predictius)
    - Model en cascada 
    - Model en V
  - Model de construcció de prototius
  - Models evolutius o incrementals
    - Model en espiral (iteratius)
    - Metodologies àgils (adaptatius)

#### Model en cascada
  -  Las fases es realitzan en el ordre indicat.
  -  El resultat d'una fase és la entrada de la següent.
  -  És un model bastant rígid que s'adapta malament a el canvi continu d'especificacions.
<img src="https://user-images.githubusercontent.com/74070913/98579016-5b8c8b00-22be-11eb-9680-ecb39dc989b6.png" alt="Model-cascada" width="1000"/>
![Captura de pantalla de 2020-11-09 19-03-45](https://user-images.githubusercontent.com/74070913/98579016-5b8c8b00-22be-11eb-9680-ecb39dc989b6.png)

#### Model en V
  -  Semblant al model en cascada.
  -  Visió jerarquitzada amb diferents nivells.
  -  Els nivells superiors indiquen major abstracció i els inferiors major nivell de detall.
  -  El resultat d'una fase és l'entrada de la següent fase.

#### Prototips  
Els requisits no estan especificats clarament durant la fase d'anàlisi. Llavors es crea un prototip i és provat per refinar els requisits de programari a desenvolupar.
Tipus: 
  -  **Prototips ràpids**
  El prototip es rebutja.
  -  **Prototips evolutius**
  El prototip es fa servir com a base per desenvolupar el projecte.
![image](https://user-images.githubusercontent.com/74070913/101241871-43abf980-36fa-11eb-9d3a-6f4088cc030b.png)

#### Model en espiral
La activitat d'enginyeria correspon a les fases dels models clàssics: anàlisi, disseny, codificació,... 
I es dóna gran importància a la reutilització de codi
![image](https://user-images.githubusercontent.com/74070913/101242706-6b4f9180-36fb-11eb-90c7-237b41a9a706.png)

### Metodoloies àgils
  -  Són mètodes d'enginyeria de programari basats en el desenvolupament iteratiu i incremental.
  -  Els requisits i solucions evolucionen amb el temps segons la necessitat de el projecte.
  -  Les metodologies més utilitzades són:  
      - Kanban
      - Scrum
      - XP (eXtreme Programming)

## Llenguatges de programació

### Tipus
Segons la forma en la que operan:
  -  Llenguatge declaratiu: Indica el resultat sense especificar els passos, utilitza automàticament els mètodes adequats.  
  Es centra en el “que”.
  Ex: Prolog, SQL.
  -  Llenguatge imperatiu: Descriu els passos a seguir per obtenir el resultat.  
  Es centra en el “com”.
  Ex: C, Java.

Segons el nivell d'abstracció:
  -  Baix nivell: assemblador
  -  Medi nivell: C
  -  Alt nivell: C ++, Java

### Obtenció de codi executable
  -  **Compilats:** Transforma el codi font d’un programa a un altre llenguatge de baix nivell.
                    Execució molt eficient.
                    Cal compilar cada vegada que el codi font és modificat.
                    Ex: C, C++.
  -  **Interpretats:** Executa directament les instruccions escrites.
                    El codi font s'interpreta directament.
                    Execució menys eficient.
                    Ex: PHP, JavaScript.

### Evolució
  -  Codi binari
  -  Assemblador
  -  Llenguatges estructurats
  -  Llenguatges orientats a objectes

### Criteris per a la selecció d'un llenguatge
  -  Camp d'aplicació
  -  Experiència prèvia
  -  Eines de desenvolupament
  -  Documentació disponible
  -  Base d'usuaris
  -  Reusabilitat
  -  Portabilitat
  -  Imposició de el client
