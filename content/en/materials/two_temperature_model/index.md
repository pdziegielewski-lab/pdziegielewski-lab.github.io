---
title: "Two temperature model"
date: 2023-10-25
draft: false

# Dla lepszej organizacji - tagi i kategorie
tags: ["TTM", "Molecular Dynamics", "Simulations"]
categories: ["Works"]

# Opis, który pojawi się na liście postów/projektów
summary: "The Two-Temperature Model (TTM) in Molecular Dynamics (MD) is a method used to simulate systems where there is a significant difference in temperature and energy distribution between the electrons and the ions/atoms (the lattice)."

# Obrazek "głównej strony" lub baner
image:
  caption: 'TTM (wikipedia.org)'
  focal_point: "Center"
  preview_only: false

# Jeśli chcesz dodać załączniki (np. PDF, kod)
url_pdf: "method_paper.pdf" # Plik PDF wrzuć do folderu z postem (moja-metoda/)
url_code: "https://github.com/twojlogin/kod-metody"
---

## Wstęp

Tutaj będzie opis tej metody.

## Schemat metody

![Tu opis obrazka, poki co featured](featured.png "Opis obrazka, który pojawi się po najechaniu")

*Rysunek 1: Przklad dzialania*

## Matematyczne podstawy

Metoda opiera się na następującym równaniu:

\begin{aligned}
KL(\hat{y} || y) &= \sum_{c=1}^{M}\hat{y}_c \log{\frac{\hat{y}_c}{y_c}} \\
JS(\hat{y} || y) &= \frac{1}{2}(KL(y||\frac{y+\hat{y}}{2}) + KL(\hat{y}||\frac{y+\hat{y{2}}}))
\end{aligned}


Gdzie:
- $F(\omega)$ to transformata Fouriera,
- $f(t)$ to sygnał w dziedzinie czasu,
- a $\omega$ to częstość kątowa.

Możemy też pisać równania w linii, np. $E = mc^2$.

## Podsumowanie

Podsumowanie metody i jej zalet.

---

### 📄 Pełny artykuł

Pobierz pełny artykuł w formacie PDF: [Pobierz PDF](method_paper.pdf)