# Funkcionalnosti – Pixel Corner

Pixel Corner je spletna trgovina za ljubitelje video iger. Prodaja nove in rabljene igre, konzole ter dodatke, posebej pa izpostavlja retro opremo (SNES, PlayStation 1, Sega Mega Drive, Game Boy ...). V tej datoteki so zbrane funkcionalnosti, ki jih nameravamo narediti. Prioriteta pove, kako nujna je posamezna funkcionalnost: **visoka** pomeni, da brez nje stran ne deluje kot trgovina, **srednja** pomeni, da je zelo koristna, **nizka** pa, da jo dodamo, če nam ostane čas.

## Seznam funkcionalnosti

| ID  | Ime | Opis | Prioriteta |
|-----|-----|------|------------|
| F01 | Domača stran | Uporabnik na prvi strani vidi pasico s ponudbo, glavne kategorije in nekaj izpostavljenih izdelkov. Od tu z enim klikom pride v trgovino. | Visoka |
| F02 | Navigacijski meni | Na vrhu vsake strani je enak meni (Domov, Trgovina, O nas, Kontakt) in gumb za košarico, da se uporabnik nikoli ne izgubi. | Visoka |
| F03 | Seznam izdelkov | Uporabnik v trgovini vidi vse izdelke kot kartice s sliko, imenom, ceno in gumbom »V košarico«. | Visoka |
| F04 | Podrobnosti izdelka | S klikom na izdelek se odpre stran z večjimi slikami, opisom, platformo, stanjem (novo ali rabljeno) in zalogo. | Visoka |
| F05 | Košarica | Uporabnik doda izdelke v košarico, spreminja količino, jih odstrani in vidi skupno ceno z dostavo. | Visoka |
| F06 | Kontaktni obrazec | Na strani Kontakt uporabnik vpiše ime, e-pošto in sporočilo ter ga pošlje trgovini. Po pošiljanju dobi potrditev. | Visoka |
| F07 | Filtriranje izdelkov | Uporabnik omeji seznam po kategoriji, platformi, stanju in ceni, da hitreje najde, kar išče. | Srednja |
| F08 | Iskanje | V iskalno polje v glavi vpiše ime igre ali konzole in dobi seznam zadetkov. | Srednja |
| F09 | Razvrščanje | Seznam izdelkov lahko uredi po ceni (naraščajoče ali padajoče) ali po datumu dodajanja. | Srednja |
| F10 | Prilagodljiv prikaz | Stran se pravilno prikaže na računalniku, tablici in telefonu (meni se na telefonu skrije pod gumb). | Srednja |
| F11 | Oznaka stanja pri rabljenih izdelkih | Pri vsakem rabljenem izdelku piše, ali je testiran, ali ima originalno škatlo in v kakšnem stanju je ohišje. | Srednja |
| F12 | Podobni izdelki | Na strani izdelka se pod opisom pokažejo izdelki za isto platformo (npr. igre za SNES pod konzolo SNES). | Nizka |
| F13 | Stran O nas | Uporabnik prebere, kdo smo, kje smo in kako preverjamo rabljeno opremo, preden jo prodamo. | Nizka |
| F14 | Blagajna | Uporabnik vpiše podatke za dostavo, izbere način plačila in odda naročilo. To je predvideno za naslednjo fazo projekta. | Nizka |

## Opombe

- Funkcionalnosti F01–F06 so osnova, ki jo naredimo najprej. Domača stran in stran Kontakt sta že odprti kot issue na GitHubu.
- Košarica (F05) bo v prvi verziji delovala samo v brskalniku (shranjena v `localStorage`), brez prave baze in plačila.
