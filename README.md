# Glazera

Site-ul Glazera — folie inteligentă PDLC.

Pagina principală: `index.html` (un singur fișier, fără build).

## Cerere de ofertă

Formularul de ofertă e un configurator în 3 pași (tip spațiu → suprafață → telefon), definit o singură dată în `<template id="tplQuiz">` și afișat în două locuri: în hero (`B2B - Hero`) și la final (`B2B - Final`). Cererile pleacă prin FormSubmit la office@glazera.ro.

Evenimente Meta Pixel: `LeadFormStart`, `QuizStep` (pasul completat), `Lead` / `LeadGlazera` (cerere trimisă), `Contact` (click pe WhatsApp sau telefon).

## Credite

Pașii configuratorului folosesc [Wizard-JS](https://github.com/AdrianVillamayor/Wizard-JS) de Adrián Villamayor (licență MIT). Detalii în [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
