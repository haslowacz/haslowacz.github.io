# 🔐 Generator Haseł

Prosty, estetyczny generator haseł w przeglądarce. Tworzy silne, a jednocześnie łatwe do zapamiętania hasła na bazie polskich słów.

👉 **Demo:** [https://haslowacz.github.io/](https://haslowacz.github.io/)

---

## ✨ Funkcje

* Generowanie haseł w formacie:

  ```
  SłowoSłowo13#$
  ```
* 2 losowe polskie słowa
* 2 losowe cyfry
* 2 losowe znaki specjalne
* TransliteracjA polskich znaków
* Kopiowanie hasła jednym kliknięciem
* Styl retro (VT323)
* 100% offline – działa lokalnie w przeglądarce

---

## 🧠 Przykładowe hasła

```
MotylZamek42@#
PlanetaRzeka07$!
LaptopOgród91%&
```

---

## 🛠️ Jak uruchomić lokalnie

1. Sklonuj repozytorium:

   ```bash
   git clone https://github.com/haslowacz/haslowacz.github.io.git
   ```

2. Wejdź do katalogu:

   ```bash
   cd haslowacz.github.io
   ```

3. Otwórz plik `index.html` w przeglądarce

Gotowe 🎉

---

## 📁 Struktura projektu

```
/
├── index.html      # Główna strona
├── baza.txt        # Lista polskich słów
├── icon.png        # Favicon
└── README.md       # Ten plik
```

---

## ⚙️ Jak działa generowanie

Każde hasło składa się z:

* Losowego słowa #1
* Losowego słowa #2
* 2 losowych cyfr (0–9)
* 2 losowych znaków specjalnych (`! @ # $ % & * ? + - _`)

Dodatkowo:

* Pierwsza litera każdego słowa jest wielka
* transliteracja polskich znaków

---

## 🎨 Technologie

* HTML5
* CSS3
* JavaScript (Vanilla)
* Google Fonts (VT323)

---

## 📌 Roadmap (pomysły)

* [ ] Opcja wyboru długości hasła
* [ ] Przełącznik: małe/duże litery
* [ ] Własna lista słów
* [ ] Eksport haseł do pliku
* [ ] Tryb jasny / ciemny

---

## 👤 Autor

**Damian**

---

## 📜 Licencja

MIT – rób co chcesz, byle nie mów, że to Twój pomysł 😉
