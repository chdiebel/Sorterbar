---
title: "Datenschutzerklärung — IMGCabinet"
lang: de
noindex: true
---

# Datenschutzerklärung — IMGCabinet

*[English version](privacy-policy)*

**Stand: 1. Oktober 2026**

Diese Erklärung beschreibt, wie die Android-App IMGCabinet und diese
Begleitseite mit personenbezogenen Daten umgehen. Sie gilt nicht für den
Google Play Store, der von Google betrieben wird und eine eigene
Datenschutzerklärung hat.

In Kürze: Die App selbst erhebt und überträgt keine Daten, da ihr die
Berechtigung zur Internetnutzung fehlt. Alles, was Sie in der App anlegen,
bleibt im app-eigenen Speicher Ihres Telefons und verlässt das Gerät nur,
wenn Sie selbst etwas exportieren oder teilen oder den Sync-Ordner
einschalten und eine App Ihrer Wahl ihn übertragen lassen (Ziffer 2.6). Es gibt keine Konten, keine
Anmeldung, keine Analyse, keine Absturzberichte, keine Werbung und keine
Dienste Dritter in der App. Beim Aufruf dieser Website fallen jedoch, wie bei
praktisch jeder Website, technisch bedingte Server-Logs beim Hosting-Anbieter
an — Einzelheiten dazu unter [Hosting dieser Website](#3-hosting-dieser-website).

## 1. Verantwortlicher

Christopher Diebel<br>
Taunusstraße 9b<br>
63694 Limeshain<br>
Deutschland

E-Mail: Sorterbar@gmail.com

Verantwortlicher im Sinne des Art. 4 Nr. 7 DSGVO. Die App wird bei Google Play
unter dem Entwicklernamen „Sorterbar“ veröffentlicht.

## 2. Datenverarbeitung in der App

### 2.1 Gespeicherte Inhalte

Alles Folgende stammt von Ihnen und liegt in einem Speicherbereich, der der App
gehört und für andere Apps nicht lesbar ist:

- die Bilder, die Sie hinzufügen, und die daraus erzeugten Vorschaubilder
- Texte und Links, die Sie mit der App teilen oder in ihr schreiben
- Titel, Notizen und Schlagwörter, die Sie eintippen
- die Ordner, die Sie anlegen, und welche Bilder Sie darin ablegen
- Text, der aus einem Bild erkannt wurde, wenn Sie das anfordern oder einschalten
- das unbeschnittene Original eines Screenshots, wenn Sie das Häkchen dafür setzen
- Ihre Einstellungen, etwa die gewählte Akzentfarbe

Nichts davon wird übertragen, und nichts davon ist dem Anbieter zugänglich.
Wenn Sie die App deinstallieren, löscht Android all das mit; Dateien in einem
selbst gewählten Sync-Ordner (Ziffer 2.6) bleiben dort, bis Sie sie löschen. Die App ist zudem
von der Android-eigenen Cloud-Sicherung ausgenommen, diese Daten werden also
nicht in Ihr Google-Konto kopiert.

### 2.2 Netzwerkzugriff

Eine Android-App darf das Netz nur nutzen, wenn sie die Berechtigung `INTERNET`
anmeldet. IMGCabinet meldet sie nicht an — sie ist ausdrücklich aus dem
Manifest der App entfernt. Das Betriebssystem verweigert deshalb jeden Versuch,
eine Netzwerkverbindung zu öffnen, gleich ob er aus dem Code der App oder aus
einer darin enthaltenen Bibliothek stammt. Das erzwingt Android, es ist kein
Versprechen.

In der Berechtigungsliste im Play Store kann Ihnen `ACCESS_NETWORK_STATE`
auffallen, angezeigt etwa als „Netzwerkverbindungen abrufen". Sie kommt mit
einer der quelloffenen Bibliotheken mit, auf denen die App aufbaut, und erlaubt
lediglich zu *lesen*, ob eine Verbindung besteht — nicht, sie zu nutzen. Ohne
`INTERNET` kann ohnehin nichts übertragen werden.

### 2.3 Berechtigungen

**Vibration (`VIBRATE`)** — kurzes haptisches Feedback bei Gesten.

**Kamera (`CAMERA`)** — für die eingebaute Kamera der App, die ein Foto direkt
in einen Ordner Ihrer Bibliothek aufnimmt. Android fragt Sie danach, wenn Sie
diese Kamera zum ersten Mal öffnen, nicht vorher, und Sie können die
Berechtigung jederzeit in den Systemeinstellungen verweigern oder entziehen;
alles andere in der App funktioniert auch ohne sie. Die Kamera läuft nur,
solange ihr Bildschirm geöffnet ist. Fotos werden wie jedes andere Bild im
eigenen Speicher der App abgelegt, ohne Standortangaben, und eine
Mikrofon-Berechtigung hat die App nicht.

Das sind die einzigen beiden. Insbesondere fragt die App nicht nach Zugriff auf Ihre
Fotos. Wenn Sie Bilder aus der Galerie hinzufügen, öffnet sich die Auswahl von
Android selbst: Sie wählen die Bilder dort aus, und die App erhält nur diese.
Den Rest Ihrer Fotosammlung bekommt sie nie zu sehen, und eine Berechtigung
braucht sie dafür nicht. Bilder und Texte, die Sie aus einer anderen App heraus
teilen, kommen auf dieselbe Weise an — nur das, was Sie übergeben. Ein geteilter
Link wird als Text gespeichert; die App öffnet oder lädt ihn nie. Tippen Sie in
einem gespeicherten Text auf einen Link, wird die Adresse an Ihren Browser
übergeben, der sie mit seinen eigenen Berechtigungen lädt; die App selbst baut
weiterhin keine Verbindung auf.

### 2.4 Texterkennung in Bildern

Die App kann Wörter in einem Bild lesen, damit Sie später danach suchen können.
Das läuft vollständig auf Ihrem Telefon, mit einem Erkennungsmodell, das in der
App selbst enthalten ist. Das Bild wird nicht hochgeladen, und es geht keine
Anfrage hinaus — was aus dem oben genannten Grund auch nicht möglich wäre. Der
erkannte Text wird beim Bild im app-eigenen Speicher abgelegt.

### 2.5 Teilen, Sicherungen und Export

Die App kann Ihre Bibliothek oder einen einzelnen Ordner in eine ZIP-Datei
packen und an die Teilen-Funktion von Android übergeben. Das geschieht nur auf
Ihre Veranlassung, und Sie wählen das Ziel — einen Cloud-Speicher, einen
Dateimanager, einen Messenger oder etwas anderes. Ab diesem Moment gelten die
Datenschutzbestimmungen des von Ihnen gewählten Ziels. Der Anbieter hat weder
Zugriff darauf noch Kenntnis davon.

Dasselbe gilt für das Teilen eines einzelnen Bildes.

### 2.6 Sync-Ordner (optional)

In den Einstellungen der App können Sie einen Ordner auf Ihrem Telefon wählen
und die Synchronisierung einschalten. Die App schreibt dann eine Kopie Ihrer
Bibliothek in diesen Ordner und liest die gleichartigen Dateien, die Ihre
anderen Geräte dort ablegen:

- Ihre Bilder und Texte, als gewöhnliche Dateien;
- deren Titel, Notizen, Schlagwörter und Schlagwortfarben, Ihre Ordner und die
  Angabe, welches Bild in welchem Ordner liegt;
- für jedes Gerät: eine zufällig erzeugte Kennung, einen Namen für das Gerät
  wie dessen Modell sowie die Zeitpunkte, zu denen Einträge angelegt, geändert
  und gelöscht wurden.

Aufbewahrte Screenshot-Originale, KI-Profile und Einstellungen werden dort
nicht abgelegt.

Die App selbst überträgt weiterhin nichts — ihr fehlt die Berechtigung zur
Internetnutzung. Den Ordner zwischen Ihren Geräten abzugleichen, übernimmt eine
separate App, die Sie selbst auswählen und einrichten, etwa eine
Synchronisierungs-App oder die App eines Cloud-Speicherdienstes. Solche Apps
sind Angebote Dritter; der Anbieter steht in keiner Verbindung zu ihnen und hat
keinen Einfluss auf sie, und es gelten deren eigene Bedingungen und
Datenschutzerklärungen. Nutzen Sie einen Cloud-Speicherdienst, liegt Ihre
Bibliothek dort nach dessen Bedingungen.

Den Zugriff gewähren Sie über die Ordnerauswahl von Android selbst, für genau
den einen gewählten Ordner und sonst nichts. Schalten Sie die Synchronisierung
aus, schreibt die App nichts mehr in den Ordner; die Bibliothek auf Ihrem
Telefon und die Dateien, die bereits im Ordner liegen, bleiben, wie sie sind.
Sie können den Ordner jederzeit mit einem Dateimanager oder der Sync-App
löschen.

## 3. Hosting dieser Website

Diese Seiten werden über GitHub Pages gehostet, einen Dienst der GitHub, Inc.,
88 Colin P. Kelly Jr. Street, San Francisco, CA 94107, USA (Teil der Microsoft
Corporation). Beim Aufruf dieser Seite verarbeitet GitHub automatisch
technische Daten Ihres Zugriffs in sogenannten Server-Logfiles, unter anderem:

- IP-Adresse
- Datum und Uhrzeit der Anfrage
- aufgerufene Seite und übertragene Datenmenge
- Browsertyp und Betriebssystem
- die zuvor besuchte Seite (Referrer)

Diese Daten werden von GitHub zum Zweck der Auslieferung, Stabilität und
Sicherheit der Website verarbeitet; dem Anbieter dieser Seite liegen sie nicht
vor, und es findet kein Tracking statt. Rechtsgrundlage ist das berechtigte
Interesse an einem sicheren und funktionsfähigen Betrieb der Website
(Art. 6 Abs. 1 lit. f DSGVO). Da GitHub in den USA sitzt, ist mit der
Verarbeitung eine Datenübermittlung in ein Drittland verbunden; GitHub stützt
diese nach eigenen Angaben auf die EU-Standardvertragsklauseln. Weitere
Informationen enthält die [Datenschutzerklärung von
GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 4. Rechtsgrundlage der Datenverarbeitung durch den Anbieter

Der Anbieter selbst — unabhängig vom Hosting nach Ziffer 3 — erhebt und
erhält keine personenbezogenen Daten aus der Nutzung der App. Die in Ziffer 2
beschriebenen Informationen werden ausschließlich lokal auf Ihrem eigenen
Gerät und unter Ihrer eigenen Kontrolle verarbeitet; sie erreichen den
Anbieter nicht. Schreiben Sie den Anbieter per E-Mail an, verarbeitet er die
dabei mitgeteilten Daten (z. B. Ihre E-Mail-Adresse) zur Bearbeitung Ihrer
Anfrage auf Grundlage von Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse
an der Kommunikation mit Nutzerinnen und Nutzern).

## 5. Rechte der betroffenen Personen

Ihnen stehen gegenüber dem Anbieter grundsätzlich die Rechte auf Auskunft
(Art. 15 DSGVO), Berichtigung (Art. 16 DSGVO), Löschung (Art. 17 DSGVO),
Einschränkung der Verarbeitung (Art. 18 DSGVO), Datenübertragbarkeit
(Art. 20 DSGVO) und Widerspruch (Art. 21 DSGVO) zu, ebenso das Recht auf
Beschwerde bei einer Aufsichtsbehörde (Art. 77 DSGVO), etwa dem
Hessischen Beauftragten für Datenschutz und Informationsfreiheit. Da der
Anbieter zu Ihrer Nutzung der App keine Daten hält, laufen entsprechende
Anfragen zur App-Nutzung mangels vorhandener Daten praktisch leer; die Daten
selbst können Sie jederzeit unmittelbar aus der App heraus exportieren oder
durch Löschen einzelner Bilder, durch Löschen eines eingerichteten
Sync-Ordners beziehungsweise durch Deinstallation der App entfernen. Für Anfragen zu den in Ziffer 3 und 4 genannten Verarbeitungen
wenden Sie sich an die oben genannte Adresse.

## 6. Google Play

Herunterladen und Installieren laufen über den Google Play Store. Google
verarbeitet dabei Daten — etwa zu Ihrem Konto, Ihrem Gerät und Ihrem
Download-Verlauf — als eigener Verantwortlicher und nach eigenen Bedingungen.
Das liegt außerhalb des Einflussbereichs des Anbieters und ist nicht Gegenstand
dieser Erklärung. Die Datenschutzerklärung von Google finden Sie unter
<https://policies.google.com/privacy>.

Wenn Sie die App aus einer Datei statt über Play installieren, ist Google gar
nicht beteiligt.

## 7. Kinder

Die App richtet sich nicht an Kinder und enthält nichts, was für sie bestimmt
wäre. Sie erhebt von niemandem Daten, von Kindern also auch nicht.

## 8. Änderungen dieser Erklärung

Sollte sich die App in einer Weise ändern, die eines der obigen Punkte
berührt, wird diese Seite angepasst und das Datum oben mit ihr. Da die App das
Netz nicht erreichen kann, wird sie Sie nicht benachrichtigen; maßgeblich ist
stets die hier veröffentlichte Fassung.

## 9. Kontakt

Sorterbar@gmail.com

---

[Impressum](../impressum) · [Legal notice](../legal-notice)
