# PPS2 — Vežbe (HTML prezentacije)

Materijali sa vežbi iz predmeta **Planiranje prostora i saobraćaja 2**.
Svaka vežba je jedan samostalan HTML fajl (radi offline, bez ikakvih zavisnosti).

## Struktura

```
index.html        — početna strana sa spiskom svih vežbi
vezba-01.html     — Vežba 1: Vremenska i prostorna akumulacija
_template.html    — šablon za nove vežbe (ne linkuje se sa index strane)
```

## Korišćenje

Otvoriti `index.html` (ili direktno `vezba-XX.html`) u bilo kom browseru.

Navigacija kroz slajdove:
- strelice `←` `→` (ili `↑` `↓`), `Space`, `PageUp`/`PageDown` (radi i sa prezenterom/klikerom)
- `Home`/`End` — prvi/poslednji slajd
- skrol mišem ili prevlačenje na telefonu
- `Ctrl+P` — štampa/PDF (jedan slajd = jedna strana)

## Dodavanje nove vežbe

1. Kopirati `_template.html` kao `vezba-XX.html`
2. Izmeniti `<title>`, naslovni slajd i sadržaj — šablon sadrži primere svih
   komponenti: kartice, metrike, tabele, formule (`.eq`, `.frac`, `.sum`),
   tamni divider, zadatak za samostalni rad
3. Dijagrami: pozvati `drawChart(id, opcije)` sa podacima — podržava linijske
   i stepenaste serije, anotacije (Qmax strelice, Qsr linije) i legendu
4. Na `index.html` zameniti jedan „uskoro" red pravom karticom (uzor: Vežba 1)

## Objavljivanje (GitHub Pages)

1. Push repozitorijuma na GitHub
2. Settings → Pages → Source: `main` branch, root
3. Sajt je na `https://<korisnik>.github.io/<repo>/` — studentima poslati taj link
