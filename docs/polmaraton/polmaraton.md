# Predykcja czasu półmaratonu

Aplikacja Streamlit pozwala użytkownikowi szybko uzyskać predykcję:
Wejście: pole tekstowe, w którym użytkownik opisuje siebie (np. imię, płeć, wiek, czas 5 km).

Jeśli brakuje wymaganych danych — aplikacja informuje użytkownika, jakie informacje trzeba uzupełnić.
Korzysta z LLM (OpenAI) do automatycznego wyłuskania wymaganych pól i zwraca je w postaci słownika/JSON.
Wywołuje model (lokalny / pobrany ze Spaces) i zwraca przewidywany wynik.
Integracja z Langfuse: rejestruje i zbiera metryki działania LLM (np. trafność ekstrakcji, czas odpowiedzi), co pozwala monitorować i poprawiać część NLP.

Przyjazna aplikacja webowa, wdrożona na DigitalOcean App Platform, z monitorowaniem jakości ekstrakcji LLM i wersjonowaniem modelu.

<a href="https://github.com/gitkol2002/polmaraton" class="md-button md-button--primary">Kod programu</a>

