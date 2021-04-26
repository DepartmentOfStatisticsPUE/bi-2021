# Zadanie domowe 

## Cel zadania

Celem zadania domowego jest ściągnięcie 20 wyników naborów do KPRM z portalu https://nabory.kprm.gov.pl. W tym celu proszę wykorzystać poniższy link:

LINK: https://nabory.kprm.gov.pl/wyniki-naborow?AdResult%5BpagesCnt%5D=20&AdResult%5BisAdvancedMode%5D=&AdResult%5Bsort%5D=1&AdResult%5Bid%5D=&AdResult%5Bid_institution%5D=&AdResult%5Bid_institution_position%5D=

## Cele szczegółowe

Zadanie składa się z dwóch etapów:

1. W pierwszym należy pobrać informacje o ogłoszeniach ze strony wyszukiwania. Należy pobrać elementy zaznaczone strzałkami oraz link prowadzący do ogłoszenia, który jest ukryty pod nazwą stanowiska (podpowiedź `html_attr`). Strzałkami oznaczyłem tylko jedno ogłoszenie ale oczywiście chodzi o pobranie tych informacji dla wszystkich 20 ogłoszeń. 

<img width="600" alt="kprm1" src="https://user-images.githubusercontent.com/3464669/116071030-9f692600-a68d-11eb-967c-e367ae99f1e9.png">

2. W drugim należy wejść w link ogłoszenia pobrany w kroku pierwszym i pobrać następujące informacje (podpowiedź: można skorzystać z pętli `for`). Należy również zapisać link do ogłoszenia ukrywający się pod przyciskiem `Pokaż ogłoszenie`.  

<img width="600" alt="kprm2" src="https://user-images.githubusercontent.com/3464669/116071122-c293d580-a68d-11eb-9893-cbcdf9974b6e.png">

Wyniki należy zapisać w ramce danych, która opisana jest poniżej.

## Tabela wynikowa

Wynikiem ma być ramka danych (`data.frame` w R, `pandas.DataFrame` w `pythonie` czy `DataFrame` w Julii), która będzie zawierać 20 wierszy oraz następujące kolumny:

1. numer  (przykładowo: NR 77455)
2. stanowisko (przykładowo: starszy referent)
3. pracodawca (przykładowo: izba administracji skarbowej w Łodzi)
4. miejsce (przykładowo: skierniewicze)
5. data_publikacji (przykładowo: 26.04.2021)
6. data_ogloszenia (przykładowo: 26.04.2021)
7. data_wyniku (przykładowo: 26.04.2021)
8. status (przykładowo: koniec naboru)
9. link_wynik (przykładowo: link z 1 etapu)
10. link_ogloszenia (przykładowo: link z 2 etapu)



## Technologie

Można korzystać z dowolnych technologii 

## Przesyłanie rozwiązań

Link do notatnika colab (nie przesyłamy plików) przesłany przez moodle.
