# BEM according to Codeloop

Main idea of BEM (Block__Element--Modifier) approach is ...

## Namespacing (js-hooks)

## Encapsulation and specificity (avoid nesting components)

## Wrappers (l-*) (wewn. _c-block.scss zdefiniowany)

## HTML

## Styling (Main.scss + _partial.scss)
podział na pliki - kazdy blok osobno

### General approach in sass (.block -> &__element + &--element-modifier -> &--modifier)

### _general.scss

### _layout.scss

### _helpers.scss
kolory
oprócz zastosowanego rozwiązania z rozmiarami fontów, podać alternatywne (h-txt-12, etc. do kontroli rozmiaru,)

###  _fonts.scss
oprócz zastosowanego rozwiązania z rozmiarami fontów, podać alternatywne (h-txt-12, etc. do kontroli rozmiaru,)



*References:*

1. [*Battling BEM CSS: 10 Common Problems And How To Avoid Them*](https://www.smashingmagazine.com/2016/06/battling-bem-extended-edition-common-problems-and-how-to-avoid-them/)


Dwa blogposty:

-BEM (helpery, grafika x2/3 (osobno c-section, osobno lista z kontaktu + lista z certyfikatów jako wariacja) unikanie nestowania komponentów -> encapsulation + specificity)

-Czego się nauczyliśmy w projekcie (np. wczyytwanie fontów (swap), wczytywanie stylów nie, tłumaczenia, _variables.scss, customization of Bootstrap)