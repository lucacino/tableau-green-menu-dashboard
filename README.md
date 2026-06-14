# Tableau — Green Menu Dashboard

> Analisi della carbon footprint degli alimenti per supportare un ristorante nella costruzione di un menù sostenibile, con dashboard interattiva su Tableau Public.

**IT** | Progetto di Data Visualization realizzato nell'ambito del Master in Data Science, Analytics e AI @ Start2Impact University.

---

## Obiettivo / Objective

**IT:** Supportare un ristorante nella transizione verso un menù più sostenibile, analizzando le emissioni di CO₂ per kg di prodotto durante l'intero ciclo di vita degli alimenti (dalla coltivazione al retail). L'output è una dashboard Tableau pensata per un pubblico non tecnico, che consente decisioni basate sui dati.

**EN:** Help a restaurant build a data-driven green menu by analyzing GHG emissions per kg of food product across the full lifecycle — from farm to retail. Delivered as an interactive Tableau Public dashboard designed for non-technical stakeholders.

---

## Dataset

Source: [GHG Emissions by Lifecycle Stage](https://ourworldindata.org/food-choice-vs-eating-local) — Our World in Data

[Download diretto CSV](https://ourworldindata.org/uploads/2020/02/GHG-emissions-by-life-cycle-stage-OurWorldinData-upload.csv)

Variabili analizzate:
- `Food product` — nome dell'alimento
- `Land use change`, `Animal Feed`, `Farm`, `Processing`, `Transport`, `Packaging`, `Retail` — emissioni CO₂ per fase (kg CO₂eq / kg prodotto)
- `Animal / Plant Products` — classificazione per origine

---

## Analisi e Insight / Analysis & Key Insights

### Emissioni Totali per Prodotto
Il manzo domina con circa **60 kg CO₂/kg** — quasi il doppio di agnello e formaggio. I prodotti vegetali si concentrano nella parte bassa: la differenza non è marginale, è strutturale.

### Animale vs Vegetale
| Categoria | CO₂ Totale |
|---|---|
| Prodotti animali | ~150 kg |
| Prodotti vegetali | ~105 kg |

Divario del **40%**, con i prodotti animali che rappresentano una parte minoritaria degli alimenti analizzati.

### Alternative a Basse Emissioni
| Categoria | Alto impatto | Alternativa sostenibile |
|---|---|---|
| Proteine | Manzo (~60), Agnello (~25) | Tofu (~3), Legumi (~2) |
| Latticini | Formaggio (~21) | Latte (~3), Latte di soia (~1) |
| Carboidrati | Riso (~4) | Patate (~0.4) |

---

## Raccomandazioni Strategiche / Strategic Recommendations

1. **Ridurre il manzo** — la sostituzione singola più impattante
2. **Rivalutare i latticini** — preferire latte e alternative vegetali al formaggio dove possibile
3. **Legumi e tofu come proteine principali** — impatto minimo, percezione consumer in crescita
4. **Patate come carboidrato base** — più sostenibili del riso e già familiari in cucina

---

## Target della Dashboard

Il pubblico ideale è il management di ristoranti e food service interessati a posizionarsi sul mercato della ristorazione sostenibile. La dashboard è progettata per essere leggibile senza competenze tecniche: i grafici a barre con ranking immediati e i confronti per categoria permettono decisioni operative dirette — quale proteina sostituire nel menù, quale carboidrato preferire — senza dover interpretare dati grezzi.

Un menù costruito su questi criteri non è solo più sostenibile: è anche una leva di comunicazione verso un pubblico sempre più attento alle scelte ambientali.

---

## Dashboard Tableau

🔗 **[Visualizza la Dashboard su Tableau Public](INSERISCI_LINK)**

La dashboard include:
- Ranking emissioni totali per prodotto
- Confronto Animale vs Vegetale
- Grafici comparativi per categoria (Proteine / Latticini / Carboidrati)
- Tooltip, filtri e azioni per navigazione interattiva

---

## Tech Stack

- Tool: Tableau Desktop / Tableau Public
- Tipo di chart: Bar chart, Grouped bar, Summary KPI cards
- Interattività: tooltip, filtri, dashboard actions

---

## Struttura del Repository

```
tableau-green-menu-dashboard/
├── README.md
├── dashboard/
│   └── green_menu.twbx
└── presentation/
    └── Progetto_Data_Visualization_con_Tableau_di_Luca_Cino.pdf
```

---

## Autore / Author

**Luca Cino** — [LinkedIn](https://www.linkedin.com/in/lucacino) | [GitHub](https://github.com/lucacino)

Master Professionale in Data Science, Analytics e AI @ Start2Impact University
