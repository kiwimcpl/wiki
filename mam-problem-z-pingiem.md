---
icon: wifi-slash
---

# Mam problem z pingiem

### Dostawca internetu, połączenie (światłowód/miedź/radio/mobilny itp.)

Tu najlepiej wejść na stronę [https://www.maxmind.com/en/locate-my-ip-address](https://www.maxmind.com/en/locate-my-ip-address)

Potrzebujemy jedynie informacji z pól ISP oraz Connection type.

Wyślij te informacje na naszego discorda (nie zamieszczaj **ŻADNYCH** adresów IP) oraz to czy jesteś połączony po wifi czy po kablu, a jeśli masz możliwość - czy sprawdzałeś czy po przesiadce z wifi na kabel sytuacja się poprawiła

### Modpack

Jeśli grasz na jakimś modpacku, możliwe że zainstalowane mody powodują jakieś problemy. Sprawdź czy na vanilii występuje ten sam problem.

### Jeśli problem występuje w jakimś konkretnym miejscu

Kliknij F3 podczas gry i sprawdź wartości tx i rx w trzeciej linii (obok "Paper server"), tx to ilość pakietów które ty wysyłasz do serwera (i ta wartość rzadko kiedy przekracza 30) a rx to otrzymywane od niego - w normalnej sytuacji nie więcej niż 300-400

<figure><img src=".gitbook/assets/Screenshot 2024-05-10 at 20.58.49.png" alt=""><figcaption><p>Wartości w normalnej sytuacji</p></figcaption></figure>

<figure><img src=".gitbook/assets/Screenshot 2024-05-10 at 20.59.34.png" alt=""><figcaption><p>Potencjalnie problematyczna sytuacja</p></figcaption></figure>

Na pierwszym screenshoocie widać wartości z stania sobie gdzieś w okolicach spawnu, na drugim stanie nad składającą się z kilkuset upchanych krów farmy. W tej drugiej sytuacji gra musi przetworzyć więcej rzeczy i co najważniejsze - muszą one do niej na pewno dotrzeć, w przeciwnym wypadku serwer będzie musiał wysłać je ponownie tworząc lag.
