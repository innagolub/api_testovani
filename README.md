# Projekt 2 – Testování REST API

Tento projekt se zaměřuje na testování REST API aplikace pro správu studentů.

## Rozsah testování
Byly testovány následující metody:
- GET – získání dat studenta
- POST – vytvoření studenta
- PUT – aktualizace studenta (partial i full update)
- DELETE – smazání studenta

## Testovací přístup
Testování zahrnovalo:
- pozitivní scénáře (úspěšné operace)
- negativní scénáře (chybové stavy)
- edge cases
- ověření konzistence dat pomocí SQL dotazů

## Použité nástroje
- Postman (testování API)
- DBeaver (ověření dat v databázi)

## Výstup
Výsledkem je PDF dokument obsahující:
- testovací scénáře
- exekuci testů
- identifikované chyby (bug report)

Během testování bylo odhaleno několik chyb API, včetně nesprávných status kódů a nekonzistence při práci s daty.
