#Kalkulačka v html a php
## Ondřej Belatka 58792
###HTML struktura: HTML stránka obsahuje formulář, ve kterém jsou vstupní pole pro zadání čísel a výběr operátoru, a tlačítko pro odeslání formuláře. Tento formulář je odesílán metodou POST.

PHP zpracování: Když uživatel odešle formulář, PHP skript na straně serveru zpracuje data. Kód načte hodnoty zadaných čísel a operátoru pomocí metody POST.

Provedení operace: PHP skript provede matematickou operaci podle zvoleného operátoru. To je provedeno pomocí příkazu switch, který vyhodnotí hodnotu operátoru a provede odpovídající operaci (+, -, *, /).

Výstup výsledku: Výsledek operace je pak zobrazen na stránce pomocí PHP skriptu, který vytvoří odpovídající HTML kód a vloží výsledek do odpovídajícího místa na stránce.

http://calcu.great-site.net/
