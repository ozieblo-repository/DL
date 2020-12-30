# sandbox

### Projekt na zaliczenie cwiczen, easy customer clustering

`projekt_cwiczenia_customer_clustering_python`

### GLM method

`praca_zal_1_v5.Rmd`

DATASET: http://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29

based on the below exercise (PL language):

Ze strony UCI Machine Learning Repository ściągnij zbiór danych o nazwie Statlog (German Credit Data) (plik german-data.numeric) i zapoznaj się z nim (opisem zmiennych). Wykonaj następujące polecenia:

Ustaw ziarno losowania, np. 12345
Wczytaj dane, sprawdź czy są braki danych i dokonaj przekształcenia wartości ostatniej zmiennej z {1,2} na {0,1}.
Dokonaj losowego podziału zbioru na zbiory: uczący, walidacyjny i testowy w proporcjach odpowiednio 40%, 30% i 30%.
Zbuduj dwa różne modele wykorzystując metodę regresji logistycznej.
Zaprezentuj zdolność predykcyjną obu modeli na zbiorze uczącym i walidacyjnym wykresem ROC i wyznacz wartość statystyki AUC.
Na osobnym wykresie zaprezentuj zdolność predykcyjną na zbiorze walidacyjnym i testowym najlepszego modelu wykresem ROC i wyznacz wartości statystyki AUC.
Narysuj krzywą kosztów złych decyzji w zależności od poziomu progu odcięcia na przedziale od 0,5 do 0,9 z krokiem 0,01 dla najlepszego modelu na zbiorze walidacyjnym. Przyjmij koszt złych decyzji (False Positive oraz False Negative) na poziomie odpowiednio 150 i 1000 PLN. Wskaż optymalny próg odcięcia, dla którego koszty złych decyzji będą najniższe. Policz koszty złych decyzji dla najlepszego modelu i ustalonego progu odcięgia na zbiorze testującym.

### Materialy wykorzystane podczas seminarium MLSG 5 listopada 2019

`wyklad MLSG.pdf`
`std_l2_dpt_reg.ipynb`

**Tematy:**
- Uniwersalny przepływ roboczy uczenia maszynowego
- Nadmierne i zbyt slabe dopasowanie modeli

**Zawartość:** 
- slajdy do prezentacji
- wykresy strat trenowania i walidacji 
