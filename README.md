# Hibridni Ekspertski Sistem za Klasifikaciju Tumora Dojke

## Opis Projekta

Ovaj projekat predstavlja detaljan razvoj i implementaciju hibridnog sistema za mašinsko učenje sa ciljem postizanja savršene dijagnostičke klasifikacije tumora dojke na osnovu "Wisconsin (Diagnostic)" skupa podataka.

Kroz iterativan proces, koji je uključivao dubinsku analizu podataka, poređenje više modela i forenziku grešaka, razvijen je finalni sistem koji kombinuje snagu **Random Forest** klasifikatora sa **na pravilima zasnovanom "sigurnosnom mrežom"**. Ovaj pristup je uspešno rešio problem "graničnih slučajeva" koje standardni modeli propuštaju.

**Finalni sistem postiže 100% tačnost, preciznost i odziv na test setu.**

## Struktura Repozitorijuma

-   `data/data.csv`: Originalni skup podataka korišćen za analizu.
-   `notebooks/Breast_Cancer_Classification_Final_Report.ipynb`: Glavni Jupyter Notebook koji sadrži celokupan proces analize, razvoja modela i finalne zaključke.
-   `requirements.txt`: Lista svih neophodnih Python biblioteka za pokretanje projekta.
-   `README.md`: Ovaj fajl.

## Kako Pokrenuti Projekat

1.  **Klonirajte repozitorijum:**
    ```bash
    git clone https://github.com/VASE_KORISNICKO_IME/BreastCancerDiagnosticClassification.git
    cd BreastCancerDiagnosticClassification
    ```

2.  **Kreirajte i aktivirajte virtuelno okruženje (preporučeno):**
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # Na Windows-u: .venv\Scripts\activate
    ```

3.  **Instalirajte potrebne biblioteke:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Pokrenite Jupyter Notebook:**
    Otvorite `notebooks/Breast_Cancer_Classification_Final_Report.ipynb` u Jupyter okruženju (Jupyter Lab, Jupyter Notebook, VS Code, PyCharm) i izvršite ćelije.

## Korišćene Tehnologije

-   Python 3.12
-   Pandas & NumPy za manipulaciju podacima
-   Matplotlib & Seaborn za vizuelizaciju
-   Scikit-learn za modeliranje i evaluaciju
-   XGBoost