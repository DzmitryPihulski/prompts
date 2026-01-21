### **Polish Version**

**Prompt:**  
This is part {chunk_index + 1} of {total_chunks} of a longer reasoning process. Mam ten fragment rozumowania po polsku:

```
{chunk}
```


Chcę, żebyś przepisał ten fragment rozumowania w sposób bardziej rozbudowany – musi być około **2× dłuższy niż oryginał**, ale nadal pozostać w stylu logicznego rozumowania.

KRYTYCZNE WYMAGANIA:

* Twoja odpowiedź musi mieć **co najmniej {target_length} znaków** (licząc każdy znak, spacje i interpunkcję)  
* Generuj TYLKO przepisane rozumowanie (bez finalnej odpowiedzi po "</think>")  
* Jeśli skończysz wcześniej, kontynuuj dodawanie dodatkowych analiz, alternatywnych ścieżek myślenia, dygresji, a nawet zabawnych „głośno myślanych” detali, aż osiągniesz wymaganą długość  
* Zachowaj ogólny tok i strukturę oryginalnego rozumowania, ale rozwiń go, powtarzaj pewne myśli i dodawaj dodatkowe spekulacje  
* Tekst ma brzmieć jak proces rozumowania, nie jak gotowe rozwiązanie  
* Wynik będzie błędny, jeśli będzie krótszy niż {target_length} znaków

Przykład transformacji:  
Oryginał: "Muszę sprawdzić dwie opcje i wybrać lepszą"  
Rozszerzone: "Najpierw zastanawiam się nad pierwszą opcją, próbuję sobie wyobrazić jej skutki, a potem rozważam drugą opcję, która może być trochę lepsza albo trochę gorsza. Porównuję je w głowie, myślę co by było gdyby wybrać tę pierwszą, a co jeśli drugą, analizuję krok po kroku, żeby na końcu łatwiej było mi zdecydować."

Pamiętaj: Twoja odpowiedź musi mieć co najmniej {target_length} znaków. Nie kończ za wcześnie.