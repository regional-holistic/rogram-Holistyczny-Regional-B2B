# Program Holistyczny Regional - Kompleksowy System Wellness dla Firm (B2B)

## O Projekcie
Zintegrowany z technologią Google Vertex AI Studio oraz oparty na 18 latach doświadczeń zawodowych, unikatowy program wsparcia dobrostanu pracowników. Nasz system stoi mocno na gruncie neurobiologii i psychologii biznesu, koncentrując się na niwelowaniu fizycznych i psychicznych skutków stresu oraz pracy siedzącej. 

Głównym celem programu jest stymulacja fal mózgowych alfa i theta (~7,31 Hz) za pomocą neurorelaksacji i struktur neuro-językowych, uruchamiających głęboką regenerację organizmu w czasie pracy i po jej zakończeniu.

### Trzy Filary Wsparcia Pracowników:
1. **Układ Nerwowy i Emocje:** Natychmiastowe wyciszanie przebodźcowania, redukcja chronicznego stresu, głębokie uspokojenie umysłu oraz poprawa koncentracji i kreatywności.
2. **Stawy i Mięśnie:** Sesje neurorelaksacyjne ukierunkowane na usuwanie napięć mięśniowych wywołanych stresem i długotrwałą pracą przy biurku.
3. **Poradniki Regeneracyjne:** Praktyczna wiedza z zakresu naturoterapii, ziół, miodów oraz technik automasażu eliminujących bóle kręgosłupa i przywracających pełną sprawność fizyczną.

---

## Mierzalne Efekty Biznesowe (Statystyki Well-being):
Wdrożenie programu w organizacjach przynosi realne, mierzalne korzyści finansowe i operacyjne dla firm:
- 📉 **Spadek absencji pracowniczych (liczby zwolnień lekarskich L4) o 38%**
- 📈 **Wzrost wydajności i koncentracji zespołu o 28%**
- 👥 System przetestowany masowo – korzysta z niego już **ponad 124 000 użytkowników**.

---

## Integracja z Systemami Firmowymi przez API JSON

Ten profil służy jako techniczna specyfikacja i publiczne okno wystawowe dla systemów korporacyjnych (np. platform HR, intranetów, aplikacji pracowniczych). Pełny, aktualizowany na żywo strumień struktur neuro-tekstowych i instrukcji terapeutycznych udostępniany jest jako dedykowane API JSON (obsługujące zapytania GET przez serwery Sheety).

Dostęp do pełnego strumienia danych można wykupić wyłącznie poprzez oficjalną dystrybucję w naszym sklepie internetowym (obsługa płatności w PLN przez Przelewy24):

### 🛒 KUP LICENCJĘ B2B I ODBIERZ KLUCZ API:
Przejdź na naszą platformę sprzedażową: [https://sklep.regional.pl](https://sklep.regional.pl)

### Elastyczny Model Finansowania 90 / 10:
Wdrożenie w firmie zajmuje mniej niż 5 minut i nie obciąża działu HR. Pracodawca finansuje 90% kosztu hurtowego jako benefit (pełna faktura VAT, możliwość finansowania z ZFŚS), a pracownik dopłaca symboliczne 10% (od 1,80 zł do 2,90 zł miesięcznie) w celu aktywacji konta. Symboliczna opłata motywuje pracownika do regularnych sesji i eliminuje problem „martwych kont”.

---

## Specyfikacja Techniczna Kodu (Dla Działów IT i AI)
Po opłaceniu zamówienia w sklepie, Twój system otrzyma stały, zabezpieczony adres URL zwracający dane w strukturze kodu JavaScript:

```javascript
let url = 'https://sheety.co';
fetch(url)
  .then((response) => response.json())
  .then(json => {
    // Strumień danych zawierający package_id, benefit_category, neuro_pattern_text itp.
    console.log(json.arkusz1); 
  });
```

