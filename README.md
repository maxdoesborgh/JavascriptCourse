# 🚋 Passenger Counter App — JavaScript Fundamenten

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black&style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Semantics-E34F26?logo=html5&logoColor=white&style=flat-square)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-Modern_Layout-1572B6?logo=css3&logoColor=white&style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Course](https://img.shields.io/badge/Course-Scrimba_Learn_JavaScript-2B2D42?style=flat-square)](https://scrimba.com/learn/learnjavascript)
[![HBO-i](https://img.shields.io/badge/HBO--i-Niveau_2_Realisatie-0047FF?style=flat-square)](https://www.hbo-i.nl/)

> Een interactieve client-side webapplicatie voor het registreren, bijhouden en archiveren van passagiersstromen. Gerealiseerd met **Vanilla JavaScript**, **HTML5** en **CSS3** als onderdeel van de Scrimba *Learn JavaScript* cursus.

Repository URL: **[https://github.com/maxdoesborgh/JavascriptCourse/tree/main](https://github.com/maxdoesborgh/JavascriptCourse/tree/main)**

---

## 📌 Overzicht & Doelstelling

Deze applicatie dient als bewijslast voor het beheersen van native client-side webstandaarden zonder abstractielagen van externe frameworks (zoals React of Vue). De focus ligt op:
* Begrip van de **DOM (Document Object Model)** als levende representatie van de HTML-structuur;
* Een strikte scheiding tussen **runtime geheugenstatus (State)** en de **visuele weergave (View)**;
* Efficiënte interactie via de **JavaScript Event Loop** en performance-vriendelijke DOM-updates.

---

## ⚙️ Technische Kernconcepten & Rationale

De werking van de applicatie is gebaseerd op zes fundamentele principes:

### 1. DOM Manipulatie & Node Caching (`document.getElementById`)
```javascript
let saveEl = document.getElementById("save-el")
let countEl = document.getElementById("count-el")
