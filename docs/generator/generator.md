# Generowanie napisów do plików Audio lub Video

Aplikacja umożliwia kompleksową pracę z materiałami video, automatyczną transkrypcją oraz edycją napisów. Po przesłaniu pliku video przez użytkownika, film zostaje natychmiast wyświetlony w interfejsie aplikacji. System automatycznie wyodrębnia z niego ścieżkę dźwiękową, która również jest dostępna do odsłuchu.

Następnie wykorzystujemy model speech-to-text do wygenerowania wstępnych napisów na podstawie dźwięku. Transkrypcja pojawia się bezpośrednio w aplikacji, gdzie użytkownik może ją dowolnie poprawiać i edytować.

Po zakończeniu edycji napisy można zapisać / pobrać w popularnych formatach — SRT oraz VTT. Aplikacja pozwala także na podgląd materiału wideo z naniesionymi napisami w wbudowanym odtwarzaczu, co ułatwia ocenę efektu końcowego.

Dodatkowo użytkownik ma możliwość pobrania gotowego, wygenerowanego filmu z dołączonymi napisami, dzięki czemu cały proces — od transkrypcji po renderowanie finalnego materiału — odbywa się w jednym miejscu.


## Instrukcja obługi:
### ***Wymagane wprowadzenie klucza OpenAI przez użytkownika!***

    1. Wybierz plik wideo (`mp4`, `mp3`, `avi`, `mov`, `mkv`).  
    2. Odtwórz film i audio, sprawdź czy działa.  
    3. Wygeneruj napisy automatycznie (Whisper AI).  
    4. Edytuj napisy jeśli trzeba.  
    5. Zapisz i pobierz w formacie `.srt` lub `.vtt`.  
    6. Podejrzyj film z napisami w playerze HTML5.  
    7. Kliknij ➕ Wczytaj kolejne wideo, aby rozpocząć od nowa.

<a href="https://github.com/gitkol2002/generator_napisow" class="md-button md-button--primary">Kod programu</a>

