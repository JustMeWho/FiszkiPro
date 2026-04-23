## ☕ Wsparcie projektu

Jeśli program Ci się podoba i chcesz docenić moją pracę nad jego rozwojem, możesz postawić mi wirtualną kawę:

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/paymewho)

Każde wsparcie motywuje do dodawania nowych funkcjonalności! Dzięki! 🚀

# 🗂️ Fiszki Pro - Twój Osobisty Trener Słownictwa

Fiszki Pro to nowoczesna, desktopowa aplikacja do nauki języków obcych (aktualnie wspiera angielski i polski), zbudowana w Pythonie przy użyciu biblioteki **CustomTkinter**. Program pozwala na kompleksowe zarządzanie własnymi zestawami słówek oraz oferuje cztery różnorodne tryby nauki, które angażują różne mechanizmy zapamiętywania.

---

## ✨ Kluczowe Funkcjonalności

### 🗃️ Zarządzanie Zestawami
* **Tworzenie i Import:** Możliwość ręcznego wpisywania słówek w wygodnym widoku tabelarycznym lub masowego importu z tekstu (obsługa separatorów takich jak średnik, przecinek czy myślnik).
* **Edycja Wizualna:** Pełna kontrola nad istniejącymi zestawami – dodawanie, usuwanie i modyfikacja słówek w dowolnym momencie.
* **Baza Danych SQLite:** Wszystkie Twoje postępy i zestawy są bezpiecznie przechowywane w lokalnej bazie danych `fiszki.db`.

### 🧠 Tryby Nauki
1.  **📝 Quiz (ABCD):** Klasyczny wybór jednej z czterech odpowiedzi. Idealny na początek nauki z nowym materiałem.
2.  **⌨️ Wpisywanie:** Wymaga wpisania poprawnego tłumaczenia z klawiatury. Najskuteczniejsza metoda na utrwalenie poprawnej pisowni.
3.  **🧩 Dopasowania:** Dynamiczna gra logiczna, w której musisz połączyć w pary rozrzucone kafelki z angielskimi i polskimi słówkami.
4.  **📄 Test ABCD:** Kompleksowy sprawdzian wiedzy z podsumowaniem wyników, statystyką procentową i możliwością przejrzenia błędów.

### 🛠️ Zaawansowane Funkcje
* **Inteligentne Powtórki:** W trybach Quiz i Wpisywanie program automatycznie tworzy nową turę z wyrazów, w których popełniłeś błąd.
* **System Pauzy:** Możesz przerwać naukę w dowolnym momencie i wrócić do niej później – program zapyta, czy chcesz kontynuować zapisaną sesję.
* **Dwukierunkowość:** Nauka z polskiego na angielski lub odwrotnie (przełączane jednym przyciskiem).
* **Personalizacja:** Regulacja skali interfejsu (100-150%) oraz czasu wyświetlania poprawnej odpowiedzi po błędzie.

---

## 🚀 Jak zacząć?

### Wymagania
* System operacyjny: Windows

### Instalacja i Uruchomienie
1.  Pobierz plik exe z zakładki `Releases`.
2.  Uruchom program. Przy pierwszym starcie aplikacja automatycznie utworzy niezbędne pliki konfiguracji i bazę danych.

---

## 🎨 Technologie
* **Język:** Python 3.x
* **Interfejs:** CustomTkinter (Modern UI)
* **Baza danych:** SQLite3

---

## 📝 Notatki deweloperskie
Program został zaprojektowany z myślą o prostocie i szybkości działania. Dzięki zastosowaniu **CustomTkinter**, aplikacja wspiera tryb ciemny i jasny (zgodnie z ustawieniami systemu Windows).
