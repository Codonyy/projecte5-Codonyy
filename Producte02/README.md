# P02 – Llicenciament Windows Server 2025

## Breu descripció
Mentre inicieu la vostra aventura emprenedora, cal seguir pagant factures. Gràcies a la bona feina realitzada a EverPia, els responsables de la consultora us deriven un nou encàrrec d’un client que necessita suport especialitzat en llicenciament de sistemes Microsoft.

L’objectiu d’aquesta tasca és analitzar i justificar correctament el **model de llicenciament de Windows Server 2025** per a una infraestructura virtualitzada.

---

## Introducció al client
**TransLògic S.A.** és una empresa dedicada a la logística regional que vol renovar la seva infraestructura IT.

Actualment disposen d’un servidor físic antic que ha quedat obsolet i volen:
- Virtualitzar tota la càrrega de treball
- Millorar la disponibilitat dels serveis
- Preparar la infraestructura per a creixement futur

---

## Detalls de la infraestructura

### Servidor físic (Host)
- 1 servidor físic
- 2 CPUs
- 12 nuclis físics per CPU
- **Total de nuclis:** 24 cores

---

### Càrrega de treball (Màquines Virtuals)
Totes les màquines virtuals utilitzen **Windows Server 2025**:

- 1 VM – Controlador de Domini (Active Directory)
- 1 VM – Servidor de Fitxers
- 1 VM – Servidor d’Impressores i Gestió Documental
- 1 VM – SQL Server (base de dades de l’ERP)
- 8 VMs – Aplicacions de logística i terminals de magatzem

**Total:** 12 màquines virtuals

---

### Usuaris i dispositius
- **45 empleats en total**
  - 30 treballadors d’oficina  
    - 1 PC + 1 portàtil per usuari
  - 15 mossos de magatzem  
    - Comparteixen 5 tauletes robustes
    - Treballen en 3 torns

---

## Encàrrec del client
Com a consultors informàtics, cal realitzar les tasques següents:

1. Analitzar el **model de llicenciament per nucli (core)** de Windows Server 2025.
2. Calcular el **cost total** utilitzant:
   - Windows Server 2025 **Standard**
   - Windows Server 2025 **Datacenter**
3. Determinar quin tipus de **CAL** és més econòmic:
   - User CAL
   - Device CAL
4. Justificar la decisió final tenint en compte:
   - Cost econòmic
   - Escalabilitat futura
   - Funcionalitats avançades (Storage Spaces Direct, SDN, etc.)
5. Preparar una **presentació per al client** (5–10 minuts):
   - Llenguatge clar i no tècnic
   - Orientada al gerent de TransLògic S.A.

---

## Resultat esperat
- Anàlisi clara i raonada del llicenciament
- Comparativa econòmica entre Standard i Datacenter
- Elecció justificada del tipus de CAL
- Presentació entenedora i professional per a un perfil no tècnic

---

## Materials i recursos de suport
- **UD6.AA1. Introducció a Windows Server**  
  Moodle 0224 SOX
- **Microsoft – Preus i llicències de Windows Server**  
  Documentació oficial de Microsoft
