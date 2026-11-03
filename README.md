# klasifikacija-sisara
Klasifikacija slika sisara primjenom CNN i MobileNetV2 modela
# Klasifikacija slika sisara primjenom dubokog učenja

Projektni zadatak iz predmeta Principi prezentacije i prepoznavanje oblika.

## Opis projekta

Cilj projekta je klasifikacija slika sisara u 45 različitih klasa. 
Skup podataka sadrži ukupno 13.751 sliku.

## Korišćeni modeli

- baseline konvoluciona neuronska mreža
- MobileNetV2 sa transfer learningom

## Podjela podataka

- trening skup: 9.625 slika
- validacioni skup: 2.063 slike
- test skup: 2.063 slike

## Rezultati

- baseline CNN test tačnost: 17,55%
- MobileNetV2 test tačnost: 92,44%

## Pokretanje projekta

1. Otvoriti Colab svesku.
2. Dodati ZIP skup podataka na Google Drive.
3. Po potrebi prilagoditi vrijednost promenljive ZIP_PATH.
4. Pokrenuti ćelije redom, od početka do kraja.

## Korišćene tehnologije

- Python
- TensorFlow i Keras
- MobileNetV2
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
