# T03: Serveis de Transferència de Fitxers

## Breu descripció
Al llarg de la vostra experiència a EverPia heu configurat serveis fonamentals com DHCP, DNS i sistemes de connexió i administració remota dels equips. Ara, iniciant el vostre camí professional de manera més autònoma, és necessari ampliar coneixements i dominar altres serveis essencials.

Tot i que actualment els serveis de núvol com Dropbox o Google Drive són molt utilitzats, és imprescindible conèixer i dominar els **protocols fonamentals de transferència de fitxers**. Per aquest motiu, us inscriviu en una formació orientada a convertir-vos en experts en aquest àmbit.

---

## Introducció a la tasca
Aquesta formació se centra en l’estudi i la implementació de serveis de transferència de fitxers, posant especial atenció a la **seguretat**, ja que en entorns professionals la transferència de dades és un punt crític.

L’objectiu és entendre no només el funcionament dels protocols, sinó també els riscos associats i les mesures necessàries per garantir comunicacions segures.

---

## Objectius de la formació
En finalitzar la formació, haureu de ser capaços de respondre amb fets i configuracions reals a les següents qüestions:

- Com funciona el protocol FTP.
- Diferències entre el mode actiu i el mode passiu.
- Implementació d’un servidor FTP segur.
- Ús del protocol sFTP com a alternativa al FTP tradicional.
- Engabiament d’usuaris en connexions sFTP.
- Altres mètodes alternatius per a la transferència de fitxers.

---

## Pla de treball
Aquesta formació es divideix en dues parts clarament diferenciades: la part teòrica i la implementació pràctica.

---

## 1. Fonaments Teòrics i Seguretat
Estudi dels protocols **FTP** i **sFTP**, posant especial atenció a:
- Funcionament del mode actiu i passiu del FTP.
- Engabiament (chroot) d’usuaris.
- Aspectes de seguretat associats a cada protocol.
- Riscos de la transferència de dades sense xifrar.

---

## 2. Laboratori Pràctic (The "Real World")
Aplicació pràctica dels coneixements mitjançant màquines virtuals, configurant dos entorns diferenciats.

### Activitat A: Servidor FTP
- Configuració d’un servidor FTP estàndard.
- Creació d’usuaris.
- Engabiament (chroot) dels usuaris.
- Assignació de permisos de lectura i escriptura.
- Anàlisi de la transferència de dades sense xifratge.

---

### Activitat B: Servidor sFTP (Secure FTP)
- Implementació de la transferència de fitxers sobre SSH.
- Configuració d’un entorn sFTP segur.
- Engabiament d’usuaris per evitar fuites de seguretat.
- Verificació de la connexió segura des d’un client extern.

---

## Nota important
Com a administradors de sistemes, **la seguretat no és una opció, és una obligació**. Entendre les diferències entre FTP i sFTP és fonamental per al vostre futur professional.

---

## Sistema d’avaluació
Per superar la formació, cal demostrar la competència mitjançant dos formats:

### Prova escrita (40%)
- Preguntes sobre protocols.
- Ports utilitzats.
- Modes de connexió.
- Conceptes teòrics de seguretat.

### Examen pràctic (60%)
- Repte de configuració cronometrat.
- Creació des de zero d’un servidor FTP i un servidor sFTP.
- Configuració d’usuaris amb permisos específics.
- Verificació de la connexió des d’un client extern.

---

## Preparació de l’entorn
Prepareu les màquines virtuals i els entorns de proves.  
**Comencem a transferir dades!**
