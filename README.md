# open.bydata Notebooks

### Ausführung der Open Data Notebooks

Unsere Codebeispiele sind als **IPython‑Notebooks (.ipynb)** implementiert.  
Die Notebooks können **entweder online ohne lokale Installation** oder **lokal auf dem eigenen Rechner** ausgeführt werden.

---

#### A) Notebooks **online ausführen**

Für den schnellen Einstieg empfehlen wir die folgenden browserbasierten Tools zur Auswahl:

1. **Google Colab**  
   Link: [https://colab.research.google.com/](https://colab.research.google.com/)  
   So öffnest du ein Notebook aus unserem Repository:

   1. Öffne Colab.
   2. Klicke auf „Notebook öffnen“.
   3. Im Dialogfenster „Notebook öffnen“ wähle links den Tab „GitHub“.
   4. Gib im Suchfeld „byte-bayern“ ein.
   5. Wähle das gewünschte Notebook aus der Liste aus.
   6. Das Notebook startet direkt in Colab und kann ausgeführt werden.

2. **MyBinder**  
   Link: [https://mybinder.org/](https://mybinder.org/)  
   MyBinder ermöglicht es, ein komplettes Jupyter‑Notebook‑Setup aus einem GitHub‑Repository zu starten – ohne lokale Installation.  
   Anleitung:

   1. Besuche die MyBinder‑Seite.
   2. Kopiere die URL des Git-Repositories von GitHub (unter „Code“ > „HTTPS“) und füge diesen auf MyBinder unter „GitHub repository name or URL“ ein.
   3. Gib unter „Git ref (branch, tag, or commit)“ den Namen der Branch ein. (z.B. „main“)
   4. Gib unter „File to open (in JupyterLab)“ den Namen des zu öffnenden Notebooks ein (z.B. `munich-bike-counting-stations.ipynb`).
   5. Klicke auf "launchen".
   6. Nach dem Build öffnet sich eine interaktive Jupyter-Umgebung.

3. **JupyterLite**  
   Link: [https://jupyter.org/try-jupyter/lab/](https://jupyter.org/try-jupyter/lab/)  
   Diese Variante erlaubt das Ausführen von Notebooks direkt im Browser – vollständig client‑seitig.
   1. Lade dir eine lokale Kopie unseres Git-Repositories herunter („Download ZIP“ oder `git clone <URL>`).
   2. Besuche die Jupyter-Website und lade dort den Inhalt des Repos hoch.

---

#### B) Notebooks **lokal ausführen**

Für maximale Flexibilität kannst du die Notebooks auch **lokal ausführen** – z. B. mit:

- Jupyter Notebook
- JupyterLab
- einer Python‑IDE wie VS Code + Jupyter‑Extension

**Voraussetzungen**  
Damit das Notebook bei dir lokal läuft, müssen die benötigten Python‑Pakete installiert sein.

Typischer Ablauf:

```bash
# Repository klonen
git clone <URL-zum-Repository>
cd <repo>

# Abhängigkeiten installieren
pip install -r requirements.txt

# Notebook starten
jupyter notebook
```
