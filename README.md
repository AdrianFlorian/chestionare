# Chestionare Sfera Business

Chestionare de autoevaluare, ca wizard-uri web (doar frontend): o afirmație pe pagină, rezultatele afișate imediat la final.

| Pagina | Adresa |
|---|---|
| Pagina principală | https://adrianflorian.github.io/chestionare/ |
| Test de personalitate DISC (80 de afirmații, 4 dimensiuni) | https://adrianflorian.github.io/chestionare/disc/ |
| Chestionar de Change Readiness (35 de afirmații, 7 scale) | https://adrianflorian.github.io/chestionare/change-readiness/ |
| Calitatea motivației (18 afirmații, 6 tipuri de motivație) | https://adrianflorian.github.io/chestionare/motivatie/ |

Demo cu răspunsuri aleatorii: adăugați `#demo` la adresa oricărui chestionar.

Structură: `index.html` (pagina principală), `disc/index.html`, `change-readiness/index.html`, `motivatie/index.html`. Chestionarele sunt independente: fiecare are propriile afirmații, propriul calcul și propriile rezultate salvate. Fiecare chestionar este un singur fișier HTML, fără dependențe externe.

Răspunsurile rămân doar în browserul utilizatorului (localStorage). Nimic nu este trimis către un server. Paginile sunt marcate `noindex`.
