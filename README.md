# ceneo-feed

Plik XML z ofertami Margot System dla Ceneo:
**https://zhuartel-hue.github.io/ceneo-feed/ceneo.xml**

Shopify blokuje roboty (błąd 429/403), więc co godzinę GitHub Actions
pobiera plik `https://margotsystem.com/collections/wolnostojace?view=ceneo`,
sprawdza, czy to poprawny XML z ofertami, i publikuje kopię na gałęzi `gh-pages`.
Jeśli pobranie się nie uda, zostaje poprzednia wersja.
