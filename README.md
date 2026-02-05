# Výletník

<img src="https://html.edumach.cz/img/vyletnik_final.png" width="800">

## Cíl projektu

Vytvořte jednoduchý web „Výletník“, který bude prezentovat **čtyři** vybraná místa v České republice vhodná na výlet. Web bude obsahovat úvodní stránku a jednotlivé stránky s výlety.

---

## Struktura odevzdání

Odevzdáte **zazipovanou složku** s názvem:

```
10XPrijmeniJ-vyletnik.zip
```

Tato složka bude obsahovat:

* soubor **index.html** (výchozí stránka),
* další stránky s jednotlivými výlety,
* **externí CSS soubor** se styly,
* **složku s obrázky**.

---

## Obrázky

* Každý výlet bude mít **2 obrázky**.
* Všechny obrázky:

  * upravte na rozměr **300 × 200 px**,
  * budou mít **barevný rámeček**,
  * budou uložené ve složce pro obrázky.

---

## Vzhled stránky

Stránka bude splňovat tyto požadavky:

1. **HTML hlavička**

   * Úplná HTML5 struktura.
   * Titulek stránky: **Výletník**.

2. **Rozvržení stránky**

   * Světle pastelová barva pozadí.
   * Obsah bude zarovnán na střed a omezen na šířku **800 px**.

Příklad struktury:

```html
<body>
  <div class="obal">

  Zde je viditelný obsah

  </div>
</body>
```

Příklad stylu:

```css
.obal {
  max-width: 800px;
  margin: auto;
}
```

3. **Písmo**

   * Bezpatkové písmo (např. Arial, Verdana nebo webové písmo z Google Fonts).

---

## Horní část stránky

Každá stránka bude obsahovat:

### Záhlaví

* Hlavní nadpis.
* Krátký odstavec.
* Obojí zarovnané na střed.
* Velikost písma odstavce přibližně **1.3em**.

### Navigaci

* Odkazy na jednotlivé výlety.
* Nad navigací i pod ní bude vodorovná čára.

---

## Obsah výletu

Každý výlet bude obsahovat:

1. **Nadpis 2. úrovně** s názvem místa.

2. **Text**

   * Alespoň **dva odstavce** s popisem a zajímavostmi.

3. **Seznam**

   * Lokalita (město nebo obec).
   * Odkaz na oficiální web.

4. **Galerie a média**

   * 2 obrázky,
   * výřez z mapy (mapy.com),
   * video z YouTube.

Všechny čtyři prvky:

* budou mít rozměr **300 × 200 px**,
* budou **zarovnané na střed**.

Mapa se vkládá stejně jako video pomocí značky `<iframe>`, pouze s jinými atributy.

<img src="https://html.edumach.cz/img/iframe-mapy.png" width="600">


---

## Odkazy

* Barva: zelená.
* Písmo: tučné.
* Po přejetí myší se odkaz **nepodtrhne** nebo bude mít jiný efekt (pseudotřída `:hover`).

---

## Odevzdání

Před odevzdáním:

1. Zkontrolujte, že všechny odkazy fungují.
2. Zkontrolujte rozměry obrázků.
3. Ověřte, že se styly načítají z externího souboru.

Nakonec:

* celou složku zazipujte,
* odevzdejte podle pokynů zadavatele.

---

## Kritéria hodnocení projektu

**Zcela splněno (známka 1):**

* Web je odevzdán ve správné složce, obsahuje všechny požadované soubory a funguje po rozbalení.
* Stránky mají správnou strukturu (HTML5 hlavička, externí styly, index.html).
* Vzhled odpovídá zadání (šířka obsahu, zarovnání, barvy, písmo, odkazy, navigace).
* Každý výlet obsahuje všechny požadované prvky: nadpis, alespoň dva odstavce, seznam, dva obrázky, mapu a video ve správných rozměrech a zarovnání.
* Obrázky jsou upravené na dané rozměry a mají rámeček.
* Stránka je přehledná a bez zásadních chyb v kódu nebo zobrazení.

**Částečně splněno (známka 3):**

* Web je funkční, ale některé požadavky nejsou dodrženy (např. chybí část prvků, drobné chyby ve vzhledu, ne zcela správné rozměry nebo styly).
* Struktura stránek je převážně správná, ale obsahuje nedostatky.
* Některé části nejsou sjednocené nebo neodpovídají přesně zadání, ale stránka je použitelná.

**Nesplněno (známka 5):**

* Projekt nebyl v termínu odevzdaný.
* Web nelze otevřít nebo chybí podstatná část souborů.
* Chybí většina požadovaných prvků (např. navigace, obrázky, mapa nebo video).
* Není dodržena základní struktura stránky nebo nejsou použity externí styly.
* Stránka je nefunkční, nepřehledná nebo neodpovídá zadání ve většině bodů.

