# 📏 Modul A - Responsivt design og bilder

Dette prosjektet viser forskjellen mellom faste og responsive målenheter i CSS, samt bruk av `<picture>`-elementet for responsiv bildehåndtering. Ved hjelp av `em`, `rem`, `ch`, `vw`, `vh`, og prosentbaserte målinger, får du innsikt i hvordan CSS måleenheter fungerer i ulike kontekster.

---

## 🧠 Hva lærer du?

✅ Forskjellen på **fast vs. fleksibel** størrelse  
✅ Bruk av måleenheter: `px`, `em`, `rem`, `ch`, `%`, `vw`, `vh`  
✅ Hvordan `min-` og `max-width/height` fungerer i praksis  
✅ Bruk av `<picture>`-element for **responsiv bildevalg**  
✅ Konseptet bak `object-fit` og bildekvalitet (SVG vs raster)

---

## 🧱 Seksjoner i prosjektet

### 1. 📷 `<picture>` med `srcset`

```html
<picture>
  <source srcset="./cat-1024.jpg" media="(max-width: 1024px)" />
  <source srcset="./cat-700.jpg" media="(max-width: 700px)" />
  <source srcset="./cat-250.jpg" media="(max-width: 250px)" />
  <img src="./manja-vitolic-gKXKBY-C-Dk-unsplash.jpg" alt="cat" />
</picture>
