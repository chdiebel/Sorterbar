# Privacy Policy — IMGCabinet

*[Deutsche Fassung](datenschutz)*

**Last updated: 11 September 2026**

This policy explains how the IMGCabinet app for Android handles information. It
is written for the app itself; it does not cover the Google Play Store, which
is operated by Google and has its own policy.

## The short version

IMGCabinet does not collect anything, does not send anything anywhere, and has
no way to do either. The app is not granted permission to use the internet.
Everything you put into it stays in the app's own storage on your phone, and
the only way anything leaves is if you deliberately export or share it
yourself.

There are no accounts, no sign-in, no analytics, no crash reporting, no
advertising, and no third-party services of any kind inside the app.

## Who is responsible

Christopher Diebel<br>
Taunusstraße 9b<br>
63694 Limeshain<br>
Germany

Email: Sorterbar@gmail.com

This is the controller within the meaning of Article 4(7) of the General Data
Protection Regulation (GDPR). The app is published on Google Play under the
developer name “Sorterbar”.

## What the app stores, and where

Everything below is written by you and kept in storage that belongs to the app
and is not readable by other apps:

- the pictures you add, and the thumbnails the app generates from them
- titles, notes and tags you type
- the folders you create and which pictures you file into them
- text recognised from a picture, when you ask for it or switch it on
- the uncropped original of a screenshot, when you tick the box to keep it
- your settings, such as the highlight colour

None of this is transmitted, and none of it is available to the developer. If
you uninstall the app, Android deletes all of it. The app is also excluded from
Android's own cloud backup, so this data is not copied to your Google account.

## Why the app has no way to send anything

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

## Permissions the app does use

**Photos and media (`READ_MEDIA_IMAGES`, `READ_MEDIA_VISUAL_USER_SELECTED`)**
Two purposes, both of which need access to the pictures already on your phone:

1. Choosing pictures to add to your library.
2. Deleting a screenshot from your gallery after you have saved it into the
   app — but only for that one picture, and only when you tick that box while
   saving it. To do this the app has to find that picture among your photos,
   which requires read access. Android then asks you to confirm the deletion
   itself; the app cannot delete anything without that confirmation.

On Android 12 and older the equivalent permissions are `READ_EXTERNAL_STORAGE`
and `WRITE_EXTERNAL_STORAGE`, which is why they appear with a version limit.

The app reads only what it needs for the action you started. It does not scan,
index or catalogue your photo library.

**Vibration (`VIBRATE`)** — short haptic feedback when a gesture is recognised.

## Reading text in pictures

The app can read words inside a picture so you can search for them later. This
runs entirely on your phone, using a recognition model that is included in the
app itself. The picture is not uploaded, and no request goes out — it could
not, for the reason given above. The recognised text is saved with the picture
in the app's own storage.

## Sharing, backups and exports

The app can pack your library, or a single folder, into a ZIP file and hand it
to Android's share sheet. This happens only when you ask for it, and you choose
where the file goes — a cloud drive, a file manager, a messaging app, or
anywhere else. From that moment the file is subject to whatever privacy terms
apply to the destination you picked. The developer has no access to it and no
knowledge that it exists.

The same applies to sharing a single picture out of the app.

## Legal basis and your rights

Because the developer neither collects nor receives any personal data, there is
no processing of your data by the developer for which a legal basis under
Article 6 GDPR would be required. The information described above is processed
locally on your own device, under your own control.

For the same reason, a request under Articles 15 to 22 GDPR — access,
rectification, erasure, restriction, portability, objection — would find
nothing on the developer's side to act on. You remain free to contact the
address above, and you have the right to lodge a complaint with a supervisory
authority. The data itself is entirely in your hands: it can be exported from
within the app at any time, and removed by deleting individual pictures or by
uninstalling the app.

## Google Play

Downloading and installing the app happens through the Google Play Store.
Google processes data in connection with that — such as your account, device
and download history — as its own controller and under its own terms. This is
outside the developer's control and is not covered by this policy. Google's
privacy policy is at <https://policies.google.com/privacy>.

If you install the app from a file rather than from Play, Google is not
involved at all.

## Children

The app is not directed at children and contains nothing intended for them. It
collects no data from anyone, children included.

## Changes to this policy

If the app ever changes in a way that affects any of the above, this page will
be updated and the date at the top changed with it. Because the app cannot
reach the network, it will not notify you; the current version is always the
one published here.

## Contact

Sorterbar@gmail.com

---

[Legal notice](../legal-notice) · [Impressum](../impressum)
