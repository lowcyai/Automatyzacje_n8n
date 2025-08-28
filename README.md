n8n ma wersję open-source (darmową) którą możesz hostować samodzielnie oraz płatną wersję Cloud. Do celów nauki wystarczy wersja darmowa.

# Automatyzacje n8n – przykłady z bloga lowcyai.pl

Repozytorium zawiera automatyzacje i workflow prezentowane na blogu [lowcyai.pl](https://lowcyai.pl), głównie dla n8n. Znajdziesz tu gotowe przykłady, które możesz zaimportować do swojej instancji n8n.

## Przykłady automatyzacji

- Publikacja postów na WordPress z AI
- Automatyczne generowanie obrazów do wpisów
- Dystrybucja treści na social media
- Planowanie publikacji i kolejka postów
- Powiadomienia o statusie publikacji

## Jak korzystać?

1. Pobierz wybrany plik workflow (np. `simple-blog-post.json`)
2. Zaimportuj go w n8n przez "Import Workflow"
3. Uzupełnij swoje dane (API, klucze, itp.)
4. Uruchom i testuj automatyzację

Przykładowy input do webhooka:
```json
{
  "title": "Automatyczny post z n8n",
  "keywords": "n8n, automatyzacja, blog",
  "wordCount": 500,
  "language": "pl"
}
```

Więcej przykładów i instrukcji znajdziesz na [lowcyai.pl](https://lowcyai.pl).

## Kontakt

Masz pytania lub chcesz zgłosić pomysł? Napisz na [kontakt@lowcyai.pl](mailto:webmaster@lowcyai.pl) lub przez [lowcyai.pl](https://lowcyai.pl).

---

**Repozytorium powstało jako wsparcie dla czytelników bloga lowcyai.pl.**