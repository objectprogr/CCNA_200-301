# Wartswa aplikacji
Warstwa ta prezentuje aplikację oraz interfejs, z którym użytkownik ma do czynienia poprzez
generowanie ruchu i przetwarzanie otrzymanych danych. W tej warstwie użytkownik wybiera
odpowiednią aplikację oraz wykonuje określone czynności, które potem mają wpływ na działanie
warstw niższych. Wybór aplikacji uzależniony jest od potrzeb użytkownika — może to być
na przykład chęć wyświetlenia strony WWW lub rozpoczęcie komunikacji z serwerem FTP.
W takim przypadku użytkownik, poprzez uruchomienie przeglądarki internetowej (ang. web
browser), rozpoczyna generowanie ruchu, wykorzystując do tego najpopularniejszy w tej warstwie
protokół HTTP (ang. Hypertext Transfer Protocol). Pobranie zasobów strony internetowej odbywa
się po podaniu odpowiedniego adresu strony, zwanego URL (ang. Uniform Resource Locator).
Użytkownik może też skorzystać z klienta FTP i rozpocząć komunikację z serwerem. Następnie
warstwa aplikacji przekazuje informacje i dane niższej warstwie. Ponadto warstwa aplikacji jest
odpowiedzialna za sprawdzenie, czy program sieciowy ma zasoby systemowe odpowiednie do obsłużenia
całej komunikacji.