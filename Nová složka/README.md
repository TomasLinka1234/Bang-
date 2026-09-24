# 🤠 BANG! – Webový projekt

Jednoduchý webový projekt věnovaný populární westernové karetní hře **BANG!**. Web slouží jako informační rozcestník s přehledem pravidel, interaktivní galerií herních karet a kontaktním formulářem.

---

## 📄 Přehled stránek

Web se skládá ze čtyř propojených stránek s jednotnou horní navigací:

1. **[index.html](index.html)** (*Hlavní stránka*)
   - Úvodní představení hry BANG! a logo hry.
   - Používá stylopis `style.css`.

2. **[rules.html](rules.html)** (*Pravidla hry*)
   - Podrobný popis přípravy hry, rolí a jednotlivých fází hráčského tahu (dobírání, zahrání karet, odhazování).
   - Pravidla pro vyřazení postavy a systém odměn i trestů.
   - Používá stylopis `rules.css`.

3. **[cards.html](cards.html)** (*Karty*)
   - Galerie všech 42 originálních karet rozdělená do 3 řádků po 14 kartách (akční hnědé karty, modré vybavení/zbraně, postavy a role).
   - Responzivní CSS Grid s interaktivním hover efektem (nadzvednutí karty a stín při najetí myší).
   - Používá stylopis `cards.css`.

4. **[form.html](form.html)** (*Formulář*)
   - Jednoduchý a přehledný kontaktní formulář (jméno, e-mail, zpráva) laděný do westernového stylu webu.
   - Používá stylopis `form.css`.

---

## 📁 Adresářová struktura

```text
├── img/                  # Složka se všemi obrázky
│   ├── 01_bang.png       # Karty ze hry BANG! (42 herních karet)
│   ├── ...
│   ├── bang.png          # Logo hry BANG!
│   └── allcards.webp     # Přehled všech karet
├── cards.css             # Styly pro stránku karet (grid rozložení)
├── cards.html            # Stránka s kartami
├── form.css              # Styly pro kontaktní formulář
├── form.html             # Stránka s formulářem
├── index.html            # Hlavní (úvodní) stránka
├── rules.css             # Styly pro pravidla hry
├── rules.html            # Stránka s pravidly
├── style.css             # Styly pro hlavní stránku
└── README.md             # Dokumentace projektu
```

---

## 🛠️ Použité technologie

- **HTML5**: Sémantická struktura stránek, formulářové prvky, navigace.
- **CSS3**:
  - Pevná (fixed) horní navigace přístupná na všech stránkách.
  - CSS Grid (`grid-template-columns: repeat(14, minmax(...))`) pro zarovnání karet do 3 řad.
  - Hover efekty a plynulé přechody (`transition`, `translateY`, `box-shadow`).
  - Westernová barevná paleta laděná do pískových, hnědých a červených tónů.

---

## 🚀 Jak projekt spustit

1. Stáhněte nebo naklonujte složku s projektem.
2. Otevřete soubor `index.html` v libovolném moderním webovém prohlížeči (např. Google Chrome, Edge, Firefox).
3. Mezi jednotlivými stránkami můžete pohodlně procházet pomocí navigačního menu v pravém horním rohu.
