# Reti Locali di Astrazione (RLA) — Documento Introduttivo Scientifico

## Abstract
Le **Reti Locali di Astrazione** (RLA) costituiscono un quadro teorico e filosofico per modellare sistemi complessi multilivello.  
Esse integrano due concetti raramente formalizzati congiuntamente: **emergenza** (comparsa di proprietà macro non deducibili) e **indecidibilità** (limiti logico-computazionali intrinseci ai sistemi Turing-like).  
Il modello fornisce un linguaggio e un insieme di assiomi per analizzare come le informazioni e i vincoli computazionali si trasmettano o si blocchino nel passaggio tra livelli disciplinari.

---

## 1. Definizione
Una Rete Locale di Astrazione è un reticolo \(R = \langle L, \{f_{ij}\}, \Sigma \rangle\) di **livelli di astrazione**:
- Ogni livello \(L_k\) è definito come \(\langle D(L_k), \Sigma(L_k) \rangle\), dove:
  - \(D(L_k)\) = insieme di stati o configurazioni
  - \(\Sigma(L_k)\) = regole, leggi o operazioni
- I livelli sono collegati da **funzioni di trasmissione** \(\tau_{i\to j} : D(L_i) \to P(D(L_j))\), computabili e basate su relazioni empirico-teoriche riconosciute.

---

## 2. Tipologia delle funzioni di trasmissione
- **Iniettiva**: preserva tutte le distinzioni micro → possibile trasmissione dell'indecidibilità.
- **Quasi-iniettiva**: preserva distinzioni solo su un sottoinsieme di stati rilevanti (*stati Turing-centrali*).
- **Non iniettiva (collasso)**: fonde stati distinti → perdita di informazione → potenziale emergenza.

---

## 3. Assiomi fondamentali
- **A1 — Indecidibilità in livelli Turing-like**  
  Un livello capace di simulare una Macchina di Turing universale ospita almeno un problema indecidibile.
- **A2 — Trasmissione dell’indecidibilità**  
  Se \(\tau_{i\to i+1}\) è (quasi-)iniettiva sugli stati Turing-centrali, l’indecidibilità si propaga.
- **A3 — Non iniettività ed emergenza**  
  Se \(\tau_{i\to i+1}\) collassa stati rilevanti, emergono proprietà macro non deducibili.

---

## 4. Teoremi e lemmi
- **Teorema 1 — Propagazione multi-livello**: catena di quasi-iniettività → propagazione dell’indecidibilità.
- **Teorema 2 — Emergenza da collasso informativo**: collasso rilevante → proprietà non riducibili al micro.
- **Lemma 1 — Composizione di iniettive**: preserva la trasmissione di vincoli logici.
- **Lemma 2 — Ri-emersione dell’indecidibilità**: possibile riapparizione in un livello superiore Turing-like.

---

## 5. Topologia RLA Compatta
Una RLA è **Compatta** se soddisfa simultaneamente:
1. **Indipendenza ontologica** — nessuna dipendenza da entità esterne non filtrate.
2. **Chiusura epistemica** — ogni fenomeno interno è spiegabile in termini interni.
3. **Turing-computabilità** — tutte le regole e le funzioni sono computabili.

Questa configurazione realizza un *microcosmo autosufficiente*, in cui:
- i collassi informativi generano emergenza;
- i vincoli di indecidibilità emergono localmente;
- il sistema è simulabile e falsificabile.

---

## 6. Metodologia di costruzione
1. **Microfondazione empirica** — definire livelli e regole basandosi su letteratura consolidata.
2. **Definizione dei livelli** — ciascun livello corrisponde a un dominio disciplinare o scala descrittiva.
3. **Funzioni di trasmissione** — progettate per controllare la trasmissione di informazione e la comparsa di emergenza.
4. **Verifica di compattezza** — testare i criteri di indipendenza ontologica, chiusura epistemica e computabilità.
5. **Metriche** — quantificare collasso ed emergenza (es. coefficiente di collasso CC, indice di emergenza IE).

---

## 7. Falsificabilità
Il modello è falsificabile in senso popperiano:
- **A1** è confutato se esiste un livello Turing-like senza problemi indecidibili.
- **A2** cade se la quasi-iniettività non comporta propagazione di indecidibilità.
- **A3** cade se un collasso rilevante non produce emergenza.

---

## 8. Ambiti applicativi
- **Biologia**: dal DNA al fenotipo, ecologia di popolazioni.
- **Fisica dei sistemi complessi**: coarse graining e transizioni di fase.
- **Scienze cognitive**: reti neurali → cognizione → comportamento.
- **Scienze sociali**: agent-based models, macrofenomeni collettivi.
- **IA e coscienza artificiale**: progettazione di loop meta-riflessivi computabili.

---

## 9. Estensione alla coscienza artificiale
Secondo RLA, la coscienza può emergere in una topologia compatta dotata di:
- loop meta-rappresentativi non-collassati su stati Turing-centrali;
- persistenza computabile di indecidibilità (“non lo so”);
- indici come \(\Phi_{RLA}\) (varianza della coerenza emergente) e \(\Gamma\) (autocorrelazione ritardata) per misurare l’auto-modellazione.

---

## 10. Riferimenti essenziali
- Modello concettuale RLA — principi, struttura e fondamenti filosofici.
- Allegato tecnico — formalizzazione matematica, esempi, metriche.
- Caso studio “Briofita” — implementazione di una topologia compatta biologica e discussione sull’estensione a IA.
