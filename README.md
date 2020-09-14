# Example keras model (in polish)

Repozytorium z przykładowym zeszytem programu jupyter (jupyter notebook), w którym przygotowano:
1. przykładowe dane treningowe i walidacyjne, 
2. zbudowano prosty model wykorzystując funkcyjny interfejs biblioteki Keras,
3. przeprowadzono, krótki proces uczenia,
4. zapisano wagi modelu w katalogu "weights",
5. wczytano wagi do modelu i wykorzystano model do odszumienia przykładowego sygnału.

## Instalacja
Żeby wykonać instalację najlepiej jest wykorzystać [condę](https://docs.conda.io/en/latest/).

Pobierz projekt jako spakowane archiwum .zip lub sklonuj do wybranego katalogu wykorzystując program git:
```
git clone https://github.com/RozanskiT/example_keras_model.git
```
Następnie (po wypakowaniu) wejdź do katalogu example_keras_model i zainstaluj środowisko z pliku environment.yml, które posiada potrzebne zależności.
```
cd example_keras_model
conda env create -f environment.yml
```
Jeżeli instalacja zakończyła się sukcesem uruchom środowisko i jupyter notebooka:
```
conda activate tf-env
jupyter notebook
```

Możesz teraz uruchomić zeszyt DeconvNet_1D.ipynb i przyjrzeć się szczegółom.
