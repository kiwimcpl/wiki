---
description: Inaczej działki.
---

# Claimy

Na serwerze istnieje możliwość zabezpieczenia terenu i udostępnienia go wyłącznie wybranym osobom. Wykorzystujemy w tym celu popularny plugin [GriefPrevention](https://www.spigotmc.org/resources/griefprevention.1884/) znany głównie z anglojęzycznych survivali/freebuildów.

## Jak zabezpieczyć teren?

Potrzebujesz do tego dwóch rzeczy:

* złotej łopaty
* conajmniej 100 claim bloków (widoczne na sidebarze, co kilka minut wszyscy gracze online otrzymują dodatkowe bloki)

Minimalne pole claimu wynosi 100 bloków a minimalna wielkość boku to 5 klocków. Oznacza to że pole zabezpieczanego terenu musi wynosić 100 klocków (bok 1 \* bok 2), np. 10x10 lub 5x20, dla przykładu użyjemy terenu 10x10

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Teraz weź łopatę i kliknij prawym w obu bokach, zostanie utworzony claim.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

## Jak dodać kogoś do claima?

Wystarczy że znajdując się na swoim claimie wpiszesz polecenie `/trust` oraz nick tej osoby, np. `/trust artur9010`

Aby odebrać komuś uprawnienia do naszego terytorium należy zamiast polecenia `/trust` użyć `/untrust`

Jeśli wpisując te polecenia będziemy znajdować się poza naszą działką - nadamy uprawnienia do wszystkich należących do nas terenów.

## Jak podejrzeć granicę claimu?

Najprościej będzie wziąć złotą łopatę i kliknąć nią prawym pod siebie stojąc wewnątrz claimu, otrzymamy błąd a plugin podświetli nam granicę działki glowstone.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

## Jak zmniejszyć lub rozszerzyć claim?

Możliwości są dwie, komendą albo łopatą.

**Opcja 1: komendą (co polecamy, jest najwygodniej przy większych claimach)**

Popatrz się w kierunku w którym chcesz rozszerzyć/zmniejszyć claim i wpisz `/extendclaim <ilość klocków>`, jeśli podasz ujemną liczbę to claim się zmniejszy.

**Opcja 2: łopatą**

Weź złotą łopatę i kliknij prawym w róg claimu (patrz. "Jak podejrzeć granicę claimu?") a następnie kliknij prawym w miejscu gdzie ma się znajdować nowy róg claimu.

## Jak porzucić claim?

{% hint style="danger" %}
**POLECENIE PODANE NIŻEJ NIE WYMAGA POTWIERDZENIA, PO JEGO WPISANIU CLAIM ZOSTANIE USUNIĘTY A TEREN BĘDZIE NIEZABEZPIECZONY.**
{% endhint %}

Jeśli nie potrzebujesz już danego claimu (a pamiętaj że możesz mieć ich maksymalnie 5) to możesz go usunąć stając na nim i wpisując polecenie /abandonclaim

## Utknąłem na czimś claimie, co robić?

Wpisz polecenie `/trapped`, zostaniesz wyteleportowany poza claim. Możesz także teleportować się w dowolne inne miejsce np. /spawn

## Jak zdobyć claimbloki?

Claimbloki otrzymać można za:

* grę na serwerze, w ciągu godziny możesz otrzymać 180 claim bloków za sam fakt bycia online
* kopanie i budowanie, istnieje niewielka szansa że podczas budowania lub niszczenia klocków otrzymasz dodatkowe claimbloki (od 1 do 7 sztuk)

## Czy mogę komuś oddać swoje claim bloki?

Tak, jeśli posiadasz conajmniej 500 claim bloków to możesz je przelać komuś innemu poleceniem `/giveblocks <nick> <ilość>`. Wymóg przelania minimum 500 bloków uniemożliwia spam poleceniem i utrudnia nabijanie claim bloków poprzez tworzenie nowych kont.
