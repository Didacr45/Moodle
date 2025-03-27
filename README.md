# Moodle

# Pràctica UF4 - Instal·lació i configuració de moodle
## Objectius generals de la pràctica
* Instal·lar i configurar gestors de continguts, concretament `moodle`.

## Com fer la instalaccio

En aquest repositori veureu com es pot fer la instalaccio de **Moodle**

## Configuració

**1.** Inicia sessió al teu **Moodle** com administrador per arribar a podre editar tots els apartats del **Moodle**
  
   **A)** Comprova que la franja horària del teu lloc sigui la correcta. Això es pot fer anant a l'opció `Administració del lloc > Ubicació > Paràmetres`.
   
  Aquesta configuració sera importat al'hora de crear tasques amb data de venciment
   
   **B)** Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. 

**2.** Crea els següents cursos: un curs anomenat A que estigui format per 3 temes i un altre anomenat B que estigui format per 5 temes.

  **Curs A** 

  **Curs B**

**3.** Vés a algun dels cursos creats al punt anterior i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema.


**4.** Creació d’usuaris i alumnes. 
   
   **A)** Crea manualment un usuari anomenat `Bob` que ha de fer servir el **mètode d'autenticació manual**. 

 <img src="comvocatoria.jpg" alt="Comvocatoria">
   
   **B)** Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc.

**Paso 1**
 <img src="SPaso1" alt="Comvocatoria">

**Paso 2**   
 <img src="SPaso2" alt="Comvocatoria">

   **C)** Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció `Administració del lloc > Usuaris > Accions amb usuaris en bloc`
 
 <img src="comvocatoria.jpg" alt="Comvocatoria">

**5.** Ara matricula aquests usuaris als diferents cursos.

**Paso 1**
<img src="Paso1.png" alt="Paso1.png">

**Paso 2**
<img src="Paso2.png" alt="Paso2.png">

**Paso 3**
<img src="Paso3.png" alt="Paso3.png">
 
**Configuracio cursos**
   **A)** Fes que al curs A no hi hagi possibilitat. 
   
   **B)** D'altra banda, fes que al curs B es necessiti registre manual d'usuaris 

   **C)** Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV.

   **D)** Comprova el contingut del curs A.

**6.** Canvia l'aparença estètica del teu lloc.

**7.** Assigna un professor i matricula alumnes al curs A.

**8.** Amb el professor afegeix contingut al curs A. Afegeix diferents tipus d’activitats i recursos. Crea una tasca amb data d’entrega oberta que demani la càrrega d’un fitxer PDF.

**9.** Entra amb un alumne i comprova que pots lliurar la tasca.


### Continguts

En el curs A crea una UF amb 2 NF dintre. En aquesta UF crea diverses activitats.

### Qualificació
En el curs A fes que un alumne completi totes les tasques evaluables. Calificales amb el professor i configura el calificador per a que doni una nota de la UF automàticament a `Administració del Curs > Configuració de qualificacions`.

Crea una insignia i atorga-la a aquest alumnel.

## Qüestionaris
Crea un qüestionari i afegeix preguntes del banc de preguntes. Crea diferents categories dintre del banc de preguntes i diverses preguntes en cada categoria. 

A l'hora de crear el qüestionari has de seleccionar les preguntes del banc de preguntes. Respon les preguntes del qüestionari amb un usuari estudiant i mira les qualificacions amb l'usuari professor.

## Seguretat
Baneja una IP i aplica una política de seguretat. Pots posar la que vulguis però l’hauràs de justificar.


