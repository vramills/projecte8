# Tasca 01 – Dossier de Projecte Tècnic
## Client 4: "Fruits de la terra"

**Data:** Maig 2026  
**Grup:** Christian Bogdanas, Pol Castaño i Víctor Rodríguez

---

## Índex

1. [Descripció del client](#1-descripció-del-client)
2. [Anàlisi de l'estat actual](#2-anàlisi-de-lestat-actual)
3. [Definició d'objectius](#3-definició-dobjectius)
4. [Informe de Connectivitat](#4-informe-de-connectivitat)
5. [Inventari de Hardware "Tot Terreny"](#5-inventari-de-hardware-tot-terreny)
6. [Disseny del Quadern de Camp Digital](#6-disseny-del-quadern-de-camp-digital)
7. [Comparativa de Software](#7-comparativa-de-software)
8. [Dilema: Programari Local vs. Núvol](#8-dilema-programari-local-vs-núvol)
9. [Pressupost "Claus en Mà"](#9-pressupost-claus-en-mà)
10. [Conclusions](#10-conclusions)

---

## 1. Descripció del client

**"Fruits de la terra"** és una explotació agrícola familiar situada en zona rural que vol modernitzar la seva gestió incorporant tecnologia digital. Els seus objectius principals són:

- Substituir la documentació en paper per eines digitals.
- Implementar traçabilitat dels productes des del camp fins al punt de venda.
- Convertir-se en un referent de sostenibilitat i innovació al sector primari.

**Reptes específics del client:**
- Ubicació rural sense connexió a internet preinstal·lada.
- Necessitat de treballar al camp en condicions adverses (sol, pols, humitat).
- Pressupost limitat, propi d'una petita explotació agrícola.
- Poca experiència tecnològica del personal.

---

## 2. Anàlisi de l'estat actual

| Àmbit                         | Situació actual             | Problema detectat                                |
| ----------------------------- | --------------------------- | ------------------------------------------------ |
| **Connectivitat**             | Sense internet              | No es pot usar cap eina digital en línia         |
| **Gestió documental**         | Llibretes de paper          | Risc de pèrdua, no compartible, no buscable      |
| **Tractaments fitosanitaris** | Apuntats a mà               | Dificultat de traçabilitat i compliment normatiu |
| **Regs**                      | Control manual o de memòria | Ineficiència i risc de pèrdues de collita        |
| **Hardware**                  | Sense equipament específic  | Cal definir tot l'inventari des de zero          |
| **Còpies de seguretat**       | Inexistents                 | Risc de pèrdua total d'informació                |

---

## 3. Definició d'objectius

### Objectius a curt termini (0–3 mesos)
- Establir connexió a internet fiable al magatzem i a l'oficina.
- Adquirir l'equipament hardware necessari.
- Posar en marxa el quadern de camp digital.

### Objectius a mig termini (3–12 mesos)
- Tenir traçabilitat completa dels productes (des del camp fins al client).
- Implementar registre digital de tots els tractaments fitosanitaris i regs.
- Formar el personal en les eines seleccionades.

### Objectius a llarg termini (> 1 any)
- Obtenir certificació de sostenibilitat (p. ex., GlobalG.A.P.) gràcies a la traçabilitat digital.
- Optimitzar els consums d'aigua i fitosanitaris mitjançant l'anàlisi de dades.

---

## 4. Informe de Connectivitat

Atès que la finca no disposa de connexió a internet preinstal·lada, s'han analitzat tres alternatives tecnològiques.

### 4.1 Comparativa de tecnologies d'accés

| Criteri                     | Starlink (Satèl·lit)                | Ràdio-enllaç                       | 4G/5G Rural                      |
| --------------------------- | ----------------------------------- | ---------------------------------- | -------------------------------- |
| **Velocitat baixada**       | 100–250 Mbps                        | 10–100 Mbps                        | 20–150 Mbps                      |
| **Velocitat pujada**        | 10–20 Mbps                          | 5–50 Mbps                          | 10–50 Mbps                       |
| **Latència**                | 25–60 ms                            | 5–30 ms                            | 30–80 ms                         |
| **Fiabilitat**              | Alta (pot baixar amb pluja intensa) | Molt alta                          | Dependent de cobertura           |
| **Instal·lació**            | Senzilla (DIY possible)             | Requereix professional             | Molt senzilla                    |
| **Cost instal·lació**       | ~500 € (kit)                        | 800–2.000 €                        | 50–150 € (router 4G)             |
| **Quota mensual**           | ~55–100 €/mes                       | 30–80 €/mes                        | 20–50 €/mes                      |
| **Disponibilitat en rural** | Universal (tot el territori)        | Limitada (necessita visió directa) | Dependent de cobertura operadora |
| **Dependència de tercers**  | Baixa                               | Baixa                              | Alta (operadora)                 |

### 4.2 Recomanació

**Recomanem Starlink** com a primera opció per als motius següents:

- Cobertura universal, independent de la ubicació geogràfica de la finca.
- Instal·lació senzilla que el mateix client pot fer sense tècnic.
- Velocitat suficient per a totes les aplicacions previstes (quadern digital, còpies de seguretat al núvol, videotrucades).
- Sense compromís de permanència.

**Com a alternativa econòmica**, si hi ha cobertura 4G suficient de Movistar, Orange o Vodafone, un router 4G extern (p. ex., Huawei B818) representa la solució més econòmica a curt termini.

### 4.3 Anàlisi de costos de connectivitat (5 anys)

| Solució                   | Instal·lació | Quota mensual | Cost total 5 anys |
| ------------------------- | ------------ | ------------- | ----------------- |
| **Starlink Standard**     | 499 €        | 55 €/mes      | 3.799 €           |
| **Ràdio-enllaç**          | 1.500 €      | 50 €/mes      | 4.500 €           |
| **Router 4G (SIM dades)** | 150 €        | 30 €/mes      | 1.950 €           |

> **Nota:** El router 4G és la solució més econòmica, però cal verificar la cobertura a la ubicació exacta de la finca abans de decidir.

---

## 5. Inventari de Hardware "Tot Terreny"

### 5.1 Equipament d'oficina

| Component                     | Model recomanat                    | Preu aprox. | Justificació                           |
| ----------------------------- | ---------------------------------- | ----------- | -------------------------------------- |
| **Ordinador sobretaula**      | Intel NUC 13 Pro o similar mini-PC | 400–600 €   | Compacte, fiable, baix consum elèctric |
| **Monitor**                   | LG 24MK430H (24", Full HD)         | 130 €       | Suficient per a gestió agrícola        |
| **Teclat + ratolí**           | Kit sense fils Logitech MK270      | 30 €        | Còmode i econòmic                      |
| **SAI (Protecció elèctrica)** | APC Back-UPS 700VA                 | 90 €        | Protecció contra talls de llum         |
| **Disc dur extern (Backup)**  | WD Elements 4TB                    | 80 €        | Còpies de seguretat locals             |
| **Router/Switch**             | TP-Link Archer AX23                | 60 €        | Distribució de la connexió             |

**Estratègia de còpies de seguretat (Backup 3-2-1):**
- **3** còpies de les dades.
- En **2** suports diferents (disc extern + núvol).
- **1** còpia fora de les instal·lacions (núvol: Google Drive o Nextcloud).

Backup automàtic setmanal amb programari gratuït (Veeam Agent Free per a Windows, o `rsync` si s'usa Linux).

### 5.2 Dispositius mòbils per al camp

| Component                 | Model recomanat                                           | Preu aprox. | Justificació                                                   |
| ------------------------- | --------------------------------------------------------- | ----------- | -------------------------------------------------------------- |
| **Tablet rugeritzada**    | Samsung Galaxy Tab Active5                                | 500–650 €   | Certificació MIL-STD-810H, IP68, pantalla llegible sota el sol |
| **Alternativa econòmica** | Tablet estàndard + funda militar (p. ex., Catalyst o UAG) | 250–400 €   | Protecció equivalent a menor cost                              |
| **Pantalla**              | Mín. 800 nits de lluminositat                             | —           | Llegible sota llum solar directa                               |
| **Bateria**               | Mín. 7.000 mAh                                            | —           | Autonomia per a jornada completa de camp                       |
| **Bateria externa**       | Anker PowerCore 20.000 mAh                                | 45 €        | Reforç per a jornades llargues                                 |

**Recomanació final per al camp:** Si el pressupost és ajustat, una tablet Samsung Galaxy Tab A9+ (pantalla brillant, resistència accepteable) amb funda Catalyst Waterproof és una opció a ~300 € que cobreix el 90% de les necessitats.

---

## 6. Disseny del Quadern de Camp Digital

El quadern de camp digital ha de substituir la llibreta de paper i permetre registrar des del camp:

- Tractaments fitosanitaris (producte, dosi, data, parcel·la, operari).
- Regs (durada, volum, dates).
- Incidències i observacions.
- Collites (quantitat, qualitat, parcel·la).

### 6.1 Requisits funcionals

- Accessible des de tablet al camp (app mòbil o web responsive).
- Funcionament **offline** (sincronització quan hi hagi connexió).
- Exportació de registres per a inspeccions i traçabilitat.
- Interfície senzilla (el personal pot tenir poca experiència tecnològica).

### 6.2 Opcions de programari analitzades

**Opció A – Agroptima (SaaS comercial):**
- App mòbil iOS/Android molt intuïtiva.
- Registre de tractaments fitosanitaris, regs i quadern de camp.
- Traçabilitat integrada.
- Preu: ~25–40 €/mes.

**Opció B – Odoo (Programari lliure + mòdul agrícola):**
- ERP complet amb mòduls de gestió agrícola.
- Major control de les dades (allotjat en servidor propi o VPS).
- Requereix major configuració inicial.
- Preu: 0 € (Community) + cost de servidor (~10–20 €/mes VPS).

**Opció C – Farmbrite o similar:**
- SaaS especialitzat en gestió de granges i explotacions.
- Quadern de camp, inventari, traçabilitat.
- Preu: ~30–50 €/mes.

---

## 7. Comparativa de Software

| Criteri                       | Odoo Community (Lliure)          | Agroptima (SaaS)          | Farmbrite (SaaS)          |
| ----------------------------- | -------------------------------- | ------------------------- | ------------------------- |
| **Cost llicència**            | 0 €                              | ~30 €/mes                 | ~40 €/mes                 |
| **Cost servidor/allotjament** | 10–20 €/mes (VPS)                | Inclòs                    | Inclòs                    |
| **Control de les dades**      | Total (servidor propi)           | Parcial (empresa tercera) | Parcial (empresa tercera) |
| **Facilitat d'ús**            | Mitja-baixa (requereix formació) | Alta                      | Alta                      |
| **App mòbil**                 | Sí (limitada offline)            | Sí (offline)              | Sí (offline)              |
| **Funcionament offline**      | Limitat                          | Sí                        | Sí                        |
| **Traçabilitat**              | Sí (amb configuració)            | Sí (integrada)            | Sí (integrada)            |
| **Manteniment**               | Responsabilitat pròpia           | Inclòs                    | Inclòs                    |
| **Suport tècnic**             | Comunitat / contractar           | Inclòs                    | Inclòs                    |
| **Escalabilitat**             | Molt alta                        | Mitja                     | Mitja                     |
| **Compliment normatiu agri.** | Configurable                     | Sí (dissenyat per a això) | Sí                        |

### Recomanació de software

Per a una PIME agrícola amb poc personal tècnic, **recomanem Agroptima** com a primera opció perquè:

- Està dissenyada específicament per a explotacions agrícoles.
- L'app mòbil funciona offline (clau per a zones amb connexió inestable).
- El cost mensual és assumible i inclou suport i manteniment.
- La corba d'aprenentatge és mínima.

Odoo es recomana com a alternativa si l'explotació vol créixer i necessita un ERP complet, o si la propietat de les dades és una prioritat absoluta.

---

## 8. Dilema: Programari Local vs. Núvol

Atesa la ubicació rural de la finca, aquest és un punt crític.

### Avantatges del programari LOCAL

- Funciona **sense internet** en tot moment.
- Les dades mai surten de les instal·lacions del client.
- Sense dependència de tercers ni quotes mensuals (a llarg termini).

### Inconvenients del programari LOCAL

- Requereix manteniment tècnic intern o contractat.
- Les actualitzacions són responsabilitat del client.
- Si l'ordinador pateix una avaria, el servei s'interromp.

### Avantatges del programari al NÚVOL (SaaS)

- Accessible des de qualsevol dispositiu i ubicació.
- Actualitzacions i seguretat gestionades pel proveïdor.
- Còpies de seguretat automàtiques.
- Menor inversió inicial.

### Inconvenients del programari al NÚVOL

- **Depèn totalment de la connexió a internet.**
- Cost recurrent mensual.
- Les dades estan en servidors de tercers.

### Conclusió del dilema

**Recomanem una solució híbrida:**

1. Usar una eina SaaS (Agroptima) amb **app offline**: es treballa al camp sense internet i es sincronitza quan hi ha connexió.
2. Mantenir una còpia local de les dades crítiques (backup automàtic al disc extern).
3. Invertir en una connexió Starlink o 4G per minimitzar la dependència offline.

---

## 9. Pressupost "Claus en Mà"

### 9.1 Inversió inicial (una sola vegada)

| Concepte                                | Cost        |
| --------------------------------------- | ----------- |
| Kit Starlink Standard (antena + router) | 499 €       |
| Instal·lació i configuració Starlink    | 0 € (DIY)   |
| Mini-PC d'oficina (NUC 13 o similar)    | 500 €       |
| Monitor 24"                             | 130 €       |
| Teclat + ratolí sense fil               | 30 €        |
| SAI protecció elèctrica                 | 90 €        |
| Disc dur extern 4TB (backup)            | 80 €        |
| Router WiFi d'oficina                   | 60 €        |
| Tablet Samsung Galaxy Tab Active5       | 600 €       |
| Funda protectora addicional             | 40 €        |
| Bateria externa 20.000 mAh              | 45 €        |
| **TOTAL INVERSIÓ INICIAL**              | **2.074 €** |

### 9.2 Despeses recurrents (mensuals)

| Concepte                                      | Cost mensual |
| --------------------------------------------- | ------------ |
| Connexió Starlink Standard                    | 55 €         |
| Llicència Agroptima (quadern de camp digital) | 30 €         |
| Emmagatzematge al núvol (Google Drive 2TB)    | 10 €         |
| **TOTAL MENSUAL**                             | **95 €**     |

### 9.3 Cost total a 3 anys

|                                       | Import      |
| ------------------------------------- | ----------- |
| Inversió inicial                      | 2.074 €     |
| Despeses recurrents (36 mesos × 95 €) | 3.420 €     |
| **TOTAL 3 ANYS**                      | **5.494 €** |

### 9.4 Opció econòmica alternativa

Si el pressupost és molt ajustat, es pot optar per:

| Concepte                                           | Cost                             |
| -------------------------------------------------- | -------------------------------- |
| Router 4G (si hi ha cobertura) en lloc de Starlink | 150 € (inversió) + 30 €/mes      |
| Tablet estàndard + funda militar                   | 300 €                            |
| PC de sobretaula de gamma econòmica                | 350 €                            |
| **Total inversió alternativa**                     | **~930 €** + despeses recurrents |

---

## 10. Conclusions

El pla de transformació digital proposat per a "Fruits de la terra" aborda de forma integral les necessitats de l'explotació agrícola en tres eixos fonamentals:

**Connectivitat:** La implantació de Starlink o una solució 4G elimina la barrera principal per a la digitalització, donant accés a internet fiable en una ubicació rural sense infraestructura prèvia.

**Hardware:** L'equipament proposat combina un ordinador d'oficina robust amb una estratègia de backup 3-2-1, i dispositius mòbils rugeritzats que permeten treballar al camp en condicions adverses.

**Software:** Agroptima com a quadern de camp digital proporciona una eina especialitzada, intuïtiva i amb funcionament offline, resolent el dilema local/núvol amb una solució híbrida pràctica.

Amb una inversió inicial d'aproximadament **2.074 €** i un cost recurrent de **95 €/mes**, "Fruits de la terra" pot assolir una transformació digital completa que millori la seva eficiència operativa, garanteixi la traçabilitat dels productes i obri la porta a la obtenció de certificacions de qualitat i sostenibilitat.