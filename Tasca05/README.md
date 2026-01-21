# T05: Instal·lació del Domini (Active Directory)

## Breu descripció
Aquesta tasca és la continuació directa de la instal·lació de Windows Server. L’objectiu és desplegar **Active Directory Domain Services (AD DS)** sobre la màquina virtual per practicar el procediment abans de la implantació real al client **TransLògic**.

Aquest desplegament servirà també com a **Prova de Concepte (PoC)** per presentar als responsables del client i permetrà ajustar les configuracions a les necessitats reals de l’empresa.

---

## Introducció
El directori actiu és un component essencial en entorns empresarials basats en Windows. En aquesta tasca es crea un domini complet en un bosc nou, establint els nivells funcionals adequats i documentant tot el procés amb l’objectiu de generar una guia reutilitzable.

La documentació resultant formarà part del repositori del projecte.

---

## Procediment a documentar

### Instal·lació dels rols
- Instal·lar els rols necessaris per al desplegament d’Active Directory.
- Verificar que el servidor compleix els requisits previs.

---

### Creació del domini
- Crear un **domini nou en un bosc nou** amb el nom:
  
  translogicXX.test
  
  *(on `XX` correspon al número de llista)*

- Establir el **nivell funcional del domini** a **Windows Server 2025**.

---

### Promoció del servidor a Controlador de Domini
- Promocionar el servidor com a **Domain Controller (DC)**.
- Documentar especialment la **pantalla resum final** del procés.
- Verificar el correcte funcionament del domini després del reinici.

---

### Automatització amb PowerShell
- Gravar en un fitxer l’**script de PowerShell** que permet automatitzar:
  - La instal·lació dels rols.
  - La creació del domini.
  - La promoció del servidor a controlador de domini.

---

### Còpia de l’script al repositori
Un cop finalitzat tot el procediment, copiar l’script PowerShell a la carpeta del repositori utilitzat mitjançant algun dels següents mètodes:
- Còpia mitjançant dispositiu USB.
- Enviament a través d’Internet (correu electrònic, Google Drive o serveis similars).
- Còpia mitjançant `scp` (cal instal·lar el servei SSH a Windows Server).

---