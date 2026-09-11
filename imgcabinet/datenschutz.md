# Datenschutzerklärung — IMGCabinet

*[English version](privacy-policy)*

**Stand: 11. September 2026**

Diese Erklärung beschreibt, wie die Android-App IMGCabinet mit Informationen
umgeht. Sie gilt für die App selbst, nicht für den Google Play Store — der wird
von Google betrieben und hat eine eigene Datenschutzerklärung.

## Kurz gesagt

IMGCabinet erhebt nichts, sendet nichts und hat auch keine Möglichkeit dazu.
Der App ist die Berechtigung, das Internet zu benutzen, nicht erteilt. Alles,
was Sie hineinlegen, bleibt im app-eigenen Speicher Ihres Telefons. Es verlässt
das Gerät nur, wenn Sie selbst etwas exportieren oder teilen.

Es gibt keine Konten, keine Anmeldung, keine Analyse, keine Absturzberichte,
keine Werbung und keine Dienste Dritter in der App.

## Verantwortlicher

Christopher Diebel<br>
Taunusstraße 9b<br>
63694 Limeshain<br>
Deutschland

E-Mail: Sorterbar@gmail.com

Verantwortlicher im Sinne des Art. 4 Nr. 7 DSGVO. Die App wird bei Google Play
unter dem Entwicklernamen „Sorterbar“ veröffentlicht.

## Was die App speichert und wo

Alles Folgende stammt von Ihnen und liegt in einem Speicherbereich, der der App
gehört und für andere Apps nicht lesbar ist:

- die Bilder, die Sie hinzufügen, und die daraus erzeugten Vorschaubilder
- Titel, Notizen und Schlagwörter, die Sie eintippen
- die Ordner, die Sie anlegen, und welche Bilder Sie darin ablegen
- Text, der aus einem Bild erkannt wurde, wenn Sie das anfordern oder einschalten
- das unbeschnittene Original eines Screenshots, wenn Sie das Häkchen dafür setzen
- Ihre Einstellungen, etwa die gewählte Akzentfarbe

Nichts davon wird übertragen, und nichts davon ist dem Anbieter zugänglich.
Wenn Sie die App deinstallieren, löscht Android all das mit. Die App ist zudem
von der Android-eigenen Cloud-Sicherung ausgenommen, diese Daten werden also
nicht in Ihr Google-Konto kopiert.

## Warum die App nichts senden kann

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

## Berechtigungen, die die App nutzt

**Fotos und Medien (`READ_MEDIA_IMAGES`, `READ_MEDIA_VISUAL_USER_SELECTED`)**
Zwei Zwecke, die beide Zugriff auf die bereits vorhandenen Bilder brauchen:

1. Bilder auswählen, um sie in die Bibliothek aufzunehmen.
2. Einen Screenshot nach dem Speichern aus Ihrer Galerie löschen — aber nur
   dieses eine Bild und nur dann, wenn Sie beim Speichern das Häkchen setzen.
   Dafür muss die App das Bild unter Ihren Fotos finden, was Lesezugriff
   voraussetzt. Die Löschung selbst lässt Android Sie anschließend bestätigen;
   ohne diese Bestätigung kann die App nichts löschen.

Unter Android 12 und älter heißen die entsprechenden Berechtigungen
`READ_EXTERNAL_STORAGE` und `WRITE_EXTERNAL_STORAGE`, weshalb sie mit einer
Versionsgrenze auftauchen.

Die App liest nur, was sie für die von Ihnen angestoßene Handlung braucht. Sie
durchsucht, indiziert oder katalogisiert Ihre Fotosammlung nicht.

**Vibration (`VIBRATE`)** — kurzes haptisches Feedback bei Gesten.

## Texterkennung in Bildern

Die App kann Wörter in einem Bild lesen, damit Sie später danach suchen können.
Das läuft vollständig auf Ihrem Telefon, mit einem Erkennungsmodell, das in der
App selbst enthalten ist. Das Bild wird nicht hochgeladen, und es geht keine
Anfrage hinaus — was aus dem oben genannten Grund auch nicht möglich wäre. Der
erkannte Text wird beim Bild im app-eigenen Speicher abgelegt.

## Teilen, Sicherungen und Export

Die App kann Ihre Bibliothek oder einen einzelnen Ordner in eine ZIP-Datei
packen und an die Teilen-Funktion von Android übergeben. Das geschieht nur auf
Ihre Veranlassung, und Sie wählen das Ziel — einen Cloud-Speicher, einen
Dateimanager, einen Messenger oder etwas anderes. Ab diesem Moment gelten die
Datenschutzbestimmungen des von Ihnen gewählten Ziels. Der Anbieter hat weder
Zugriff darauf noch Kenntnis davon.

Dasselbe gilt für das Teilen eines einzelnen Bildes.

## Rechtsgrundlage und Ihre Rechte

Da der Anbieter keine personenbezogenen Daten erhebt oder erhält, findet auf
seiner Seite keine Verarbeitung statt, für die eine Rechtsgrundlage nach Art. 6
DSGVO erforderlich wäre. Die oben beschriebenen Informationen werden lokal auf
Ihrem eigenen Gerät und unter Ihrer eigenen Kontrolle verarbeitet.

Aus demselben Grund fände ein Auskunfts-, Berichtigungs-, Löschungs-,
Einschränkungs-, Übertragbarkeits- oder Widerspruchsverlangen nach Art. 15 bis
22 DSGVO beim Anbieter nichts vor, worauf es sich beziehen könnte. Sie können
sich dennoch jederzeit an die oben genannte Adresse wenden, und Ihnen steht das
Recht auf Beschwerde bei einer Aufsichtsbehörde zu. Die Daten selbst liegen
vollständig bei Ihnen: Sie lassen sich jederzeit aus der App heraus
exportieren und durch Löschen einzelner Bilder oder durch Deinstallation der
App entfernen.

## Google Play

Herunterladen und Installieren laufen über den Google Play Store. Google
verarbeitet dabei Daten — etwa zu Ihrem Konto, Ihrem Gerät und Ihrem
Download-Verlauf — als eigener Verantwortlicher und nach eigenen Bedingungen.
Das liegt außerhalb des Einflussbereichs des Anbieters und ist nicht Gegenstand
dieser Erklärung. Die Datenschutzerklärung von Google finden Sie unter
<https://policies.google.com/privacy>.

Wenn Sie die App aus einer Datei statt über Play installieren, ist Google gar
nicht beteiligt.

## Kinder

Die App richtet sich nicht an Kinder und enthält nichts, was für sie bestimmt
wäre. Sie erhebt von niemandem Daten, von Kindern also auch nicht.

## Änderungen dieser Erklärung

Sollte sich die App in einer Weise ändern, die eines der obigen Punkte
berührt, wird diese Seite angepasst und das Datum oben mit ihr. Da die App das
Netz nicht erreichen kann, wird sie Sie nicht benachrichtigen; maßgeblich ist
stets die hier veröffentlichte Fassung.

## Kontakt

Sorterbar@gmail.com

---

[Impressum](../impressum) · [Legal notice](../legal-notice)
