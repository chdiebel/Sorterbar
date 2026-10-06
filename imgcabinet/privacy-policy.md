---
title: "Privacy policy — IMGCabinet"
lang: en
noindex: true
---

# Privacy Policy — IMGCabinet

*[Deutsche Fassung](datenschutz)*

**Last updated: 1 October 2026**

This policy explains how the IMGCabinet Android app and this accompanying
website handle personal data. It does not cover the Google Play Store, which
is operated by Google and has its own privacy policy.

In short: the app itself neither collects nor transmits any data, because it
is not granted permission to use the internet. Everything you put into the
app stays in its own storage on your phone and leaves the device only if you
deliberately export or share it yourself, or switch on the sync folder and
let another app of your choice move it (section 2.6). There are no accounts, no sign-in,
no analytics, no crash reporting, no advertising, and no third-party services
inside the app. Visiting this website, like practically any website, does
generate technical server logs at the hosting provider — see [Hosting of
this website](#3-hosting-of-this-website) for details.

## 1. Who is responsible

Christopher Diebel<br>
Taunusstraße 9b<br>
63694 Limeshain<br>
Germany

Email: Sorterbar@gmail.com

This is the controller within the meaning of Article 4(7) of the General Data
Protection Regulation (GDPR). The app is published on Google Play under the
developer name “Sorterbar”.

## 2. Data processing in the app

### 2.1 What the app stores, and where

Everything below is written by you and kept in storage that belongs to the app
and is not readable by other apps:

- the pictures you add, and the thumbnails the app generates from them
- texts and links you share into the app or write in it
- titles, notes and tags you type
- the folders you create and which pictures you file into them
- text recognised from a picture, when you ask for it or switch it on
- the uncropped original of a screenshot, when you tick the box to keep it
- your settings, such as the highlight colour

None of this is transmitted, and none of it is available to the developer. If
you uninstall the app, Android deletes all of it; files in a sync folder you
chose yourself (section 2.6) stay there until you delete them. The app is also excluded from
Android's own cloud backup, so this data is not copied to your Google account.

### 2.2 Network access

Android apps can only use the network if they declare the `INTERNET`
permission. IMGCabinet does not declare it — it is explicitly removed from the
app's manifest — so the operating system will refuse any attempt to open a
network connection, whether from the app's own code or from a library inside
it. This is enforced by Android, not by a promise.

You may notice `ACCESS_NETWORK_STATE` in the permission list on the store page,
shown as something like "view network connections". It arrives with one of the
open-source libraries the app is built on. It only allows reading whether a
connection exists; it does not allow using one. Without `INTERNET`, nothing can
be transmitted regardless.

### 2.3 Permissions

**Vibration (`VIBRATE`)** — short haptic feedback when a gesture is recognised.

**Camera (`CAMERA`)** — for the app's built-in camera, which takes a photo
straight into a folder of your library. Android asks you for it the first time
you open that camera, not before, and you can refuse or revoke it at any time
in the system settings; everything else in the app works without it. The
camera runs only while its screen is open. Photos are saved in the app's own
storage like every other picture, no location is recorded with them, and the
app has no microphone permission.

Those are the only two. In particular, the app does not ask for access to your
photos. When you add pictures from your gallery, Android's own picker opens:
you choose the pictures there, and the app receives only those. It never sees
the rest of your photo library and needs no permission for this. Pictures and
text you share into the app from another app arrive the same way — only what
you hand over. A shared link is saved as text; the app never opens or loads
it. Tapping a link in a saved text hands the address to your browser, which
loads it with its own permissions; the app itself still opens no connection.

### 2.4 Reading text in pictures

The app can read words inside a picture so you can search for them later. This
runs entirely on your phone, using a recognition model that is included in the
app itself. The picture is not uploaded, and no request goes out — it could
not, for the reason given above. The recognised text is saved with the picture
in the app's own storage.

### 2.5 Sharing, backups and exports

The app can pack your library, or a single folder, into a ZIP file and hand it
to Android's share sheet. This happens only when you ask for it, and you choose
where the file goes — a cloud drive, a file manager, a messaging app, or
anywhere else. From that moment the file is subject to whatever privacy terms
apply to the destination you picked. The developer has no access to it and no
knowledge that it exists.

The same applies to sharing a single picture out of the app.

### 2.6 Sync folder (optional)

In the app's settings you can choose a folder on your phone and switch on
sync. The app then writes a copy of your library into that folder, and reads
the same kind of files written there by your other devices:

- your pictures and texts, as ordinary files;
- their titles, notes, tags and tag colours, your folders, and which pictures
  are in which folder;
- for each device: a randomly generated identifier, a name for the device such
  as its model, and the times at which items were created, changed and
  deleted.

Kept screenshot originals, AI profiles and settings are not written there.

The app itself still transmits nothing — it has no internet permission. Moving
the folder between your devices is done by a separate app that you choose and
set up yourself, for example a file-synchronisation app or the app of a cloud
storage service. Such apps are offered by third parties; the developer has no
connection to them and no influence on them, and their own terms and privacy
policies apply. If you use a cloud storage service, your library is stored
there under that service's terms.

Access is granted through Android's own folder picker, for the one folder you
choose and nothing else. Switching sync off stops all writing to the folder;
the library on your phone and the files already in the folder stay as they
are. You can delete the folder at any time with a file manager or the sync app.

## 3. Hosting of this website

This website is hosted on GitHub Pages, a service of GitHub, Inc., 88 Colin P.
Kelly Jr. Street, San Francisco, CA 94107, USA (part of Microsoft
Corporation). When you visit this page, GitHub automatically processes
technical data about your visit in server log files, including:

- IP address
- date and time of the request
- the page requested and the amount of data transferred
- browser type and operating system
- the referring page

GitHub processes this data to deliver the page and to keep it stable and
secure; the developer of this site has no access to it, and no tracking takes
place. The legal basis is the legitimate interest in operating a secure,
functioning website (Article 6(1)(f) GDPR). Because GitHub is based in the
US, this involves a transfer of data to a third country; GitHub states that
it relies on the EU Standard Contractual Clauses for this. Further
information is available in [GitHub's privacy
statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 4. Legal basis for processing by the developer

Separately from the hosting described in section 3, the developer neither
collects nor receives any personal data from your use of the app. The
information described in section 2 is processed exclusively on your own
device, under your own control, and never reaches the developer. If you email
the developer, the data you provide (such as your email address) is processed
to handle your request, on the basis of Article 6(1)(f) GDPR (legitimate
interest in communicating with users).

## 5. Your rights

You generally have the right to access (Article 15 GDPR), rectification
(Article 16 GDPR), erasure (Article 17 GDPR), restriction of processing
(Article 18 GDPR), data portability (Article 20 GDPR) and objection
(Article 21 GDPR), as well as the right to lodge a complaint with a
supervisory authority (Article 77 GDPR) — for example the Hessian
Commissioner for Data Protection and Freedom of Information. Because the
developer holds no data about your use of the app, requests concerning app
usage will in practice find nothing to act on; the data itself can be
exported directly from within the app at any time, and removed by deleting
individual pictures, by deleting a sync folder you set up, or by uninstalling
the app. For requests concerning the
processing described in sections 3 and 4, contact the address above.

## 6. Google Play

Downloading and installing the app happens through the Google Play Store.
Google processes data in connection with that — such as your account, device
and download history — as its own controller and under its own terms. This is
outside the developer's control and is not covered by this policy. Google's
privacy policy is at <https://policies.google.com/privacy>.

If you install the app from a file rather than from Play, Google is not
involved at all.

## 7. Children

The app is not directed at children and contains nothing intended for them. It
collects no data from anyone, children included.

## 8. Changes to this policy

If the app ever changes in a way that affects any of the above, this page will
be updated and the date at the top changed with it. Because the app cannot
reach the network, it will not notify you; the current version is always the
one published here.

## 9. Contact

Sorterbar@gmail.com

---

[Legal notice](../legal-notice) · [Impressum](../impressum)
