---
description: Lista komend dostępnych na serwerze
hidden: true
---

# Komendy - smp

## Czat

| Komenda                    | Opis                                                                                                                                                        |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /msg \<gracz> \<wiadomość> | Wysyła prywatną wiadomość do innego gracza                                                                                                                  |
| /r \<wiadomość>            | Odpisuje na ostatnią otrzymaną prywatną wiadomość                                                                                                           |
| /ignore \<gracz>           | Blokuje możliwość pisania do nas prywatnych wiadomości przez innego gracza. Ukrywa także jego wiadomości na czacie                                          |
| /msgtoggle                 | Włącza lub wyłącza możlwiość pisania do nas wiadomości prywatnych                                                                                           |
| /rtoggle                   | Zmienia tryb działania polecenia /r - albo odpisujemy wtedy ostatniej osobie która do nas napisała albo odpisujemy ostatniej osobie do której my pisaliśmy. |

## Ekonomia

## Działki

Więcej informacji na dedykowanej podstronie:

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}

## Teleportacja

| Komenda           | Opis                                                                                                                                                                                                                   |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /tptoggle         | Włącza lub wyłącza możliwość wysyłania zapytań o teleportacje                                                                                                                                                          |
| /tpa \<gracz>     | Wysyła zapytanie o teleportacje do innego gracza. Po jego zaakceptowaniu TY zostaniesz przeteleportowany.                                                                                                              |
| /tpahere \<gracz> | Wysyła zapytanie o teleportacje do innego gracza. Po jego zaakceptowaniu wpisany gracz zostanie przeteleportowany DO CIEBIE.                                                                                           |
| /tpaccept         | Akceptuje prośbę o teleportacje.                                                                                                                                                                                       |
| /tpacancel        | Odrzuca prośbę o teleportacje.                                                                                                                                                                                         |
| /spawn            | Teleportuje Cię na spawn.                                                                                                                                                                                              |
| /warp             | Wyświetla listę publicznie dostępnych punktów.                                                                                                                                                                         |
| /warp \<nazwa>    | Teleportuje Cię do konkretnego publicznie dostępnego punktu                                                                                                                                                            |
| /tpr              | Teleportuje Cię w losowe miejsce na mapie.                                                                                                                                                                             |
| /home             | Teleportuje Cię do domu, lub wyświetla listę domów jeśli masz więcej niż jeden.                                                                                                                                        |
| /home \<nazwa>    | Teleportuje Cię do wybranego domu                                                                                                                                                                                      |
| /sethome \<nazwa> | <p>Ustawia nowy dom w punkcie w którym stoisz<br><a data-footnote-ref href="#user-content-fn-1"><mark style="color:red;"><strong>To polecenie jest dostępne wyłącznie na głównej mapie (world)</strong></mark></a></p> |
| /delhome \<nazwa> | Usuwa dom o konkretnej nazwie.                                                                                                                                                                                         |

Dodatkowo pod komendą `/gwarp` znajdziesz [warpy-graczy.md](warpy-graczy.md "mention")

[^1]: 
