# ⛳ DG - Enkel Discgolf Scorecard (PWA)

Detta är ett lättviktsverktyg för att föra statistik och hålla koll på resultat under en runda discgolf. Appen är byggd som en Progressive Web App (PWA) för snabb och stabil användning direkt från mobilens hemskärm.

## ✨ Funktioner

* **Enkel inmatning:** Snabb registrering av antal kast per hål.
* **PB-spårning:** Visar ditt personbästa (PB) per bana.
* **Totalstatistik:** Håller koll på totalt antal rundor och genomsnittligt resultat.
* **Lokal Lagring:** All data sparas lokalt i din webbläsare för snabb åtkomst och offline-användning.

## 📱 Så här installerar du den som en app

Eftersom detta är en PWA kan du lägga till den på din hemskärm för att använda den som en riktig app, utan webbläsarfönster eller adressfält.

1.  **Besök länken:** Gå till följande URL på din mobiltelefon:
    [https://ssrall.github.io/DG/](https://ssrall.github.io/DG/)
2.  **Installera/Lägg till på hemskärmen:**
    * **Chrome (Android):** Klicka på menyn (de tre prickarna) och välj "Installera appen" eller "Lägg till på startskärmen".
    * **Safari (iPhone/iOS):** Klicka på delningsikonen (fyrkant med pil upp) och välj "Lägg till på hemskärmen".
3.  **Starta:** Appen kommer nu att finnas på din hemskärm och öppnas direkt som ett eget program.

## 🛠️ Teknik

Appen är byggd med rena webbteknologier och kräver ingen server-side-kod:

* **HTML:** Struktur
* **CSS:** Styling
* **JavaScript:** All logik för att räkna poäng och spara data (med `localStorage`).

## ✍️ Licens

Detta projekt är tillgängligt under **Creative Commons BY-ND 4.0*. Se filen [LICENSE](LICENSE) för mer information.

## 🔒 Dataskydd och Integritet

<p>Denna applikation hanterar din data enligt följande principer, i enlighet med GDPR (Dataskyddsförordningen):</p>
<ul>
    <li>Ingen extern lagring: Alla resultat, spelarnamn och statistiska data (inklusive UDisc-rating) som läses in från din CSV-fil **lagras uteslutande lokalt** i din webbläsares minne (<code>localStorage</code>). Inga uppgifter skickas, överförs eller sparas på någon extern server, databas eller molntjänst.</li>
    <li>Personuppgifter: De uppgifter som behandlas är de som finns i din inlästa CSV-fil (t.ex. spelarnamn och ratingar), vilka räknas som personuppgifter.</li>
    <li>Ändamål: Syftet med behandlingen är att erbjuda dig personlig statistik och en förbättrad översikt över dina och dina medspelares rundor.</li>
    <li>Radering: Om du raderar data från din webbläsare eller rensar din webbläsares lokala lagring, kommer all sparad information från denna applikation att raderas permanent.</li>
</ul>
<p>Genom att använda applikationen godkänner du att din webbläsare lagrar dessa uppgifter lokalt för det angivna ändamålet.</p>
