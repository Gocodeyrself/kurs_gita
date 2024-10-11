W konfiguracji ftp-simple w Visual Studio Code, opcje autosave i confirm dotyczą sposobu, w jaki rozszerzenie zarządza zapisywaniem i wysyłaniem plików na serwer FTP. Oto szczegółowe wyjaśnienia obu opcji:

1. autosave: true/false
autosave: true – Jeśli ta opcja jest ustawiona na true, rozszerzenie ftp-simple automatycznie zapisze plik na serwerze FTP za każdym razem, gdy dokonasz zmian w pliku lokalnym i zapiszesz go w edytorze. Nie musisz ręcznie wysyłać plików na serwer po ich edycji. To wygodne rozwiązanie, jeśli chcesz mieć pewność, że zawsze pracujesz na najnowszej wersji pliku na serwerze.

autosave: false – Jeśli ta opcja jest ustawiona na false, pliki lokalne nie będą automatycznie przesyłane na serwer po ich zapisaniu. Będziesz musiał ręcznie przesłać plik na serwer, co daje większą kontrolę, ale wymaga dodatkowych kroków.

2. confirm: true/false
confirm: true – Jeśli ta opcja jest ustawiona na true, przed wysłaniem pliku na serwer FTP (np. przy autosave lub ręcznym wysłaniu pliku) rozszerzenie wyświetli okno dialogowe z prośbą o potwierdzenie operacji. Jest to dodatkowe zabezpieczenie, które pozwala upewnić się, że chcesz faktycznie wysłać plik na serwer.

confirm: false – Jeśli ta opcja jest ustawiona na false, pliki będą przesyłane na serwer FTP bez konieczności potwierdzania operacji. To przyspiesza proces pracy, ale zmniejsza kontrolę nad tym, kiedy pliki są wysyłane.
