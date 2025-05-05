# Excel
## Soontu Health Tracker 2022
<li> Szybki dashboard analizujący postępy aktywności fizycznej na podstawie danych: aktywność, data, bmi, waga, whr
<li> Typ danych źródłowych: csv 
<li> Techstack: Excel
<li> przykłady funkcji czyszczenia danych: 
<br>Złączamy dane w jedną kolumnę =TEXTJOIN(";";TRUE;tb_source4[@[Date of Purchase]:[Refund Request]])
<br>Do zliczenia dubli używamy: =ROWS(UNIQUE(tb_source4[[#All];[ID_unique]]))
<br>Do zliczenia wszystkich wierszy używamy: =COUNTA(tb_source4[ID_unique])
<br>Do wylistowania dubli używamy: =FILTER(tb_source3[ID_unique];COUNTIF(tb_source3[ID_unique];tb_source3[ID_unique])>1)
<li> Raport pokazuje aktwność fizyczną w pozwiązaniu z efektami wpłwu na zdrowie w czasie 12 miesięcy. Widzimy zwiększoną aktwność ćwiczącej w miesiącacach: kwiecień, sierpień oraz październik. Natomiast rozkład watości maksymalnych aktywności rozkłada się równo we wszystkich miesiącach. Przy równym rozkładzie widzimy spadek wagi, bmi oraz whr z poziomów zagrażających zdrowiu do wartości oznaczonych jako bezpieczne.
  
![Soontu Health Tracker 2022 dashboard screen](https://github.com/user-attachments/assets/11f5c01a-0d33-4f37-8c50-7e1a3dba06e5)

<br>Wskaźnik BMI (Body Mass Index) to proste narzędzie do oceny masy ciała w relacji do wzrostu. Oblicza się go dzieląc wagę (w kg) przez kwadrat wzrostu (w metrach). Prawidłowy BMI mieści się w przedziale 18,5 - 24,9. Niski BMI (poniżej 18,5) wskazuje na niedowagę, a wysoki (powyżej 25) na nadwagę lub otyłość. 

<br>Wartości BMI i ich interpretacja:
<li>Poniżej 18,5: Niedowaga
<li>18,5 - 24,9: Prawidłowa masa ciała
<li>25 - 29,9: Nadwaga
<li>30 - 34,9: Otyłość I stopnia
<li>35 - 39,9: Otyłość II stopnia
<li>40 i więcej: Otyłość III stopnia 

Wskaźnik WHR (Waist-Hip Ratio) to stosunek obwodu talii do obwodu bioder, używany do oceny rozmieszczenia tkanki tłuszczowej i typu sylwetki. Pomaga w identyfikacji ryzyka chorób związanych z otyłością brzuszną. 
Jak obliczyć wskaźnik WHR:
Zmierz obwód talii w najwęższym miejscu, Zmierz obwód bioder w najszerszym miejscu, Podziel obwód talii przez obwód bioder. 

Interpreacja wyników:

U kobiet:

<li>WHR < 0,8 - otyłość udowo-pośladkowa (typu gruszka).
<li>WHR > 0,8 - otyłość brzuszna (typu jabłko).

U mężczyzn:

<li>WHR < 1 - otyłość udowo-pośladkowa (typu gruszka).
<li>WHR > 1 - otyłość brzuszna (typu jabłko). 
<li>Wartości referencyjne (dla zdrowia):
<li>WHR poniżej 0,9 dla mężczyzn i poniżej 0,85 dla kobiet. 
<li>Idealny WHR u kobiet to 0,7, a u mężczyzn to 1.

## UK Railway sales report
<li> Szybki dashboard pokazujący sprzedaż biletów UK Railway wg sprzedaż total, typ biletu, rodzaj biletu, sprzedaż w godzinach szczytu, wg liczby opóźnień
<li> Techstack: Excel
<li> Raport wskazuje przewagę sprzedaży bileów typu Advance w porównaniu do Off-Peak i Anytime. Tylko 20% klientów wybiera bielety First Class. Natomiast ponad 67% przychodu z bilwów przypada w godzinach szczytu czyli 4.00-9.00 i 16.00-19.00. Tylko ponad 4000 połączeń miało opóźnienia lub było anulowanych spośród ponad 31 000 połączeń. Najczęściej sprzedawane trasy to TOP3: 
<br>1. Manchester Piccadilly - Liverpool Lime Street
<br>2. London Euston - Birmingham New Street
<br>3. London Kings Cross - York
  
![UK Railway sales report dashboard screen](https://github.com/user-attachments/assets/15b96c35-067c-4dd6-8127-b42f3e9c4ebd)



