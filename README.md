# ✈️ UI/UX Prototype – Reiseportal

Ein responsiver Frontend-Prototype für ein Reiseportal, erstellt mit purem HTML und CSS – kein Framework, kein JavaScript-Build-Tool.

---

## 📁 Projektstruktur

```
/
├── index.html
├── css/
│   └── style.css
└── img/
    ├── aviation_logo-22.jpg
    ├── christine-roy-ir5MHI6rPg0-unsplash.jpg
    ├── luca-bravo-O453M2Liufs-unsplash.jpg
    ├── ian-dooley-hpTH5b6mo2s-unsplash.jpg
    ├── jack-anstey-XVoyX7l9ocY-unsplash.jpg
    ├── jairph-1XLyzi17Z2M-unsplash.jpg
    ├── jake-blucker-tMzCrBkM99Y-unsplash.jpg
    ├── gaddafi-rusli-2ueUnL4CkV8-unsplash.jpg
    ├── philipp-kammerer-6Mxb_mZ_Q8E-unsplash.jpg
    ├── ryan-miglinczy-02n9_v-d1yY-unsplash.jpg
    ├── ryan-XGKaRnWjv1c-unsplash.jpg
    └── timo-stern-iUBgeNeyVy8-unsplash.jpg
```

---

## 🧩 Seitenaufbau

**Navigation** – Logo links, Linkleiste rechts. Auf Mobile wird die Navigation durch einen Hamburger-Button ein- und ausgeklappt (reines CSS + minimales Inline-JS, keine externe Library).

**Header / Hero** – Vollflächiges Hintergrundbild mit einer zentrierten Search Box. Die Box enthält ein Tab-Element, eine Überschrift sowie ein Suchformular mit zwei Feldern (Abflugort / Zielort) und einem Submit-Button.

**Our Destinations** – Galerie-Layout mit einem großen Bild links und einem 2×2-Grid rechts.

**Our Gallery** – Flexbox-Galerie mit variablen Bildbreiten; jedes vierte Bild ist breiter dargestellt.

**Footer** – Einfacher Footer mit Linkliste.

---

## 📱 Responsive Breakpoints

| Breakpoint | Zielgerät | Änderungen |
|---|---|---|
| `≤ 1024px` | Tablet | Galleries auf 90% Breite, Search Box Padding reduziert |
| `≤ 768px` | Mobil | Hamburger-Menü, Search Box aus absolutem Positioning, Form-Felder untereinander, Galleries einspaltiger |
| `≤ 480px` | Kleines Mobil | Navigation und Schriften weiter verkleinert, Gallery Grid einspaltiger |

---

## 🛠️ Technologien

- **HTML5** – semantisches Markup
- **CSS3** – Flexbox, Media Queries, `min()`, `aspect-ratio`, `object-fit`
- **Kein Framework**, kein Build-Step, kein npm

---


## 📸 Bildquellen

Alle Fotos stammen von [Unsplash](https://unsplash.com) und sind unter der [Unsplash License](https://unsplash.com/license) frei verwendbar.

---

## 📌 Hinweise

Dieser Prototype ist ein reines UI/UX-Demo ohne Backend-Anbindung. Das Suchformular sendet keine echten Anfragen.
