## Formatowanie podstawowe

Spis treści:

[Pogrubienie](#pogrubienie)  
[Kursywa](#kursywa)  
[Cytat](#cytat-wyróżnienie)  
[Wykreślenie](#wykreślenie)  
[Lista numerowana](#lista-numerowana)  
[Lista wypunktowana](#lista-wypunktowana)  
[Równanie](#równanie---wyróżnienie)  
[Kod](#kod---blok)  
[Tabele](#tabele)  
[Odsyłacze](#odsyłacze-zewnętrzne)  
[Obrazy](#obrazy)

---

### Pogrubienie

Eget _aliquet_ nibh **praesent** tristique magna sit amet purus gravida.

Składania: _(\*\*tekst\*\*)_

---

### Kursywa

Autorem poniższego cytatu jest _Bernice Johnson Reagon._

Składania: _(\_tekst\_)_

---

### Cytat - wyróżnienie

> Życiowe wyzwania nie powinny Cię paraliżować.  
> Powinny pomóc Ci odkryć, kim naprawdę jesteś.

Składania: _(\> tekst, w każdej wyróżnianej linii)_

---

### Wykreślenie

~~NIe patrz za siebie~~ Patrz przed siebie.

Składania: _(\~~tekst\~~)_

---

### Lista numerowana

1. Raz
2. Dwa
3. Trzy

Składania: _(cyfra., spacja, tekst)_

---

### Lista wypunktowana

- szklanka
- wazon
- butelka

Składania: _(-, spacja, opis)_

---

### Równanie - wyróżnienie

Obciążenie na zestaw kołowy wagonu oblicza się wg wzoru:  
`P=(Q+q)/x`  
gdzie:  
`Q - ciężar własny wagonu t`  
`q - ciężar ładunku t`  
`x - liczba osi wagonu`

Składania: _(\`wzór lub opis`)_

<!--oddzielić wiersze 2x spacja + Enter-->

---

### Kod - blok

Ciąg Fibonacciego

```Python
n = 10

fibo = [0]*(n)
fibo[0] = 0
fibo[1] = 1

for i in range(2,n):
  fibo[i] = fibo[i-1] + fibo[i-2]

print(fibo)
```

Składania: _(\`\`\`kod, można dopisać język kodu```)_

Na podglądzie w VS Studio kod wyświetla się z kolorowymi wyróżnikami funkcji.  
Markup oraz Github Markdown nie wspiera wprost wyróżniania kolorem elementów kodu.

---

### Tabele

Przykładowa tablica granic obciążeń wagonów:

| Prędkość |  A   |  B   |  C   |  D   |
| :------- | :--: | :--: | :--: | :--: |
| S        | 37,0 | 45,0 | 53,0 | 63,0 |
| 120      | 0,00 |

Smaki owoców tropikalnych:

| Owoc    |    Emoji    |          Smak |
| :------ | :---------: | ------------: |
| cytryna |   :lemon:   |        kwaśny |
| jabłko  |   :apple:   |        słodki |
| ananas  | :pineapple: | kwaśno-słodki |

Składania: _(\|tworzy kolumny\|, \----- wyznacza wiersze, \---: wyrównanie w kolumnach, emoji \:nazwa:)_

Przy pierwszej probie z emoji, GitHub wyświetliły się na stronie 2 z trzech owoców.  
Kiedy używasz emoji sprawdź czy jest rozpoznawe przez GITHUB.

---

### Odsyłacze zewnętrzne

[Machine hallucinations - Refik Anadol Studio](http://refikanadol.com/works/machine-hallucinations-space-metaverse/?fbclid=IwAR1w9llGY0RxjgYAcj_zqkDAK60xdpuVrx7efIkVfL_K1uNTZgU__dD5uFc)

Składania: _(\[text]\(link), nawiasy bez odstępów)_

Kolor roku 2024 http://icolorpalette.com/color/pantone-2024-c

Składania: _(text + wklejony link bez formatowania)_

W podglądzie VS Code składnia text + link podświetlony.  
W GHW całość wyświetla się jako text.

---

### Obrazy

To obraz wygenerowany promptem w DALL-E3.

![Ich troje: Ja, Markdown & DALL-E3](2023-11-20_18-21-13_markdown-mem-DallE3.jpg)

Składnia: _!\[text](nazwa pliku zdjęcia)_

![happy](2023-11-25_mark-mem-happy-L-DallE3-1.jpg "Happy with Markdown")

Składnia: _!\[tekst](nazwa pliku zdjęcia "tekst dymku")_

💡 Dlaczego po wklejeniu zdjęcia z dysku lokalnego, plik duplikuje się i nazwa pliku dostaje rozszerzenie np. "-1"?

💡 Czy w repozytorium muszą być podwojne pliki?

---
