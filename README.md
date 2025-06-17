# Marvel Network Analysis – Progetto GEPHI

Questo progetto consiste nell’analisi della rete sociale dei personaggi dell’universo Marvel, realizzata attraverso il software Gephi. L’obiettivo è verificare se si applica la legge di Pareto (80/20) alle interazioni tra i personaggi.

## 📁 Contenuti del repository

- `REPORTMARVEL.gephi` – File del progetto Gephi
- `ReportMarvelMiccoli.odt` – Relazione descrittiva

## 🧪 Obiettivo dell’analisi

Adattare la **legge di Pareto** alla struttura del grafo:
> “L’80% degli archi è formato dal 20% dei nodi”

## 🌐 Fonte dati

Dataset Marvel Network disponibile su:
📎 [Gephi Wiki – Marvel Social Network](https://github.com/gephi/gephi/wiki/Datasets)  
Creato da: Cesc Rosselló, Ricardo Alberich, Joe Miro – University of the Balearic Islands  
Rielaborato da Kai Chang

## 🧠 Caratteristiche del grafo

- **Tipo**: Indiretto
- **Nodi**: 10.469 (personaggi Marvel)
- **Archi**: 178.115 (interazioni)
- **Struttura**: Scale-free (pochi hub con alto grado)

## 📊 Risultati principali

- **Cammino medio**: 2.889
- **Diametro del grafo**: 7
- **Grado medio dei nodi**: 34.027

### 🔍 Verifica della legge di Pareto

- 20% dei nodi = circa 2.114 nodi
- 80% degli archi = circa 142.492 archi

Attraverso i filtri in Gephi (Filters → Topology → Degree Range), si è osservato che **circa il 20% dei nodi** è responsabile **di circa il 60% degli archi**.  
👉 Questo significa che la legge di Pareto non si applica perfettamente, ma il comportamento è tendenzialmente simile.

## 🛠️ Strumenti utilizzati

- Gephi 0.9.2
- Algoritmi di analisi: Degree, Path Length, Filters

## 👤 Autore

**Giulio Miccoli**  
Corso di Laurea in Statistica Gestionale – Sapienza Università di Roma  
Anno Accademico: **2021**
