# T04: Instal·lació Windows Server 2025

## Breu descripció
Després del procés d’assessorament realitzat, l’empresa **TransLògic S.A.** encarrega el desplegament dels seus servidors **Windows Server 2025**.

Per garantir una implantació correcta i seguir bones pràctiques, es realitza una **instal·lació de prova** mitjançant màquines virtuals. Aquesta prova té un doble objectiu:
- Aprendre i documentar el procediment d’instal·lació.
- Crear una guia base que servirà com a documentació per a futures implantacions als sistemes del client.

---

# Introducció al cas
El projecte consisteix en el desplegament inicial d’un servidor Windows Server 2025 en entorn virtualitzat. Aquesta primera instal·lació permet validar la configuració del sistema, detectar possibles problemes i establir un procediment estàndard abans de la implantació definitiva en producció.

La guia resultant s’elaborarà en format **Markdown**, amb captures de pantalla i observacions tècniques.

---

# Procediment d’instal·lació

## Creació de la màquina virtual
Cal crear una màquina virtual amb les següents característiques:

- **Memòria RAM:** 8 GB  
- **Processadors:** 2 CPU  
- **Discos:**
  - Disc principal: 32 GB (instal·lació del sistema operatiu)
  - Disc secundari: 10 GB
- **Interfícies de xarxa:**
  - Xarxa NAT
  - Xarxa Host-only

---

## Instal·lació del sistema operatiu
Durant el procés d’instal·lació s’han de seguir les següents indicacions:

- Sistema operatiu: **Windows Server 2025**
- Mode d’instal·lació: **GUI**
- Idioma del sistema: **English (US)**
- Configuració regional i teclat: **Espanyol**
- Seleccionar el disc principal de 32 GB per a la instal·lació

---

## Configuració posterior
Un cop finalitzada la instal·lació:

- Canviar el nom de l’equip a:  
