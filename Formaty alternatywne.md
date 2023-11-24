## Formaty alternatywne

### Spis treści

[Wyliczanie bez listy numerowanej](#wyliczanie-bez-listy-numerowanej)  
[Lista mieszana](#lista-mieszana)  
[Zdjęcie z opisem](#zdjęcie-z-opisem)  
[Link z opisem](#link-z-opisem)  
[Link do YouTube](#link-do-youtube)  
[Checklista](#checklista-formatów)  
[Flowchart](#flowchart)

---

### Wyliczanie bez listy numerowanej

5\. matma  
6\. chemia  
versus lista numerowana\
5. matma\
6. chemia

Składnia: _wstaw ' \ ' pomiedzy cyfrą a kropką._

---

### Lista mieszana

1. poniedziałek
2. wtorek
3. środa
   - rano
   - w południe
   - wieczorem

Składnia: _(cyfra., tab, \* )_

---

### Zdjęcie z dymkiem

![](2023-11-24_08-48-15_md-logo.jpg "Na białym tle czarna litera M i strzałka w dół w czarnej zaokrąglonej ramce. ")

Składnia: _![text lub bez tekstu](nazwa pliku "tekst_dymku")_

---

### Link z opisem

[Po godzinach](http://trianglify.io/) "generator wzorów"

Składnia: _[text](url strony)"opis linku"_

---

### Link do YouTube

[![Funkcja agreggate](https://i.ytimg.com/vi/MzqDoXgrmf8/hqdefault.jpg)](https://youtu.be/MzqDoXgrmf8?si=vmmgJhxLo7yzi0iO)

Składnia: _[![text](url do thumbnail filmu)](link YT do filmu)_

---

### Checklista formatów

- [ ] Wprowadzenie
- [ ] Spis treści
- [ ] Formatowanie

Składnia: _(- [space] Opis)_

<!--To jest komentarz-->

---

### Flowchart

```mermaid
 %%{init: {'theme': 'forest', "flowchart" : { "curve" : "basis" } } }%%
   flowchart LR
    A[herbata zimowa] ---> B{z syropem malinowym?};
    B --tak--> C[słodka];
    B --nie--> D[wytrawna];
    C ----> E[kosztuj ze smakiem];
    D ----> E[mkosztuj ze smakiem];
```

Próba wstawienia Mermaid flowchart z zastosowaniem themes - bez powodzenia.
