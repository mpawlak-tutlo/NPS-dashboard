# 📊 NPS Dashboard — Tutlo

Interaktywny dashboard do analizy wyników badań NPS (Net Promoter Score). Umożliwia przeglądanie i kategoryzowanie feedbacków klientów według zdefiniowanej taksonomii, segmentów badania oraz zespołów odpowiedzialnych za dany obszar.

---

## 🚀 Jak uruchomić

Plik działa lokalnie — nie wymaga instalacji ani serwera.

1. Pobierz plik `nps-dashboard.html`
2. Otwórz go w przeglądarce (Chrome / Edge / Firefox)
3. Gotowe — dashboard działa w całości w przeglądarce

> ⚠️ Plik przeznaczony wyłącznie do użytku wewnętrznego. Nie udostępniać na zewnątrz.

---

## 📋 Funkcje

- **Przegląd** — ogólny NPS, rozkład promotorów / pasywnych / krytyków
- **Trendy** — wykresy zmian NPS w czasie
- **Kategorie** — analiza feedbacków według 23 kategorii tematycznych
- **Zespoły** — widok feedbacków przypisanych do konkretnych zespołów
- **Odpowiedzi** — tabela wszystkich feedbacków z filtrowaniem i wyszukiwaniem (1 wiersz = 1 kategoria)
- **Wskazówki** — automatyczne rekomendacje na podstawie danych

---

## 🗂️ Segmenty badania

| Segment | Opis |
|---|---|
| NPS Onboarding | Pierwsze tygodnie nauki — start, pierwsze lekcje, kontakt z opiekunem |
| NPS Współpracy | W trakcie trwania kursu — jakość lekcji, zaangażowanie, postępy |
| NPS Zakończenia kursu | Po zakończeniu kursu — ocena całości, certyfikat, progres |
| NPS Odnowień | Klienci, którzy zdecydowali się odnowić umowę |
| NPS Rezygnacji | Klienci, którzy zrezygnowali — kluczowe powody odejścia |

---

## 🏷️ Taksonomia kategorii

| Kategoria | Opis |
|---|---|
| sprzedaż | Informacje o procesie sprzedaży, obietnicach przy zawieraniu umowy, wdrożeniu klienta w usługę |
| lekcje | Feedbacki do czasu i formy lekcji (bez lektora i materiałów) |
| lektor | Każdy feedback dotyczący lektora, nauczyciela, tutora |
| lekcje grupowe | Feedbacki wprost dotyczące lekcji grupowych |
| opiekun/brak opiekuna | Osoba wspierająca klienta, dbająca o kontakt, weryfikację progresu i wsparcie |
| brak czasu | Klient sygnalizuje brak czasu na korzystanie z usługi |
| brak kontaktu | Klient zauważa brak kontaktu ze strony Tutlo |
| brak motywacji | Klientowi lub jego dziecku brakuje motywacji do nauki |
| brak wsparcia/zainteresowania | Klient wskazuje na brak zaangażowania ze strony firmy |
| cena | Uwagi do ceny usługi |
| dostępność | Dostępność lektorów, godziny, możliwość wyboru |
| elastyczność | Możliwość zmiany terminów, planu nauki, warunków |
| finansowanie | Uwagi do formy płatności, kredytu, rat |
| forma nauki | Kwestie związane z formą nauki inne niż pozostałe kategorie |
| formalności i umowa | Długość umowy, zapisy, aneksy, warunki rezygnacji |
| funkcje Platformy | Feedback do platformy, funkcji, dostępnych narzędzi |
| materiały | Materiały edukacyjne używane przez lektorów i uczniów, materiały do pracy własnej |
| jakość obsługi | Uwagi do obsługi klienta, szybkości kontaktu, dostępnych form kontaktu |
| problemy techniczne | Trudności techniczne: dźwięk, obraz, łączenie, odtwarzanie |
| niespełnione obietnice | Obietnice bez pokrycia spoza pozostałych kategorii |
| program poleceń | Feedbacki o programie poleceń, nagrodach, formie zbierania |
| progres | Postępy ucznia, zmiana poziomu, efekty nauki |
| wygoda | Ogólna wygoda korzystania z usługi (gdy źródło nie jest jednoznaczne) |

---

## 👥 Zespoły

| Zespół | Kategorie |
|---|---|
| Materiały | materiały, lektor, lekcje grupowe |
| Platforma | problemy techniczne, funkcje Platformy |
| Lektorzy | lektor, lekcje grupowe, dostępność, brak motywacji |
| Sprzedaż | sprzedaż, niespełnione obietnice, opiekun/brak opiekuna, finansowanie, brak kontaktu |
| Formalności i umowa | formalności i umowa |
| Obsługa | jakość obsługi, brak kontaktu, opiekun/brak opiekuna, brak wsparcia/zainteresowania |
| Ogólna | progres, forma nauki, elastyczność, wygoda, lekcje |

---

## 📁 Pliki

| Plik | Opis |
|---|---|
| `nps-dashboard.html` | Główny plik dashboardu — otwórz w przeglądarce |
| `nps-kategoryzacja.csv` | Plik CSV z odpowiedziami i przypisanymi kategoriami |

---

## 🛠️ Technologie

- **HTML / CSS / JavaScript** — bez frameworków, działa offline
- **Chart.js 4.4.1** — wykresy (trend, donut, bar)
- **Inter** — czcionka (Google Fonts)

---

## 📌 Dane

Dashboard zasilany jest danymi z ankiet NPS przeprowadzanych w 5 momentach cyklu życia klienta. Każda odpowiedź może być przypisana do wielu kategorii — w widoku tabelarycznym jeden feedback pojawia się raz na każdą przypisaną kategorię.

Dane są przetwarzane wyłącznie lokalnie w przeglądarce użytkownika.
