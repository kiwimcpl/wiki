---
icon: shop
---

# Sklepy graczy

### Kupujący/sprzedający

#### Jak coś kupić lub sprzedać z/do sklepu?

Znajdź sklep i kliknij na tabliczkę, rozpocznie się transakcja. Zostaniesz poproszony o podanie liczby przedmiotów które chcesz kupić lub sprzedać.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Wpisz `0` lub odejdź od sklepu aby anulować transakcje. Wpisanie dowolnej liczby innej niż 0 spowoduje zakończenie transakcji i zakup/sprzedaż przedmiotu.

### Handlarze

#### Jak stworzyć swój sklep?

{% hint style="danger" %}
Utworzenie sklepu kosztuje $5 a utworzyć może go jedynie właściciel danej wyspy. Opłata nie jest zwracana przy usunięciu sklepu.
{% endhint %}

1. Idź na swoją wyspę
2. Postaw skrzynie
3. Weź do ręki JEDNĄ SZTUKĘ przedmiotu który planujesz sprzedawać i wpisz `/shop create [cena za sztuke]`.\
   Jeśli w ręku będzie więcej niż jedna sztuka, stworzysz sklep w którym sprzedajesz x sztuk przedmiotu za wpisaną cenę, np. trzymając 40 cobbla wpisujesz `/shop create 5`, tworzysz sklep w którym sprzedajesz cobble w pakietach po 40 sztuk za $5.
4. Stworzyłeś sklep, teraz otwórz skrzynie i włóź do niej przedmioty

#### Jak zmienić cene w sklepie?

Spójrz na swój sklep i wpisz `/shop price [nowa cena]`. Minimalna dozwolona cena to $0.01.

#### Jak usunąć sklep?

Spójrz na swój sklep i wpisz `/shop remove`. Opłata za stworzenie sklepu nie jest zwracana.

#### Jak zmienić typ sklepu?

Aby zmienić typ sklepu spójrz się na sklep i wpisz:

* `/shop buy` jeśli chcesz aby inni sprzedawali przedmioty Tobie.
* `/shop sell` jeśli chcesz aby inni kupowali przedmioty od Ciebie (domyślny typ sklepu)
