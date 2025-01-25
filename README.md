# objectDetection_ballTracking


## Descrizione del Progetto
Questo progetto si concentra sull'**Object Detection** applicata al rilevamento di una palla in un dataset di immagini o video. Utilizza tecniche di deep learning e modelli di rilevamento pre-addestrati (come YOLO, SSD o altri) per identificare e localizzare la posizione della palla.

Il progetto comprende:
- Preprocessing delle immagini.
- Addestramento di un modello personalizzato o utilizzo di modelli pre-addestrati.
- Valutazione delle performance.

---

## Contenuti della Repository
- **`Progetto_IvanPrisco_252320.ipynb`**: Notebook Jupyter contenente:
  - Caricamento e preprocessamento del dataset.
  - Addestramento e valutazione del modello di rilevamento.
  - Visualizzazione delle previsioni su immagini di test.
- **`data/`**: Cartella che include:
  - `raw/`: Dataset originale.
  - `processed/`: Dataset preprocessato per l'addestramento.
- **`results/`**: Immagini annotate, grafici di performance e altri output.
- **`requirements.txt`**: File con tutte le librerie richieste per eseguire il progetto.

---

## Dataset
- **Descrizione:** Il dataset contiene immagini o frame video che rappresentano scene in cui è presente una palla da rilevare.
- **Annotazioni:** Ogni immagine è annotata con le coordinate bounding box della palla.
- **Formato:** 
  - Immagini: `.jpg` o `.png`.
  - Annotazioni: Formato YOLO (`.txt`) o Pascal VOC (`.xml`).
- **Esempio di annotazione YOLO:**
  ```plaintext
  0 0.5 0.5 0.2 0.2
