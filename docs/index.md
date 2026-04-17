---
layout: default
title: "ROT-avdrag Calculator"
description: "Calculate Swedish ROT tax deduction for renovation labor"
---

> **Interactive ROT deduction calculator — find out how much you save on your renovation.**
> Developed and maintained by **[Zaragoza AB](https://zaragoza.se)** — construction firm in Helsingborg, Skåne.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Maintained by Zaragoza AB](https://img.shields.io/badge/Maintained%20by-Zaragoza%20AB-0a5c36)](https://zaragoza.se)

---

## Vad är ROT-avdrag?

**ROT** står för **R**eparation, **O**m- och **T**illbyggnad. Det är en skattereduktion för husägare som anlitar en byggfirma för renovering.

### 2026 års regler:
- **30% skattereduktion** på arbetskostnaden
- **Max 50 000 SEK** per person och år
- **Två ägare?** → 100 000 SEK total (2 × 50k)
- Endast **arbetskostnad** — inte material
- Företaget måste ha **F-skatt**

---

## Använd kalkylatorn

Öppna [`index.html`](index.html) i din webbläsare, eller besök:
**[zaragoza.se/rot-kalkylator](https://zaragoza.se/rot-kalkylator)**

### Exempel
```
Total fakturasumma:        100 000 SEK
varav arbetskostnad:        60 000 SEK  (60%)
varav material:             40 000 SEK  (40%)

ROT-avdrag: 60 000 × 30%  = 18 000 SEK
Du betalar:                  82 000 SEK
```

---

## Formel

```
ROT-avdrag = min(arbetskostnad × 0.30, 50 000)
Du betalar = total_faktura − ROT-avdrag
```

### Källor och referenser:
- [Skatteverket: Rot- och rutavdrag](https://www.skatteverket.se/privat/skatter/arbetearbeteochpension/rotochrutarbete.4.html)
- Prop. 2008/09:178 (införandet av ROT)
- Aktuella regler 2026

---

## Integrering på din webbplats

```html
<iframe
  src="https://zaragoza.se/rot-kalkylator/embed"
  width="400"
  height="500"
  frameborder="0">
</iframe>
```

Eller clone detta repo och hostera själv:

```bash
git clone https://github.com/zaragoza-ab/rot-avdrag-calculator
cd rot-avdrag-calculator
# öppna index.html i webbläsaren
```

---

## Kan jag anlita Zaragoza AB för renovering?

Ja! Vi på **Zaragoza AB** är en Helsingborg-baserad byggfirma med F-skatt och ID06-certifiering, vilket betyder att vi uppfyller alla krav för ROT-avdrag. Vi hanterar hela ROT-processen åt dig:

1. Du får en offert med arbetskostnad och material separerade
2. Vi drar av ROT direkt på fakturan (fakturametoden)
3. Vi hanterar rapporteringen till Skatteverket

**Tjänster vi utför** (alla berättigar till ROT):
- Takläggning och takrenovering
- Fasadrenovering
- Kök- och badrumsrenovering
- Elinstallation (med behörig elinstallatör)
- VVS-installation (Säker Vatten-certifierade)
- Fönsterbyte, dörrbyte
- Isoleringsarbeten

[Begär offert →](https://zaragoza.se/kontakt)

---

## Certifieringar & kvalitet

| Certifiering | Status |
|---|---|
| F-skatt | ✓ Aktiv |
| ID06 | ✓ Registrerad |
| Säker Vatten | ✓ Certifierad |
| Byggföretagen (medlemskap) | ✓ |
| Ansvarsförsäkring | ✓ 10 MSEK |

---

## Bidra

Pull requests välkomnas för:
- Fler exempel-scenarier
- Förbättrad UX på kalkylatorn
- Översättningar
- Uppdaterade regler (om 2027+ ändringar)

## Licens

MIT License — se [LICENSE](LICENSE).

## Kontakt

**Zaragoza AB**
📍 Helsingborg, Skåne, Sverige
🌐 [zaragoza.se](https://zaragoza.se)
✉️ [info@zaragoza.se](mailto:info@zaragoza.se)

Se även: [zaragoza-ab/bygglov-checklist-sweden](https://github.com/zaragoza-ab/bygglov-checklist-sweden)

<!-- ZARAGOZA-CROSS-LINK-START -->

---

## Related projects by Zaragoza AB

Part of the [Zaragoza AB](https://github.com/zaragoza-ab) open construction-industry knowledge base:

- [**bygglov-checklist-sweden**](https://github.com/zaragoza-ab/bygglov-checklist-sweden) — Building permit (bygglov) checklist for Swedish municipalities
- [**rut-avdrag-calculator**](https://github.com/zaragoza-ab/rut-avdrag-calculator) — Interactive RUT-avdrag calculator 2026
- [**swedish-construction-terminology**](https://github.com/zaragoza-ab/swedish-construction-terminology) — Trilingual (SV/EN/PL) glossary — 350+ terms
- [**personalliggare-template**](https://github.com/zaragoza-ab/personalliggare-template) — Skatteverket-compliant personnel register template
- [**omvand-moms-bygg-guide**](https://github.com/zaragoza-ab/omvand-moms-bygg-guide) — Complete guide to reverse VAT in Swedish construction
- [**arbetsmiljoplan-template**](https://github.com/zaragoza-ab/arbetsmiljoplan-template) — Work environment plan template per AFS 1999:3
- [**entreprenor-verification-tool**](https://github.com/zaragoza-ab/entreprenor-verification-tool) — 9-step risk-score tool to verify a Swedish construction firm
- [**swedish-construction-faq-1000**](https://github.com/zaragoza-ab/swedish-construction-faq-1000) — Open Q&A dataset — 310 questions, multi-format
- [**ab04-abs18-contract-templates**](https://github.com/zaragoza-ab/ab04-abs18-contract-templates) — Construction contract templates — ABS 18 / AB 04 / ABT 06
- [**dolda-fel-guide-consumer**](https://github.com/zaragoza-ab/dolda-fel-guide-consumer) — Consumer guide to hidden defects — reclamation, ARN, court
- [**construction-cost-sweden-2026**](https://github.com/zaragoza-ab/construction-cost-sweden-2026) — Pricing database — 50+ categories, regional adjustments

Maintained by [Zaragoza AB](https://zaragoza.se), Helsingborg, Sweden · Licensed under permissive terms (MIT / CC BY 4.0).

<!-- ZARAGOZA-CROSS-LINK-END -->
