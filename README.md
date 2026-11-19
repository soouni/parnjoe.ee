# Pärnjõe Jahiseltsi koduleht (demo)

Avalehe demo aadressile **www.parnjoe.ee**. Jahikaart jääb eraldi aadressile `jaht.parnjoe.ee`.

- `index.html` on iseseisev staatiline leht: üks fail, ei vaja ehitust ega sõltuvusi (v.a Google Fonts).
- Kõik seaded (järgmise jahi aeg, teadete riba, jahihooajad, galerii) on faili lõpus olevas skriptis plokis `Seaded`.
- Kohatäitjad on nurksulgudes, näiteks `[NIMI]`, `[KOOD]`, `[Kohanimi]`.

## Enne avaldamist

1. Täida nurksulgudes kohatäitjad päris andmetega.
2. **Jahihooajad on näidisandmed.** Kontrolli need kehtiva jahieeskirja järgi üle.
3. Jahikoodi kast on praegu demo (kood `1234`). Päriselt kontrollib koodi jahikaardi rakendus. Kas kood suunatakse `jaht.parnjoe.ee`-sse või jäetakse ainult nupp „Ava jaht“, on veel otsustamata.
4. Galerii fotod on kohatäitjad.

## Avaldamine

Leht avaldatakse GitHub Pagesiga harust `main` (juurkaust). Domeen on failis `CNAME` (`www.parnjoe.ee`). Jahikaart elab eraldi repos `soouni/jahiselts` aadressil `jaht.parnjoe.ee`.

Lähtekoht: Claude'i disainilõuendi „Demo – elav avaleht“, mis on teisendatud iseseisvaks HTML-iks.
Dekoratiivsed metsasiluetid ja kõrgusjooned genereeritakse brauseris.
