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

<img src="Contraseña.png" alt="Comvocatoria">

**2.** Crea els següents cursos: un curs anomenat A que estigui format per 3 temes i un altre anomenat B que estigui format per 5 temes.

  **Curs A** 

El curs **A** s'haura de crea de la mateixa manera que el **B**

  **Curs B**
 <img src="CB.png" alt="Comvocatoria">

**3.** Vés a algun dels cursos creats al punt anterior i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema.

 <img src="PDF.png" alt="Comvocatoria">

**4.** Creació d’usuaris i alumnes. 
   
   **A)** Crea manualment un usuari anomenat `Bob` que ha de fer servir el **mètode d'autenticació manual**. 

 <img src="Bob1.png" alt="Comvocatoria">

 <img src="Bob2.png" alt="Comvocatoria">

 <img src="Bob3.png" alt="Comvocatoria">
 
   **B)** Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc.

**Paso 1**
 <img src="SPaso1.png" alt="Comvocatoria">

**Paso 2**   
 <img src="SPaso2.png" alt="Comvocatoria">

   **C)** Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció `Administració del lloc > Usuaris > Accions amb usuaris en bloc`
 
 <img src="B1.png" alt="Comvocatoria">

**5.** Ara matricula aquests usuaris als diferents cursos.

**Paso 1**
<img src="Paso1.png" alt="Paso1.png">

**Paso 2**
<img src="Paso2.png" alt="Paso2.png">

**Paso 3**
<img src="Paso3.png" alt="Paso3.png">
 
**Configuracio cursos**
  
   **A)** Fes que al curs B no hi hagi possibilitat d'inscripccio. 
  
  **Resultado final**
    <img src="CPaso2.png" alt="Paso3.png">
   
   **B)** D'altra banda, fes que al curs A es necessiti registre manual d'usuaris 

   **C)** Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV.

   <img src="PPaso1.png" alt="Paso3.png">

   **D)** Comprova el contingut del curs A.

   <img src="CAPaso1.png" alt="Paso3.png">

**6.** Canvia l'aparença estètica del teu lloc.

<img src="APPaso1.png" alt="Paso3.png">

**7.** Assigna un professor i matricula alumnes al curs A.

<img src="PRPaso1.png" alt="Paso3.png">

### Continguts

En el curs A crea una UF amb 2 NF dintre. En aquesta UF crea diverses activitats.

 <img src="NF.png" alt="Comvocatoria">

### Qualificació
Crea una insignia i atorga-la a aquest alumnel.

 <img src="Insignia1.png" alt="Comvocatoria">

 <img src="Insignia2.png" alt="Comvocatoria">

 <img src="Insignia3.png" alt="Comvocatoria">

 <img src="Insignia4.png" alt="Comvocatoria">

  
## Qüestionaris
Crea un qüestionari i afegeix preguntes del banc de preguntes. Crea diferents categories dintre del banc de preguntes i diverses preguntes en cada categoria. 

Per crea el Qüestionari el que hi haura que fer es el mateix pas que al'hora de crea una Tasca pero le dones a Qüestionari

A l'hora de crear el qüestionari has de seleccionar les preguntes del banc de preguntes. Respon les preguntes del qüestionari amb un usuari estudiant i mira les qualificacions amb l'usuari professor.

<img src="BPregutas1.png" alt="Comvocatoria">

<img src="BPregutas2.png" alt="Comvocatoria">

<img src="BPregutas3.png" alt="Comvocatoria">


## Seguretat
Baneja una IP i aplica una política de seguretat. Pots posar la que vulguis però l’hauràs de justificar.

Hi haura que aplica els passos que es mostren a la dreta de la imatge
 <img src="IP.png" alt="Comvocatoria">

