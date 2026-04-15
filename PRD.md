# PRD: Fyzioterapie v Ostrově — Landing Page

## Přehled

Jednoduchá one-page webová prezentace pro fyzioterapeutickou praxi **Tomáše Vonáška** v obci **Ostrov**. Stránka slouží jako „digitální vizitka" — žádný booking systém, žádný backend, žádný CMS. Majitel komunikuje s klienty přes WhatsApp a telefon, web generuje poptávku a buduje důvěru.

### Klíčové principy
- **Nulová údržba** — statický HTML soubor, žádné pluginy, žádné aktualizace
- **Nulová podpora** — majitel nepotřebuje nic spravovat; změny provádí Jakub přes Claude Code
- **Minimální náklady** — hosting zdarma (GitHub Pages), jediný náklad je doména (~$10/rok)
- **100% čeština** — žádná angličtina nikde na stránce

---

## Cílová skupina

- Páry od 40 let výše
- Ucelené skupiny (jóga, teambuilding, firemní výjezdy)
- Lidé s problémy s pohybovým ústrojím (zejména ploténky)

---

## Podnikání — dvě hlavní větve

### 1. Soukromá praxe (1:1)
Odborná fyzioterapie formou intenzivních 4denních kempů:
- Zaměření na ploténky a pohybový aparát
- Terapie 2× denně po 30 min
- Semináře Školy zad (45 min/den)
- Tejpování
- Konají se především v době prázdnin

### 2. Wellness a skupinové pobyty
**Wellness víkendy:**
- 2 noci
- Společné cvičení + individuální 45min masáž denně
- Sauna a vířivka
- Volný odpolední program

**Pronájem prostoru:**
- Pro skupiny s vlastním programem (jóga, teambuilding, výjezdní zasedání)
- K ubytování nabízeny masáže, RHB cvičení, terapie

---

## Ubytování & lokalita

- **Kapacita:** max 12 lidí (ideálně 8–10)
- **Dispozice:** 2 dvoulůžkové apartmány + byt se 4 dvoulůžky
- **Prostředí:** malá klidná vesnice, ticho je součástí terapie
- **Okolí:** cyklostezka (Brdy), zámky (Březnice, Blatná, Orlík), města (Příbram, Písek)

---

## Strava & doplňkový program

- Snídaně zajištěny na místě
- Oběd/večeře: místní restaurace, vlastní příprava, catering, grilování
- **Doplňkové zážitky (za příplatek):**
  - Posezení u ohně s kytarou
  - Degustace vín
  - Tématický večer s kuchařem

---

## Ceník

| Balíček | Délka | Cena |
|---------|-------|------|
| Odborná péče | 4 noci | 12 500 Kč/osoba |
| Wellness víkend | 2 noci | 6 000 Kč/osoba |
| Pronájem prostoru | dle domluvy | individuální |

---

## Kontaktní údaje

- **Jméno:** Tomáš Vonášek
- **Telefon:** +420 777 296 426
- **Email:** Tomas.Vonasek@seznam.cz
- **WhatsApp:** https://wa.me/420777296426

---

## Technický stack

| Vrstva | Technologie | Proč |
|--------|------------|------|
| Kód | Jediný `index.html` soubor | Nulová komplexita, snadné úpravy |
| Styling | Tailwind CSS (CDN) | Vše v HTML, žádné externí CSS soubory |
| Fonty | Playfair Display + Inter (Google Fonts) | „Quiet luxury" estetika |
| Ikony | Lucide (CDN) | Čisté, minimalistické ikony |
| Animace | Intersection Observer API | Plynulé fade-in při scrollu |
| Hosting | GitHub Pages | Zdarma, deploy = git push |
| Doména | TBD | Zatím na jakehamix.github.io/tomas-fyzio |

---

## Design

- **Styl:** „Quiet Luxury" / Minimalistický — jako boutique hotelový web
- **Paleta:** měkké bílé (#F9FAFB), kamenné šedé (#E5E7EB), tmavá lesní zeleň (#2D4A3E)
- **Typografie:** velká a čitelná (cílová skupina 40+)
- **České typografické konvence:** `&nbsp;` po jednopísmenných předložkách (v, s, z, u, o, k)
- **Responzivita:** mobile-first (klíčové pro WhatsApp uživatele)

---

## Struktura stránky

1. **Navigace** — fixní, průhledná na hero, tmavne při scrollu
2. **Hero** — celoplošný obrázek, název, podtitul, CTA tlačítka
3. **Úvod** — filosofie „klid jako součást terapie"
4. **Služby** — 3 karty (Odborná péče, Wellness, Pronájem)
5. **Ubytování & Lokalita** — fotogalerie + popis kapacity a okolí
6. **Strava & Zážitky** — jídlo + doplňkový program
7. **Ceník** — 2 cenové karty s CTA
8. **Kontakt** — WhatsApp, telefon, email na pozadí s obrázkem
9. **Patička** — název, kontakt, navigace

---

## Fotografie

Aktuálně používáme **placeholder fotky z Unsplash**. Jakmile Tomáš dodá reálné fotky, nahradíme je. Kvalitní fotografie jsou klíčové pro „refined" dojem — 90% dojmu = fotky, 10% = typografie.

**Potřebné fotky:**
- Exteriér domu/pozemku
- Interiér apartmánů
- Wellness prostor (sauna, vířivka)
- Terapeutická místnost
- Okolní krajina, cyklostezka
- Jídlo / grilování

---

## Komunikační flow

Žádný booking systém. Web generuje poptávku, Tomáš ji zpracuje ručně:

1. Návštěvník klikne na „Rezervovat přes WhatsApp" nebo „Zavolat"
2. Otevře se WhatsApp s předvyplněnou zprávou / telefonní hovor
3. Tomáš odpoví a domluví termín po telefonu/SMS/WhatsApp
4. Platba na místě nebo přes Stripe link poslaný emailem

---

## Hosting & deployment

- **Repo:** https://github.com/JakeHamix/tomas-fyzio (public)
- **GitHub Pages:** https://jakehamix.github.io/tomas-fyzio/
- **Deploy:** automatický po push do `main`
- **Vlastní doména:** zatím nenastavena (TBD)

---

## Budoucí vylepšení (backlog)

- [ ] Nahradit placeholder fotky reálnými
- [ ] Připojit vlastní doménu
- [ ] Přidat konkrétní termíny kempů/víkendů (jednoduchý textový seznam)
- [ ] Případně embed Tally.so formulář pro registrace na akce
- [ ] SEO optimalizace (meta tagy, Open Graph)
- [ ] Favicon
