Statistics and probability projects. Data analysis, linear regression, multivariable regression.

## Project 1 - requirements:
Należy wykonać prostą analizę statystyczną danych na unikalnym zbiorze danych.
W sprawozdaniu muszą zawierać się następujące rzeczy:
- Dokładny opis danych, oraz ich źródło.
- Estymacja parametrów rozkładu (punktowa, średnia, odchylenie standardowe, odchylenie przeciętne, mediana, moda, wariancja, kurtoza, skośność, IQR, kwantyle, itp.)
- Estymacja parametrów (przedziałowa) (przedział ufności dla wariancji i dla średniej) oraz metoda nieparametryczna (bootstrap) dla średniej i porównanie.
- Różne wykresy (im więcej tym lepiej). Powinny być histogramy, wkresy kwantyl-kwantyl, boxplot i inne.
- Sprawdzenie czy rozkład (rozkłady) danych pochodzą z rozkładu normalnego.
- Wykorzystanie testu statystycznego dla średniej i wariancji.
- Estymator jądrowy gęstości.

Sprawozdanie powinno zawierać opisy i interpretacje, wykresy i kody.

## Project 2 - requirements:
Należy przygotować model regresji liniowej prostej dla wybranych danych oraz przeprowadzić diagnostykę modelu. W sprawozdaniu powinny znaleźć się następujące rzeczy:
- Dokładny opis wykorzystanych danych oraz ich źródło.
- Dane powinny posiadać przynajmniej 30 obserwacji (zalecane jest dużo więcej).
- Krótki opis teoretyczny modelu regresji liniowej.
- Zbudowanie modelu i jego analiza w R według pliku, który podesłałem na ostatnich zajęciach. Zbudowanie modelu funkcja lm.
- Interpretacja modelu. Interpretacja wartości z summary(model).
- Sprawdzenie założeń (normalność, korelacja, autokorelacja reszt, homoskedastyczność itd, wyznaczenie zbioru dla którego model ma sens itd.)
- Wykresy diagnostyczne z interpretacją, wartości odstające i wpływowe (boxplot, odległość cooke’a).
- Zbudowanie nowego modelu po usunięciu wartości wpływowych. Na koniec jeszcze Kroswalidacja.
- Po usunięciu wartości wpływowych dzielimy nasz nowy zbiór na 5 podzbiorów i tworzymy 5 modeli. Uczymy na 80% zbioru a na 20% testujemy. Liczymy dla obu metrykę R^2 i RSE. Powtarzamy to dla każdego podzbioru (łącznie 5 modeli) i uśredniamy wynik R^2 i RSE dla zbiorów testowych i treningowych.
- Sprawdzamy czy mamy do czynienia z przetrenowaniem czy nie. Ważne żeby zbiór danych treningowych i testowych był zbalansowany.
- Na koniec wnioski i podsumowanie (Czy model jest ok itd)
