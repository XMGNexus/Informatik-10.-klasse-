# Quellenverzeichnis: Passwortmanager-Vergleich (NordPass, Bitwarden & Proton Pass)

---

## Logos von den Passwortmanagern:

NordPass: https://www.heise.de/download/product/nordpass - 30.09.2026 11:07 Uhr

Bitwarden: https://commons.wikimedia.org/wiki/File:Bitwarden_logo.svg - 30.09.2026 11:08 Uhr

Proton Pass: https://proton.me/de/blog/pass-logo-story - 30.09.2026 11:11 Uhr 

---

## 1. Kriterium: Sicherheit & Verschlüsselung

*   **NordPass & XChaCha20-Verschlüsselung:** NordPass nutzt anstelle des klassischen AES-256 den moderneren XChaCha20-Algorithmus. Laut Hersteller bietet dieser eine schnellere Verschlüsselung auf Mobilgeräten ohne Hardware-Beschleunigung und ist resistenter gegen bestimmte Cyber-Angriffe.
    *   *Quelle:* [NordPass Official Website - XChaCha20 Encryption](https://nordpass.com "nordpass xchacha20 encryption")
*   **Bitwarden & AES-256 / Zero-Knowledge:** Bitwarden setzt auf die bewährte AES-256-Bit-Verschlüsselung mit PBKDF2 SHA-256 und eine strikte Zero-Knowledge-Architektur, bei der Passwörter nur lokal auf dem Gerät ver- und entschlüsselt werden.
    *   *Quelle:* [Bitwarden Help Center - Security Architecture](https://bitwarden.com/help/ "bitwarden security architecture")
*   **Sicherheits-Audits (Cure53):** Die Behauptung, dass die proprietären Teile von NordPass regelmäßig von renommierten Drittanbietern geprüft werden, wird durch die Audit-Berichte der IT-Sicherheitsfirma Cure53 gestützt.
    *   *Quelle:* [Cure53 Audit Reports Overview](https://cure53.de "cure53 audit reports")

---

## 2. Kriterium: Kosten & Gerätelimits

*   **Bitwarden Free-Tarif:** Bitwarden bietet einen der großzügigsten Gratis-Tarife auf dem Markt. Er erlaubt die unbegrenzte Speicherung von Passwörtern und die simultane Synchronisation über unbegrenzt viele Geräte hinweg.
    *   *Quelle:* [Bitwarden Pricing and Plans](https://bitwarden.com/pricing/ "bitwarden pricing plans")
*   **NordPass Free-Restriktion:** Im Gegensatz dazu erlaubt der Free-Tarif von NordPass zwar ebenfalls unbegrenzten Speicherplatz, schränkt die Nutzung jedoch stark ein: Der Login ist immer nur auf **einem aktiven Gerät gleichzeitig** möglich. Wechselt man das Gerät, wird man auf dem anderen abgemeldet.
    *   *Quelle:* [NordPass Free vs Premium Comparison](https://nordpass.com/pricing/ "nordpass pricing free premium")

---

## 3. Feature: E-Mail-Aliasse & Quellcode

*   **Proton Pass (Hide-my-Email & Open Source):** Proton Pass integriert nativ die Erstellung von E-Mail-Aliassen (über den hauseigenen Dienst SimpleLogin), um die echte E-Mail-Adresse vor Spam und Datenlecks zu schützen. Zudem ist der gesamte Code vollständig quelloffen (Open Source).
    *   *Quelle:* [Proton Pass Official Product Page](https://proton.me/pass "proton pass official page")
*   **E-Mail-Maskierung bei Mitbewerbern:** Bei NordPass ist die E-Mail-Maskierung an die Premium-Pakete gekoppelt. Bitwarden bietet keine native Generierung, erlaubt jedoch im Dashboard die Integration von API-Schlüsseln externer Anbieter wie SimpleLogin oder Fastmail.
    *   *Quelle:* [Bitwarden Help - Email Aliases Integration](https://bitwarden.com/help/ "bitwarden email alias integration")
---

# Erstellung der HTML-Datei 
Prompt in Gemini: "Erstelle zu diesem Code (Gesamter Code von praesentation.md) eine HTML-Datei" 07.10.26 11:20 Uhr

# Erstellung der PDF-Datei
Prompt in Gemini: "Erstelle auch eine PDF-Version dieses Codes" 07.10.26 11:23 Uhr