# Identification-of-key-variables-in-PCOS
Identification of key variables associated with Polycystic Ovary Syndrome (PCOS) using generalized linear models (GLM) in R. (Identyfikacja kluczowych zmiennych związanych z zespołem policystycznych jajników (PCOS) z wykorzystaniem uogólnionych modeli liniowych (GLM) w R.)

---

## Opis projektu:
Celem projektu była analiza danych pacjentek w kierunku zespołu policystycznych jajników (PCOS) oraz 
identyfikacja kluczowych zmiennych, które mogą mieć istotny wpływ na diagnozę tej choroby.  

Projekt został wykonany w języku **R** na podstawie zbioru danych [PCOS Dataset](https://www.kaggle.com/datasets) i obejmował przygotowanie danych, analizę opisową oraz budowę uogólnionych modeli liniowych (GLM, regresja logistyczna). [Czerwiec 2024]

Projekt wykonany we współpracy w ramach studiów.

---

## Etapy analizy:
1. **Wstępne przygotowanie danych:**  
   - czyszczenie i transformacja zmiennych
   - utworzenie zmiennych kategorycznych 
   - sprawdzenie braków i uzupełnianie danych  

2. **Analiza opisowa i wizualizacje:**  
   - rozkłady podstawowych parametrów zdrowotnych 
   - wizualizacja danych (wykresy pudełkowe, wykresy słupkowe i histogramy, wykresy punktowe)

3. **Testy statystyczne:**  
   - porównania średnich pomiędzy grupami
   - testy istotności zmiennych

4. **Budowa modeli:**  
   - zastosowanie uogólnionych modeli liniowych (GLM, `family = binomial`)
   - ocena wpływu zmiennych na prawdopodobieństwo PCOS  

5. **Wnioski**  
   - BMI i parametry hormonalne mają istotne znaczenie w diagnostyce PCOS. 
   - Nieregularne cykle i obecność objawów klinicznych (np. trądzik) są silnie związane z PCOS. 
   - Uogólnione modele liniowe potwierdziły istotny wpływ kilku kluczowych zmiennych na występowanie choroby.  
