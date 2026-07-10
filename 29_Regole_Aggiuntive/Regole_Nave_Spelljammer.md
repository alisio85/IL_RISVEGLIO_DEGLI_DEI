# REGOLE NAVE SPELLJAMMER — LA FARFALLA STELLARE

Sistema completo per il combattimento, la gestione e i viaggi della Farfalla Stellare. Integra e espande le regole base in [[18_Ship_Upgrades/La_Farfalla_Stellare.md]].

**Riferimento rapido:** [[18_Ship_Upgrades/La_Farfalla_Stellare.md|Scheda Nave]], [[01_Introduzione/Regole_Speciali.md#3. VIAGGIO SPELLJAMMER|Regole Base]]

---

## 1. STATISTICHE DELLA NAVE

### Farfalla Stellare (Base)

| Statistica | Valore | Note |
|------------|--------|------|
| **PF** | 250 | Si riduce con i danni |
| **CA** | 18 | Tiro per colpire la nave |
| **Velocità (Manovra)** | 50 ft/round | In combattimento |
| **Velocità (Crociera)** | 4.5 miglia/ora | In viaggio normale |
| **Velocità (Spelljammer)** | 100M miglia/giorno | Viaggio inter-piano |
| **Equipaggio Minimo** | 3 | 1 pilota obbligatorio |
| **Equipaggio Consigliato** | 8-10 | Pilota + navigatori + artiglieri |
| **Passeggeri Max** | 12 | Oltre all'equipaggio |
| **Armi** | 2 baliste, 2 cannoni magici | Vedi sotto |
| **Elmo** | Spelljamming (base) | Richiede 1 incantatore |
| **Stiva** | 10 slot | Per merci e equipaggiamento |
| **Valore** | 25.000 mo | Prezzo di acquisto |

### Statistiche delle Armi Nave

| Arma | Bonus | Danno | Gittata | Note |
|------|-------|-------|---------|------|
| Balista | +5 | 3d10 perforanti | 300/1200 ft | Azione: 1 attacco/round |
| Cannone Magico | +7 | 4d8 (vari) | 400/1600 ft | Richiede incantatore |
| Sperone | +3 | 4d10 forza | Corpo a corpo | +2d10 a chi è sul ponte |

### Miglioramenti Attivi

Traccia qui quali miglioramenti ha la nave (vedi [[18_Ship_Upgrades/La_Farfalla_Stellare.md#Miglioramenti della Nave|Miglioramenti]]):

```
Scafo Rinforzato:    □ (+50 PF)          2.000 mo
Armatura Metallica:  □ (+2 CA)           5.000 mo
Scudo Magico:        □ (+1 TS nave)      8.000 mo
Cannone Magico +1:   □ (+1, 3d10)        4.000 mo
Cannone Esplosivo:   □ (area 15 ft)      6.000 mo
Elmo Potenziato:     □ (+50% velocità)   6.000 mo
Vela Solare:         □ (+20% velocità)   2.000 mo
Giardino Idroponico: □ (cibo infinito)   2.000 mo
Infermeria:          □ (cura 2d8+4/ora)  2.500 mo
```

---

## 2. SISTEMA DI COMBATTIMENTO NAVE-NAVE

### Struttura del Turno

Ogni round di combattimento navale segue questa sequenza:

1. **Iniziativa Nave:** Il pilota tira 1d20 + INT (CD 15 per manovre complesse)
2. **Movimento Nave:** La nave si muove di 50 ft (manovra base) o compie una manovra speciale
3. **Azioni Nave:** 1 azione nave (fuoco, speronare, abbordaggio) + azione bonus se disponibile
4. **Danni e Riparazioni:** Le unità riparano danni o curano equipaggio
5. **Eventi:** Possibili guasti o eventi speciali (vedi Tabella Guasti)

### Azioni Nave Disponibili

| Azione | Effetto | CD |
|--------|---------|-----|
| **Fuoco (Balista)** | 1 attacco: +5, 3d10 perforanti | — |
| **Fuoco (Cannone)** | 1 attacco: +7, 4d8 (tipo variabile) | — |
| **Fuoco Multiplo** | Tutte le armi: svantaggio su ogni tiro | — |
| **Speronare** | +3, 4d10 forza + 2d10 a equipaggio nemico | CD 13 DES o la nave speronante subisce 2d10 |
| **Abbordaggio** | Se navi affiancate (≤10 ft): gli assaltanti saltano | CD 14 Atletismo per entrare |
| **Manovra Evasiva** | +2 CA per questo round | — |
| **Scarica Magica** | L'incantatore lancia 1 incantesimo area (effetto raddoppiato) | — |
| **Comunicazione** | Messaggio telepatico a 1 nave alleata entro 1 miglio | — |
| **Ritirata** | Velocità dimezzata, nessuna azione offensiva | — |

### Manovre Speciali

| Manovra | Effetto | Requisito |
|---------|---------|-----------|
| **Ariete Stellare** | Velocità x2, danno x2 ma la nave subisce 1d10 | Pilota CD 16 |
| **Rotazione a 180°** | Cambia direzione, +2 CA per questo round | — |
| **Spirale di Fuoco** | 2 attacchi con svantaggio ma 2 bersagli diversi | — |
| **Discesa Rapida** | Caduta 100 ft, +4 al prossimo attacco | — |
| **Volta della Morte** | Manovra impossibile: CD 18 DES o la nave perde 1d6 PF | Pilota CD 18 |
| **Doppio Sperone** | Sperona 2 navi adiacenti | Nave deve essere tra 2 navi nemiche |

---

## 3. SISTEMA DI DANNI ALLA NAVE

### Livelli di Danno

| PF Rimanenti | Stato | Effetti |
|-------------|-------|---------|
| 200+ (80%+) | **Intatta** | Nessuna penalità |
| 150-199 (60-79%) | **Danneggiata** | -10 ft velocità, 1 guasto casuale |
| 100-149 (40-59%) | **Malridotta** | -20 ft velocità, 1 guasto grave, svantaggio armi |
| 50-99 (20-39%) | **Morente** | -30 ft velocità, 2 guasti gravi, rischio collisione |
| 1-49 (1-19%) | **Sulla Pelle** | Immobile, rischio esplosione, equipaggio ferito |
| 0 | **Distrutta** | Esplosione! Equipaggio deve fuggire su scialuppe |

### Come si Infliggono Danni alla Nave

I danni alla nave vengono calcolati **separatamente** dai danni alle creature:

- **Attacchi normali** danneggiano la nave se superano la CA 18
- **Incantesimi** danneggiano la nave per il valore pieno del danno
- **Speronamento** danneggia entrambe le navi
- **Danni ad area** danneggiano la nave se colpiscono una zona critica

### Tabella Danni Critici alla Nave

Quando la nave subisce un **colpo critico** (tiro 20 naturale contro la nave) o viene ridotta a sotto una soglia di PF, tira **1d12**:

| d12 | Danno Critico | Effetto | Riparazione |
|-----|--------------|---------|-------------|
| 1 | **Scafo Incrinato** | -1 CA permanente | 500 mo |
| 2 | **Vela Strappata** | Velocità -10 ft | 200 mo |
| 3 | **Timone Bloccato** | Manovre con svantaggio | 300 mo |
| 4 | **Elmo Instabile** | CD 10 Arcano per ogni manovra | 400 mo |
| 5 | **Perdita di Gas** | La nave perde 5 PF/round | CD 15 Strumenti da Fabbro |
| 6 | **Incendio a Bordo** | 2d6 fuoco/turno, azione per spegnere | — |
| 7 | **Impatto Psichico** | Equipaggio: 1d4 psichici, 1 round sansa azione | 200 mo |
| 8 | **Surge di Energia** | Elmo disattivato 1d4 round, nave immobile | 300 mo |
| 9 | **Breccia nello Scafo** | 1 membro equipaggio risucchiato (FOR CD 15) | 600 mo |
| 10 | **Reazione a Catena** | Armi: 4d6 a ponte armi + 2d6 a equipaggio | — |
| 11 | **Campo di Forza Rotto** | La nave perde tutti i bonus di scudo 24 ore | 1.000 mo |
| 12 | **Alberatura Spezzata** | La nave non può navigare 1d4 giorni | 800 mo |

### Riparazioni

| Tipo | Metodo | Effetto |
|------|--------|---------|
| **Riparazione minore** | CD 15 Strumenti da Fabbro/Falegname | Ripara 1d10 PF |
| **Riparazione media** | CD 17 Strumenti + 50 mo materiali | Ripara 2d10 PF + 1 guasto |
| **Riparazione maggiore** | CD 19 Strumenti + 200 mo materiali | Ripara 4d10 PF + 2 guasti |
| **Riparazione incombattimento** | CD 15, azione bonus, 1 persona | Ripara 1d6 PF |
| **Ingegnere (Mastro Kael)** | Azione bonus, 1/giorno | Ripara 2d10 PF |

---

## 4. TABELLA INCONTRI SPELLJAMMER (d20)

Tira **1d20** per ogni tappa di viaggio (ogni 8 ore di navigazione):

| d20 | Incontro | Effetto |
|-----|----------|---------|
| 1 | **Pirati Spaziali** | Nave nemica 1d4 (1-2 Veliero, 3 Squalo, 4 Nautiloid). Combattimento o fuga. |
| 2 | **Tempesta di Asteroidi** | CD 15 Pilotaggio per evitare 4d10 danni alla nave |
| 3 | **Nave Mercantile in Difficoltà** | Possibilità di aiutare (guadagno 200-500 mo) o agguato (morale -1) |
| 4 | **Nebbia Magica** | La nave perde 1d4 ore. Possibili allucinazioni (SAG CD 13 o 1d4 psichici) |
| 5 | **Creatura Spaziale** | Drago Stellare o Leviatano del Vuoto (incontro diplomatico o fuga) |
| 6 | **Rovine di Nave Antica** | Tesoro (100-500 mo) ma possibili trappole (CD 14 Percezione) |
| 7 | **Zona di Silenzio Magico** | Niente comunicazioni, niente incantesimi per 1d6 ore |
| 8 | **Pattuglia Githyanki** | Documenti o combattimento diplomatico (CD 15 CAR) |
| 9 | **Stazione Spaziale Abbandonata** | Rifornimenti o pericoli (CD 13 Esplorazione) |
| 10 | **Buco Gravitazionale** | CD 18 Pilotaggio per uscire, altrimenti 3d10 danni |
| 11 | **Sciame di Meteoriti** | Spettacolo: +1 morale per 1 ora. Materiali da crafting |
| 12 | **Nave Fantasma** | Equipaggio spettrale. Maledizione o tesoro (CD 16 SAG) |
| 13 | **Corsa Solare** | Vento stellare favorevole: velocità +50% per 1d4 ore |
| 14 | **Pioggia di Stelle Cadenti** | 1d4 stelle da 100 mo ciascuna (materiale crafting) |
| 15 | **Messaggio in Bolla di Stasi** | Richiesta d'aiuto o mappa del tesoro |
| 16 | **Campo di Detriti** | CD 12 Pilotaggio o -10 PF alla nave |
| 17 | **Incontro Diplomatico** | Nave di altra fazione chiede colloquio |
| 18 | **Fenomeno Planare** | Breve apertura a un piano. 1d4 ore di viaggio strano |
| 19 | **Cisterna di Mana** | La nave recupera 1d4 cariche di abilità magiche |
| 20 | **Baia Nascosta** | Base piratesca segreta, santuario o mercato nero |

### Modificatori all'Incontro

| Situazione | Modificatore |
|------------|-------------|
| Navigatore esperto (Nyx) | -1 al tiro (peggior incontro meno probabile) |
| Mappa stellare sicura | Ignori risultati 1-3 |
| Nave nemica in inseguimento | +2 al tiro (incontro peggiore) |
| Viaggio in piani pericolosi (Abisso) | +3 al tiro |
| Giardino Idroponico a bordo | Nessun incontro per caccia |
| Elmo Potenziato | Velocità riduce la probabilità del 25% |

---

## 5. SISTEMA DI CACCIA

Quando una nave insegue un'altra nave o tenta di fuggire, entra in gioco il sistema di caccia.

### Inseguimento

1. **Scoperta:** Il pilota tira PERCEZIONE CD 14 per avvistare la nave nemica
2. **Avvicinamento:** Ogni round, entrambe le navi tirano **d20 + Velocità (mod)**:
   - Se l'inseguitore ottiene **5+ in più**: si avvicina di 1 livello
   - Se ottiene **1-4 in più**: mantiene la distanza
   - Se ottiene **meno**: la distanza aumenta
3. **Livelli di Distanza:**

| Livello | Distanza | Effetto |
|---------|----------|---------|
| Lontano | 1+ miglio | Nessun combattimento, solo avvistamento |
| Medio | 500-1000 ft | Baliste a gittata lunga, cannoni con svantaggio |
| Vicino | 100-500 ft | Tutte le armi, speronamento possibile |
| Affiancata | ≤10 ft | Abbordaggio possibile |

### Fuga

Per fuggire da un combattimento navale:
1. Il pilota tira **d20 + Velocità (mod)** vs il nemico
2. Se supera: la nave si allontana di 1 livello
3. Se fallisce: il nemico può sparare (1 round di fuoco libera)
4. **Distorsore** (se installato): vantaggio al tiro di fuga
5. **Teletrasporto d'Emergenza**: fuga automatica (1/sessione)

### Abbordaggio

Quando la nave è affiancata (≤10 ft):

1. **Fase di Prep:** Gli assaltanti si preparano (azione bonus)
2. **Salto:** Prova di Atletismo CD 14 per saltare sulla nave nemica
3. **Combattimento:** Combattimento D&D normale sul ponte nemico
4. **Obiettivo:** Catturare la nave (distruggere equipaggio) o saccheggiare (1d4×100 mo)
5. **Difesa:** Il difenditore ha vantaggio se ha più equipaggio

### Regole Speciali per Abbordaggio

- Se la nave nemica ha **meno PF della metà**: l'equipaggio è demoralizzato (vantaggio agli assaltanti)
- Se la nave nemica ha **PF pieni**: l'equipaggio è organizzato (svantaggio agli assaltanti)
- **Mind Flayer:** L'equipaggio può essere assorbito (intelligenza): CD 15 SAG o diventa schiavo
- **Pirati:** Possono arrendersi se il morale crolla (3+ equipaggio ucciso in 1 round)

---

## 6. CONSUMO E GESTIONE

### Spese di Viaggio

| Voce | Costo | Frequenza | Note |
|------|-------|-----------|------|
| Cibo equipaggio (6 persone) | 6 mo | Ogni giorno | Ridotto se c'è Giardino Idroponico |
| Provviste nave | 10 mo | Ogni giorno | Munizioni, erbe, acqua |
| Manutenzione ordinaria | 7 mo | Ogni giorno | Riparazioni minori |
| Stipendio equipaggio (base) | 20-33 mo | Ogni giorno | Vedi [[18_Ship_Upgrades/La_Farfalla_Stellare.md#Equipaggio Consigliato|Equipaggio]] |
| Stabilizzazione Elmo | 5 mo | Ogni giorno | Richiede incantatore |
| Munizioni (baliste/cannoni) | 3 mo | Ogni giorno | Se in zona di guerra: x3 |
| **Totale giornaliero** | **~51-54 mo** | — | ~1.530-1.620 mo/mese |

### Ricavi Potenziali

| Attività | Guadagno Stimato |
|----------|-----------------|
| Trasporto merci (breve) | 200-500 mo |
| Trasporto merci (lungo) | 500-2.000 mo |
| Trasporto passeggeri | 50-200 mo/persona |
| Missioni esplorazione | 500-3.000 mo |
| Caccia alla taglia | 1.000-5.000 mo |
| Commercio | 10-50% margine |

### Tabella Consumi per Viaggio

| Durata Viaggio | Cibo | Provviste | Manutenzione | Totale |
|---------------|------|-----------|--------------|--------|
| 1 giorno | 6 mo | 10 mo | 7 mo | 23 mo |
| 1 settimana | 42 mo | 70 mo | 49 mo | 161 mo |
| 2 settimane | 84 mo | 140 mo | 98 mo | 322 mo |
| 1 mese | 180 mo | 300 mo | 210 mo | 690 mo |
| 2 mesi | 360 mo | 600 mo | 420 mo | 1.380 mo |

### Eventi di Consumo (Ogni 7 giorni di viaggio)

| d6 | Evento |
|----|--------|
| 1 | **Scorta Cibo Esaurita** — CD 13 Sopravvivenza o 1d4 giorni senza cibo (affaticamento) |
| 2 | **Guasto Elmo** — CD 15 Arcano per ripristinare, altrimenti nave immobile 1d4 ore |
| 3 | **Munizioni Basse** — 50% delle munizioni rimaste. Rifornimento necessario |
| 4 | **Equipaggio Stanco** — morale -1. 1 membro ha svantaggio a tutte le prove |
| 5 | **Tempesta Magica** — 2d6 danni alla nave (CD 14 DES per dimezzare) |
| 6 | **Tutto O.K.** — nessun evento, viaggio tranquillo |

---

## 7. NEMICI SPELLJAMMER

### Statblock Navi Nemiche

| Nave | PF | CA | Velocità | Armi | Equipaggio | Speciali |
|------|----|----|----------|------|------------|----------|
| **Veliero Pirata** | 120 | 14 | 40 ft | 2 baliste, 1 catapulta | 20 pirati umani | Furtivo (+2 nascondersi) |
| **Squalo Neogi** | 150 | 16 | 45 ft | 2 baliste, 1 raggio riduttore | 10 neogi + umber hulk | Sperone affilato (+2d10) |
| **Corvetta Elfica** | 180 | 17 | 55 ft | 2 cannoni magici, 1 arco luce | 15 elfi + 1 mago | Magia: *Parola di Guardia* 1/giorno |
| **Nautiloid Mind Flayer** | 300 | 18 | 40 ft | 4 raggi psionici | 6 MF + 20 schiavi | Campo psichico: 30 ft, CD 14 SAG o paura |
| **Nave Githyanki** | 200 | 17 | 50 ft | 3 cannoni, 1 drago | 30 githyanki + drago | Drago: *Soffio* 1/giorno |
| **Dreadnought Githzerai** | 350 | 19 | 35 ft | 4 cannoni psionici, campo forza | 25 githzerai + 2 monaci | Campo forza: 100 PF bonus, rinnovabile |
| **Incrociatore dell'Oblio** | 400 | 20 | 35 ft | 6 cannoni d'oblio | 50 cultisti + generale | Cannone Oblio: 6d10 necrotici, area 30 ft |
| **Nave Mercantile Arricchita** | 100 | 12 | 30 ft | 1 balista (difesa) | 10 marinai + capitano | Fuga: +3 al tiro di fuga |

### Tattiche Nemiche

| Tipo Nave | Tattica |
|-----------|---------|
| **Pirata** | Attacca da dietro, sperona, abborda |
| **Neogi** | Raggio riduttore per indebolire, poi abbordaggio |
| **Elfica** | Fuoco magico a distanza, evita combattimento ravvicinato |
| **Mind Flayer** | Campo psichico + raggi. Cerca di catturare, non distruggere |
| **Githyanki** | Aggressivo, carica frontale con drago |
| **Githzerai** | Difensivo, campo di forza, aspetta che il nemico si stanchi |
| **Oblio** | Fuoco devastante, non arrende mai |
| **Mercantile** | Fuga se attaccata, difesa disperata |

---

## 8. NAVE E MAGIA

### Interazioni Magiche con la Nave

| Effetto | Risultato |
|---------|-----------|
| *Individuazione del Magico* | Rileva l'Elmo Spelljamming e le armi magiche |
| *Dissolvi Magie* sulla nave | CD 15. Fallimento: 1 componente si rompe |
| *Riparazione* sulla nave | Ripara 4d8 PF alla nave |
| *Scudo* sulla nave | +2 CA alla nave per 1 minuto |
| *Invisibilità* sulla nave | La nave diventa invisibile (velocità -25%) |
| *Volare* sulla nave | Non ha effetto aggiuntivo (la nave già vola) |
| *Allineamento* sulla nave | Corregge rotta: +3 al prossimo tiro di navigazione |
| *Teletrasporto* sulla nave | Solo se la nave è < 100 PF. Altrimenti: 50% di successo |

### Elmo Spelljamming e Concentrazione

L'Elmo Spelljamming richiede un **incantatore** che lo usi come concentrazione:
- Se l'incantatore perde concentrazione: la nave perde la capacità di muoversi per 1 round
- Se l'incantatore è incosciente: la nave perde capacità di manovra
- Se l'incantatore muore: la nave va alla deriva per 1d4 ore

### Incantesimi d'Area dalla Nave

Quando un incantatore lancia un incantesimo d'area dalla nave, l'effetto è **raddoppiato**:
- Raggio d'azione: x2
- Danno: x1.5
- Ma richiede concentrazione per 2 round (non 1)

---

## 9. EVENTI DI VIAGGIO

### Tabella Eventi Viaggio (d10 per tappa)

| d10 | Evento |
|-----|--------|
| 1-2 | Viaggio tranquillo |
| 3 | **Incontro spaziale** (tira su Tabella Incontri SpellJammer) |
| 4 | **Discussione tra PG** — opportunità di roleplay |
| 5 | **Sogno profetico** — 1 PG ha una visione |
| 6 | **Guasto nave** — riparazione CD 15 |
| 7 | **PNG si confida** — un alleato rivela un segreto |
| 8 | **Tempesta** — 1d6×10 danni (CD 14 Pilota per evitare) |
| 9 | **Tesoro** — 1d6×50 mo |
| 10 | **Visitatore** — qualcuno/qualcosa arriva sulla nave |

### Viaggio Piano per Piano

| Piano di Destinazione | Rischio | Tempo | Speciali |
|----------------------|---------|-------|----------|
| Faerûn (Materiale) | Basso | 1-2 giorni | — |
| Spazio Selvaggio | Medio | Variabile | Tabella incontri attiva |
| Ravenloft | Alto | 3-5 giorni | Nebbia: CD 14 SAG o paura |
| Strixhaven | Basso | 2-3 giorni | Portale magico disponibile |
| Eberron | Basso | 2-3 giorni | Zona di manifestazione |
| Krynn | Medio | 4-6 giorni | Tempeste magiche |
| Theros | Medio | 3-5 giorni | I dei possono intervenire |
| Sigil | Variabile | 1-10 giorni | Dipende dal portale usato |
| Celestia | Basso | 5-7 giorni | I demoni non possono entrare |
| Abisso | Molto Alto | 3-5 giorni | I demoni attaccano ogni 4 ore |
| Feywild | Medio | 2-4 giorni | Tempo relativo: 1 giorno = 1d4 ore |
| Shadowfell | Alto | 3-5 giorni | Tempo relativo: 1 giorno = 1d4 settimane |

---

*La Farfalla Stellare è la casa, l'arma e il mezzo di trasporto dei PG. Trattala con cura.*

**Riferimenti:**
- [[18_Ship_Upgrades/La_Farfalla_Stellare.md|Scheda Completa Nave]]
- [[25_Downtime/Downtime_Per_Mondo.md#Spelljammer (ATTO II.1-2)|Downtime Spelljammer]]
- [[29_Regole_Aggiuntive/Regole_Portali_e_Piani.md|Regole Portali]]
- [[01_Introduzione/Regole_Speciali.md|Regole Speciali]]
