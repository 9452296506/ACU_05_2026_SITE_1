📄 Polish version:
# Historia zmian

Lista zmian wprowadzonych w projekcie **ACU_05_2026_SITE_1**.
Projekt korzysta z [wersjonowania semantycznego](https://semver.org/lang/pl/) (`MAJOR.MINOR.PATCH`).

---

## [1.0.2] — 2026-05-12

### Poprawione
- Naprawiono zachowanie zamykania menu mobilnego w iOS Safari
- Drobna korekta odstępów w kartach opinii poniżej szerokości 480 px
- Skorygowano rozmiary miniatur w sekcji hero na małych tabletach

### Ulepszone
- Lekko zwiększono kontrast tekstu drugorzędnego na ciemnym tle hero
- Doprecyzowano atrybuty `alt` dla lepszej dostępności

---

## [1.0.1] — 2026-05-10

### Dodane
- Dodatkowe zdjęcia produktowe w sekcjach produktu, składu i opinii
- Sekcja galerii w stylu UGC / Instagram (`@bionetic.lv`)
- Blok ze zdjęciem sklepu w sekcji kontakt

### Zmienione
- Wydzielono CSS z pliku HTML do plików modułowych: `base.css`, `components.css`, `sections.css`
- Wydzielono JavaScript z pliku HTML do plików modułowych: `cart.js`, `ui.js`, `main.js`
- Wprowadzono zmienne CSS dla palety kolorów i typografii

---

## [1.0.0] — 2026-05-08

### Dodane
- Pierwsza wersja strony docelowej
- Przyklejony nagłówek z ikonami koszyka, konta i wyszukiwarki; wysuwane menu mobilne
- Sekcja hero z głównym zdjęciem produktu i blokiem cenowym
- Sekcje: historia marki, składniki (`Fitokeratīns`, `Aminoskābes`, `Augu izvilkumi`) oraz "Jak to działa"
- Opinie, FAQ i formularz kontaktowy z walidacją po stronie klienta
- Wysuwany koszyk zakupowy z zapisem stanu w `localStorage`
- Modal konta (zakładki: logowanie / rejestracja) oraz modal wyszukiwarki z filtrowaniem na żywo
- Pełnoekranowe strony polityk: Prywatność, Regulamin, Dostawa, Zwroty
- Banner cookie z zapamiętywaniem w `localStorage`
- Responsywny układ: desktop, tablet i mobile
- Meta tagi SEO, znaczniki Open Graph oraz dane strukturalne JSON-LD `LocalBusiness`

---

📄 English version:

# Changelog

All notable changes to project **ACU_05_2026_SITE_1** are listed here.
This project follows [Semantic Versioning](https://semver.org/) (`MAJOR.MINOR.PATCH`).

---

## [1.0.2] — 2026-05-12

### Fixed
- Corrected mobile menu close behaviour on iOS Safari
- Minor padding fix on testimonial cards below 480 px width
- Adjusted hero thumbnail sizing on small tablets

### Improved
- Slightly increased contrast of secondary text on the dark hero gradient
- `alt` attributes refined for better accessibility

---

## [1.0.1] — 2026-05-10

### Added
- Additional product imagery in product, ingredient and testimonial sections
- UGC / Instagram-style gallery section (`@bionetic.lv`)
- Store photo block inside the contact section

### Changed
- Extracted inline CSS into modular files: `base.css`, `components.css`, `sections.css`
- Extracted inline JavaScript into modular files: `cart.js`, `ui.js`, `main.js`
- Introduced CSS custom properties for the colour palette and typography

---

## [1.0.0] — 2026-05-08

### Added
- Initial release of the landing page
- Sticky header with cart, account and search icons; mobile slide-in menu
- Hero section with primary product image and price block
- Brand story, ingredients (`Fitokeratīns`, `Aminoskābes`, `Augu izvilkumi`) and "How it works" sections
- Testimonials, FAQ and contact form with client-side validation
- Shopping cart drawer with `localStorage` persistence
- Account modal (login / register tabs) and search modal with live filtering
- Privacy, Terms, Delivery and Refund policy pages (fullscreen overlays)
- Cookie banner with `localStorage` memory
- Responsive design for desktop, tablet and mobile
- SEO meta tags, Open Graph tags, JSON-LD `LocalBusiness` structured data

---
