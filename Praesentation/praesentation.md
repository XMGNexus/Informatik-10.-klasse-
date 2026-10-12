---

marp: true
theme: default
class: paginate
style: |
  /* Farbenfrohes Cyberpunk-Hacker-Theme */
  section {
    background-color: #090514 !important; /* Dunkles Cyber-Violett */
    color: #39FF14; /* Giftgrüner Terminal-Text */
    font-family: 'Courier New', Courier, monospace;
    text-shadow: 0 0 6px rgba(57, 255, 20, 0.4);
  }
  
  /* Überschriften */
  section h1 {
    color: #00F0FF; /* Neon-Cyan/Türkis für Titel */
    font-size: 2.5rem;
    border-bottom: 2px dashed #00F0FF;
    padding-bottom: 10px;
    text-shadow: 0 0 12px rgba(0, 240, 255, 0.8);
  }
  section h3 {
    color: #FF007F; /* Neon-Pink für Untertitel */
    text-shadow: 0 0 8px rgba(255, 0, 127, 0.6);
  }
  
  /* Listen-Styling */
  section ol {
    font-size: 1.5rem;
    font-weight: bold;
    color: #00F0FF;
    text-shadow: 0 0 8px rgba(0, 240, 255, 0.6);
  }
  section ul {
    font-size: 1.3rem;
    font-weight: bold;
    list-style-type: '> ';
  }
  
  /* Alles Fettgedruckte in Neon-Pink */
  section strong {
    color: #FF007F !important;
    text-shadow: 0 0 10px rgba(255, 0, 127, 0.85) !important;
  }

  /* Cyber-Grid Tabelle */
  section table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 1rem;
    font-size: 1.1rem;
    background-color: #090514 !important;
    border: 2px solid #00F0FF !important; /* Türkiser Rahmen */
    box-shadow: 0 0 15px rgba(0, 240, 255, 0.2);
  }
  section th {
    background-color: #120a26 !important;
    color: #00F0FF !important;
    font-weight: bold;
    padding: 12px;
    border-bottom: 2px solid #00F0FF !important;
    border-right: 1px solid #00F0FF !important;
    text-shadow: 0 0 8px rgba(0, 240, 255, 0.7);
  }
  section td {
    padding: 12px;
    color: #39FF14 !important;
    background-color: #090514 !important;
    border-bottom: 1px solid #1a0f38 !important;
    border-right: 1px solid #00F0FF !important;
  }
  
  section th:last-child, section td:last-child {
    border-right: none !important;
  }
  
  section td strong {
    color: #FF007F !important;
    text-shadow: 0 0 10px rgba(255, 0, 127, 0.85) !important;
  }
  
  section tr:nth-child(even) {
    background-color: #120a26 !important; /* Leicht helleres Violett */
  }

  /* Farbige Terminal-Boxen */
  .columns {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.6rem;
    margin-top: 0.8rem;
    width: 100%;
  }
  .column-box {
    border: 1px solid #FF007F; /* Pinker Rahmen für Boxen */
    padding: 0.6rem;
    background: #0d071f;
    box-shadow: 0 0 10px rgba(255, 0, 127, 0.2);
    text-align: center;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .column-box img {
    max-width: 65px;
    height: auto;
    margin: 0.3rem auto 0 auto !important;
  }
  .column-box h3 {
    font-size: 1.2rem;
    margin-bottom: 0.3rem;
  }

  .compact {
    font-size: 1.1rem;
    line-height: 1.3;
    display: block;
    margin-bottom: 0.3rem;
    color: #39FF14;
  }
  
---

# [SYS_INIT]: Passwort-Manager Vergleich
### root@cyber_terminal:~# NordPass, Bitwarden & Proton Pass
<!-- [Folie 1: SYS_INIT] -->
<!--
[SPRECHTEXT]
Guten Tag. Ich begrüße Sie zum Vergleich der Passwortmanager NordPass, Bitwarden und Proton Pass. Gängige Passwörter stellen heute ein massives Sicherheitsrisiko dar. Diese Präsentation analysiert, wie moderne Verwaltungstools dieses Problem strukturell lösen und wo die wesentlichen Unterschiede der drei Anbieter liegen.
-->

---

# [FETCH_REPOS]:<br> .//Anbieter im Überblick

<div class="columns">
<div class="column-box">
<h3>01_NordPass</h3>
<br>
<img src="./bilder/nordpass-logo_1-1-30.png" style="display:block;" />
</div>
<div class="column-box">
<h3>02_Bitwarden</h3>
<br>
<img src="./bilder/bitwarden.png" style="display:block;" />
</div>
<div class="column-box">
<h3>03_Proton_Pass</h3>
<br>
<img src="./bilder/proton_pass.png" style="display:block;" />
</div>
</div>

<!-- [Folie 2: FETCH_REPOS] -->
<!--
[SPRECHTEXT]
Unsere drei Testkandidaten im Überblick: NordPass basiert auf der Infrastruktur von NordVPN. Bitwarden ist der etablierte Standard der Open-Source-Community. Proton Pass ist ein Schweizer Newcomer mit starkem Fokus auf informationelle Selbstbestimmung. Alle drei verfolgen technologisch unterschiedliche Ansätze.
-->

---

# [ANALYSIS]: Vergleichskriterien

- **Sicherheit & Verschlüsselung** ── [CRYPT_LOG]
- **Kosten & Tarife** ────────────── [PRICING_DEPT]
- **Komfort &amp; Plattformen** ──────── [UI_UX_LAYER]

<!-- [Folie 3: ANALYSIS] -->
<!--
[SPRECHTEXT]
Die Evaluierung erfolgt anhand dreier Kernkriterien: Erstens der Sicherheits- und Verschlüsselungsarchitektur. Zweitens der Preisstruktur und den Einschränkungen der Tarife. Drittens dem Nutzungskomfort sowie der plattformübergreifenden Verfügbarkeit im Alltag.
-->

---

# [DATA_GRID]: Kernstärken

| Manager | Stärke | Feature | Krypto |
| :--- | :--- | :--- | :--- |
| **Bitwarden** | Preis-Leistung | Open Source & Self-Hosting | AES-256 |
| **Proton Pass** | Datenschutz | E-Mail-Aliasse | Argon2 & AES |
| **NordPass** | Bedienung | Intuitive UI | XChaCha20 |

<!-- [Folie 4: DATA_GRID] -->
<!--
[SPRECHTEXT]
Dieses Daten-Grid komprimiert die Kernstärken: Bitwarden überzeugt durch das Preis-Leistungs-Verhältnis und Self-Hosting. Proton Pass sichert den Datenschutz mittels nativer E-Mail-Aliasse. NordPass fokussiert sich auf maximale Benutzerfreundlichkeit und das moderne Verschlüsselungsverfahren XChaCha20.
-->

---

# [SEC_CHECK]:<br> Kriterium 1: Sicherheit

- **Zero-Knowledge:** Keinerlei Klartext-Einsicht durch Anbieter
- **Bitwarden & Proton Pass:** Standardisierte **AES-256-Verschlüsselung**
- **NordPass:** Moderner, performanter **XChaCha20-Algorithmus**

<!-- [Folie 5: SEC_CHECK] -->
<!--
[SPRECHTEXT]
Zum Kriterium Sicherheit: Alle Dienste nutzen eine Zero-Knowledge-Architektur; der Anbieter hat somit keinen Zugriff auf die Daten. Bitwarden und Proton Pass setzen auf den Industriestandard AES-256. NordPass nutzt XChaCha20, was auf Mobilgeräten performanter und als zukunftssicher einzustufen ist.
-->

---

# [COST_LAYER]:<br> Kriterium 2: Kosten

- **Bitwarden:** Bester **Free-Tarif** (unlimitierte Geräte & Passwörter)
- **Proton Pass:** Unlimitierte Geräte, aber Limit bei Mail-Aliassen
- **NordPass Free:** Stark restriktiv (nur **1 aktives Gerät** gleichzeitig)

<!-- [Folie 6: COST_LAYER] -->
<!--
[SPRECHTEXT]
Der Kostenvergleich zeigt deutliche Unterschiede: Bitwarden bietet die leistungsstärkste Gratisversion für unbegrenzte Geräte. Proton Pass folgt mit minimalen Einschränkungen. NordPass Free ist hochgradig restriktiv, da die parallele Nutzung auf mehreren Geräten komplett blockiert wird.
-->

---

# [UI_EFFICIENCY]: Kriterium 3: Komfort

- **Plattformen:** Apps für Mobile & alle gängigen Browser-Erweiterungen
- **Autofill & Passkeys:** Biometrischer Login & moderne **Passkey-Verwaltung**

<!-- [Folie 7: UI_EFFICIENCY] -->
<!--
[SPRECHTEXT]
Bezüglich des Komforts bieten alle Kandidaten ausgereifte Applikationen für gängige Betriebssysteme und Browser. Die Integration von Autofill-Funktionen via Biometrie arbeitet fehlerfrei. Zudem unterstützen alle drei Anbieter bereits den modernen Anmeldestandard über Passkeys.
-->

---

# [MASK_ING]:<br> Feature: E-Mail-Aliasse

- **Proton Pass:** Native **"Hide-my-Email"-Funktion** (Spamschutz)
- **NordPass:** E-Mail-Masking nur in **Premium-Tarifen** verfügbar
- **Bitwarden:** Nur über externe Drittanbieter-Dienste koppelbar

<!-- [Folie 8: MASK_ING] -->
<!--
[SPRECHTEXT]
Das Zusatzfeature E-Mail-Aliasse dient dem Schutz vor Spam und Datenlecks. Proton Pass bietet diese Funktion nativ in der Basisversion an. NordPass verlangt hierfür ein Premium-Abo. Bei Bitwarden ist die Funktion nur über die manuelle Verknüpfung externer Drittanbieter verfügbar.
-->

---

# [AUDIT_LOG]:<br> Feature: Quellcode

- **Bitwarden & Proton Pass:** Vollständiger **Open-Source-Code**
- **NordPass:** Proprietär, aber regelmäßige externe Audits (**Cure53**)

<!-- [Folie 9: AUDIT_LOG] -->
<!--
[SPRECHTEXT]
Ein kritischer Faktor ist die Transparenz des Quellcodes. Bitwarden und Proton Pass sind vollständig quelloffen und somit öffentlich verifizierbar. NordPass ist proprietär, kompensiert dies jedoch durch regelmäßige, unabhängige Sicherheitsaudits, unter anderem durch die renommierte Firma Cure53.
-->

---

# [SUMMARY]: Zusammenfassung

* **Sicherheit:** **Zero-Knowledge-Verschlüsselung** bei allen drei Diensten
* **Kosten:** **Bitwarden & Proton Pass** gratis, **NordPass Free** restriktiv
* **Komfort:** **Autofill & Top-Apps** überall, NordPass mit bester UI

<!-- [Folie 10: SUMMARY] -->
<!--
[SPRECHTEXT]
Zusammenfassend: Die Zero-Knowledge-Sicherheit ist überall fehlerfrei. Der Unterschied liegt im Preismodell: Bitwarden bietet die stärkste Gratisversion für unbegrenzte Geräte. Proton Pass zieht gratis fast gleich, punktet aber primär mit integriertem Spamschutz. NordPass Free blockiert den Alltag durch das Ein-Geräte-Limit, bietet dafür aber das modernste Interface.
-->

---

# [LOG_OUT]:<br> Fazit & Empfehlung

<div class="columns">
<div class="column-box">
<h3>> Bitwarden</h3>
<span class="compact">Für Open-Source-Fans, Self-Hosting & <strong>Sparfüchse</strong>.</span>
<img src="./bilder/bitwarden.png" style="display:block;" />
</div>
<div class="column-box">
<h3>> Proton Pass</h3>
<span class="compact">Für maximalen <strong>Datenschutz</strong> & integrierten Spamschutz.</span>
<img src="./bilder/proton_pass.png" style="display:block;" />
</div>
<div class="column-box">
<h3>> NordPass</h3>
<span class="compact">Für <strong>Design-Liebhaber</strong> mit Budget für Premium.</span>
<img src="./bilder/nordpass-logo_1-1-30.png" style="display:block;" />
</div>
</div>
<!-- [Folie 11: LOG_OUT] -->
<!--
[SPRECHTEXT]
Das Fazit für die Praxis: Bitwarden ist die optimale Lösung für Open-Source-Anwender und preisbewusste Nutzer. Proton Pass empfiehlt sich bei Fokus auf Privatsphäre und E-Mail-Maskierung. NordPass ist eine exzellente, jedoch kostenpflichtige Premium-Option für höchste Designansprüche. Ich bedanke mich für Ihre Aufmerksamkeit.
-->