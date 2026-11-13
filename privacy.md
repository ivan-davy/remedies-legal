---
layout: default
title: Privacy Policy
nav_order: 1
lang: en
---

# Privacy Policy

**Effective date:** 16 August 2026
**Last updated:** 14 November 2026


---

## Summary

The Remedies iOS application (the "App") does not collect personal data.

The App has no user accounts and no server-side component. Data entered into the App is stored on
the user's device in encrypted form. If the user turns on iCloud sync (part of Remedies Plus, off by
default), the App also keeps that data in the user's own iCloud account, encrypted on the device
with a key the Developer does not hold, so that it reaches the user's other devices (Section 4).
Apart from that, the App makes no network requests of its own; the only other network activity
associated with it is Apple's in-app purchase flow, and web pages or emails the user chooses to
open from it (Section 3). It contains no analytics, advertising or crash-reporting services.
Nothing entered into the App is transmitted to the Developer. The Developer has no access to that
data, on the device or in iCloud, and is therefore not in a position to disclose it.

The Developer's website, remediesapp.com (the "Website"), is a separate matter and is described in
Section 12. It is hosted by Vercel, counts page views with a cookie-free statistics service, and
holds the email addresses of people who ask to be told when the App is released. Nothing entered
into the App reaches the Website, and nothing collected by the Website reaches the App.

The sections below set this out in detail.

## 1. The Developer

The App is developed by **Ivan Davydov**, an individual entrepreneur registered in Georgia (the
"Developer"). No company or other legal entity is involved.

Contact: **ivandavy@remediesapp.com**, Batumi, Georgia. The Developer's full address is published in
the Impressum: <https://ivan-davy.github.io/remedies-legal/impressum>.

The Developer does not process the personal data entered into the App (see Sections 3 and 4) and is
therefore not a controller of that data. The Developer is a controller only of data that a user
sends to the Developer directly, such as the contents of a support email, and of the data processed
through the Website (Section 12).

## 2. Scope

This Privacy Policy applies to the App and to the Website, in each of its languages. It does not
apply to the App Store, which is operated by Apple under Apple's own privacy policy, nor to other
sites the Website links to. These legal documents are themselves hosted on GitHub Pages, and
GitHub's privacy statement applies to visits there.

## 3. Data collected

The Developer does not collect personal data through the App.

In particular, the App does **not**:

- create user accounts or request a name, email address or telephone number;
- transmit data entered into the App to the Developer or to any third party; the only copy that
  leaves the device is the encrypted one kept in the user's own iCloud account when the user turns
  on sync (Section 4);
- include analytics, attribution, advertising or crash-reporting software development kits;
- track users across apps or websites, and for that reason does not request tracking permission;
- access contacts, location, the calendar or the microphone, or read any data from Apple Health
  (what it can write there, at the user's request, is described in Section 4).

The only network activity associated with the App is:

- iCloud sync, while the user has it turned on (Section 4): the App exchanges the encrypted copy of
  its data with the private database of the user's iCloud account through Apple's CloudKit
  service, and Apple tells the App of changes with silent notifications, which are never shown;
- Apple's in-app purchase flow (see Section 9);
- web pages the user chooses to open from the App, shown in Safari inside the App: these legal
  documents (on GitHub Pages), the ideas board at remedies.fider.io (run by Fider), an Apple
  support page and the official sources linked in the register credits. Each is subject to the privacy policy of the site that serves it, and the App sends
  it nothing about the user. The App also opens the App Store when an update is needed to keep
  syncing;
- emails the user chooses to write from the App, which open in the user's own mail app addressed
  to the Developer. A feedback email is pre-filled, below the space for the user's message, with
  the App's version, the iOS version, the model of the device (for example "iPhone 15 Pro"), the
  App's language and whether Remedies Plus is active.
  Nothing from the user's records is included, and the user can change or delete any of it before
  sending.

## 4. Data stored on the device

The data listed below is stored on the user's device. With iCloud sync turned on, a copy also
travels as described under *iCloud sync* below. None of it is transmitted to the Developer.

| Category | Storage |
| --- | --- |
| Records of medicines, food supplements, medical supplies and equipment: names, active substances, strengths, forms, quantities, expiry dates, where each is kept, labels, notes, and the details taken from a patient leaflet | Encrypted app storage |
| Collections (the places items are kept) | Encrypted app storage |
| Courses, schedules, and the journal of taken and skipped doses and of the measurements the user records (such as body temperature or blood pressure) | Encrypted app storage |
| Photographs of packaging, of the item itself and of its leaflet or instructions | Encrypted files in the App's private storage |
| Reminder settings and the in-app reminder history | Encrypted app storage |
| Language, theme and other preferences, and recent searches | Encrypted app storage |
| With Remedies Plus, the list Siri reads to understand and answer the user (the names, active substances and strengths of the medicines and supplies, their usual amounts and the day's planned times) and the requests Siri leaves for the App | Encrypted files in the App's private storage, excluded from device backups |
| Whether Remedies Plus has been purchased (a copy kept so the App works offline) and the count of free uses of Smart Scan and Register Fill this month | Encrypted app storage |
| A reference list of medicines from public registers (for the United States, the FDA's National Drug Code Directory; for Italy, the open data of the Italian Medicines Agency, AIFA; for France, the Base de données publique des médicaments, BDPM; for Spain, the prescription nomenclator of the Spanish Agency of Medicines and Medical Devices, AEMPS; for Switzerland, Swissmedic’s Open Government Data; for Canada, Health Canada’s Drug Product Database, DPD; for Ukraine, the Ministry of Health’s State Register of Medicines, DRLZ, from data.gov.ua; for Poland, the Register of Medicinal Products, RPL, from dane.gov.pl; for the United Kingdom, the NHS Dictionary of Medicines and Devices, dm+d, from NHS TRUD), the same for every user and supplied with the App; it holds no personal data | The App's own files |

**Encryption.** The data is encrypted with a key that is generated on the device and stored in the
iOS Keychain. The App never transmits the key, and it is not accessible to the Developer. iOS
includes it in device backups, as described below. iCloud sync uses a separate key, described
under *iCloud sync*.

**Working copies.** To show a photograph, iOS needs it decrypted, so the App keeps a limited number of
decrypted copies in its cache directory; deleting a record deletes its copies. Photographs taken or
chosen in the App pass through the cache before they are encrypted, and those copies are deleted the
next time the App starts with its records readable; while the records are locked (the App cannot
read its key), they wait for a later start. A photograph is never stored unencrypted: one that cannot be encrypted (for
example, when the device is out of space) is not kept, and the App asks for it again. The last exported archive (Section 8) also stays in the cache until the
next export. The cache is part of the App's private storage, is not included in device backups, and
is cleared by *Reset the app* (Section 8).

**Device backups.** An iPhone backup, whether to iCloud or to a computer, includes the App's data in
encrypted form. The encryption key is included in the Keychain portion of the backup so that the
data remains readable after a restore. An **unencrypted** computer backup does not transfer
Keychain items to a *different* device; if such a backup is restored to new hardware, the App's
data will be unreadable. Before moving to a new device, the user should either use an encrypted
backup or export the data (see Section 8).

**iCloud sync.** Remedies Plus includes iCloud sync, which is off until the user turns it on in the
App's settings. While it is on, the App keeps a copy of the records, collections, courses,
schedules, journal, photographs and settings in the private database of the user's own iCloud
account, through Apple's CloudKit service, and brings it to the user's other devices signed in to
the same account. Two settings stay each device's own: whether reminders are on, and whether they
show names. Each item is encrypted on the device before it is sent, with a separate key that the
App creates and keeps in the user's iCloud Keychain, which Apple protects with end-to-end
encryption. Apple stores only the encrypted data and cannot read it; nor can the Developer, who
has no access to the user's iCloud account. What no encryption can hide remains visible to Apple:
how many items there are, their sizes, when each was created or changed, and that some carry a
file; each item's name in iCloud is a meaningless code. The copy counts against the user's iCloud
storage and is held by Apple under the user's iCloud terms. Turning sync off deletes nothing.
Settings → Data → *Delete the iCloud copy* deletes the copy in iCloud and turns sync off on every device;
the data on each device stays. Sync also stops when the user signs out of iCloud or Remedies Plus
is no longer active.

**Apple Health.** If the user turns on *Save to Apple Health* in the App's settings (part of
Remedies Plus), the App writes the measurements the user records in its journal (such as body
temperature, blood pressure, heart rate, blood glucose or body weight) to Apple Health on the
device, for the types the user allows in the iOS permission prompt. The App asks only for permission
to write; it does not read any data from Apple Health. What it writes is kept by Apple Health under
the user's control and is not transmitted to the Developer or to any third party, nor used for
advertising. The user can withdraw the permission at any time in the Health app or in the iOS
Settings. A measurement deleted in the App is deleted from Apple Health too (if the option is off at
the time, when it is next turned on), as is one changed to a value outside the range a measurement
can have; turning the option off or resetting the App deletes
nothing there, and the user can delete the data in the Health app at any time.

**Siri and Shortcuts.** With Remedies Plus, the user can log an intake or start adding an item by
speaking to Siri or through the Shortcuts app. So that Siri can recognise the user's records, the
App gives iOS their names and active substances, and keeps the list described in the table above,
which Siri reads to answer. Logging an intake this way requires the device to be unlocked. Apple
recognises the speech, and Apple's privacy policy governs what the user says to Siri and how iOS
uses the names it is given. The App receives only the request and sends nothing to the
Developer. Without Remedies Plus, Siri is given no names.

## 5. Camera and photo library

The App requests the following permissions only when a feature that requires them is used:

- **Camera** — to photograph an item, its packaging or its leaflet, and to read a pack's barcode
  while the camera is pointed at it. That live view is read on the device and not stored.
- **Photo library, "add only"** — to save a photograph from the App to the photo library, at the
  user's request.

An existing image is attached through the iOS photo picker, which gives the App only the images the
user selects and needs no permission. Images obtained in either way are stored in the App's
encrypted storage. They are not uploaded, except within the encrypted copy kept in the user's
iCloud when sync is on (Section 4).

## 6. Smart Scan

Text recognition on packaging and leaflets is performed **entirely on the device**, using Apple's
on-device text recognition and on-device language model. Neither the image nor the recognised text
is sent anywhere to be read, and neither is sent to the Developer or to any third party. A
photograph the user keeps with a record is stored like any other (Sections 4 and 5).

**Register Fill.** The App searches the register of medicines supplied with it (Section 4) on the
device and copies the product the user chooses into the record being added. The name typed and the
product chosen are not sent to the Developer or to any third party.

## 7. Reminders

Reminders are scheduled locally by iOS. The App does not use a push-notification server, and no
reminder is sent from outside the device. The only notifications that reach the device from
outside are the silent ones iCloud sends to report a change while sync is on, and they are never
shown. The content of reminders shown on the lock
screen is set by the user; by default, a reminder does **not** include the name of the medicine: it
says only what kind of record it is about (a medicine, a supply, a measurement, equipment), what is
happening (it is time, it has not been logged, a date is near or has passed, stock is running low or
has run out) and how many. When the user chooses to show names, a reminder also shows the record's
name and strength, or the measurement planned, and the time it is planned for; what the user saved with the schedule (the amount,
how it is taken, what it needs, the note) stays in the App. A reminder carries no photograph.

## 8. Data subject rights

As all data is held on the device and the Developer holds none of it, most rights are exercised
directly in the App:

- **Access and portability.** Settings → Data → *Export a backup* creates a zip archive of all data
  in the App — the records in JSON format, together with the packaging and leaflet photographs —
  and passes it to the iOS share sheet. So that it can be opened on any device, the archive is
  **not** encrypted. It should be handled with the same care as the data it contains and stored in
  a private location. The App does not send the archive anywhere; its destination is chosen by the
  user. Settings → Data → *Restore from a backup* restores an archive, replacing the data currently
  in the App, and, while iCloud sync is on, on all the user's devices.
- **Erasure.** Settings → Reset → *Reset the app* deletes everything the App holds on the device:
  the records, photographs, courses, journal, collections, settings and the working copies in its
  cache. Two things are kept: the purchase of Remedies Plus, which Apple holds, and the count of
  free uses of Smart Scan and Register Fill this month, so that a reset does not restore them. Deleting the App also
  removes its data from the device. After either, the encryption key remains in the iOS Keychain,
  where it can decrypt nothing once the data is gone. With iCloud sync on, a reset turns sync off on
  that device and leaves the copy in iCloud, which Settings → Data → *Delete the iCloud copy* deletes
  (Section 4). The Developer holds no copy. Copies in iCloud, in device backups or in
  exported archives remain under the user's control.
- **Rectification.** Any record can be edited in the App. The photographs of deleted
  records are deleted when the App next starts, unless it then holds no records at all; until then
  they are kept so that a deletion can be undone.

Users in the United Kingdom or the European Union also have the right under the GDPR to lodge a
complaint with a data protection supervisory authority, and to request from the Developer access
to, rectification, erasure and restriction of processing of personal data the Developer holds about
them, to object to its processing, and to receive it in a portable format. For the App, these
rights in practice extend only to correspondence the user has sent to the Developer, as the Developer
holds no other personal data from the App. For the Website, they also cover the data described in
Section 12.

## 9. Disclosure to third parties

The Developer does not sell, rent or otherwise disclose user data, as the Developer does not hold
it. The App involves no processor of the Developer's and no advertising or analytics providers. The
processors used by the Website are named in Section 12.

The App uses Apple's services where the user chooses them: iCloud for sync, Apple Health, Siri
(Section 4) and the App Store. Each is provided to the user by Apple under Apple's own terms and
privacy policy, and what the App keeps in iCloud is encrypted so that Apple cannot read it.

Purchases of Remedies Plus are processed by **Apple**. The App confirms a purchase with Apple on the
device. The Developer receives from Apple only the sales reports Apple provides to every developer,
which do not identify the purchaser; the Developer does not receive the purchaser's name, payment
card details or billing address. Apple's processing of that data is governed by Apple's privacy
policy.

## 10. Children

The App is not directed at children. It is intended as a household organiser, and the information
in it is entered by the adult using the App.

## 11. Security

Data held by the App is encrypted at rest, and the copy kept in iCloud while sync is on is
encrypted end-to-end (Section 4); apart from that copy, the App makes no network connections of its
own. The App runs within the iOS app sandbox, which prevents other apps from reading its files. The remaining
risks are those common to any data stored on a phone, in particular use of an unlocked device by
another person and unencrypted computer backups (see Section 4).

## 12. The Website

**Hosting.** The Website consists of static pages served by **Vercel Inc.** (United States). To
deliver a page, Vercel necessarily processes the visitor's IP address and the technical information
a browser sends with each request, such as the page requested, the time of the request and the type
of browser and operating system. Vercel acts as the Developer's processor for this data and retains
it under its own terms. The Developer keeps no logs of its own. Vercel participates in the EU-U.S.
Data Privacy Framework, its UK Extension and the Swiss-U.S. Data Privacy Framework. The legal basis
is the Developer's legitimate interest in delivering the Website and keeping it secure (Article
6(1)(f) GDPR).

**Visitor statistics.** The Website counts page views with **Vercel Web Analytics**. It sets no
cookies. Each page view is recorded with the address of the page, the referring page, the country
and region derived from the IP address, and the type of device, operating system and browser. Page
views are not tied to an IP address or to any identifier that follows a visitor to other websites;
visits are told apart by a hash of the request, which is discarded after 24 hours. The statistics
are sent to the Website's own address, and the Developer sees only aggregated figures. The legal
basis is the Developer's legitimate interest in knowing how many people visit the Website and which
pages they read (Article 6(1)(f) GDPR).

**Mailing list.** A visitor may give an email address in order to be told when the App is released
on the App Store and to receive occasional news about the App after that. Only the email address is
stored, together with the date it was added and whether it is subscribed. It is added to the list
as soon as the form is submitted; no confirmation email is sent. The
list is held by **EmailOctopus** (Three Hearts Digital Ltd, United Kingdom), which processes the
address on the Developer's behalf and stores its data in the European Union on Amazon Web Services;
transfers between the European Union and the United Kingdom are covered by the European
Commission's adequacy decision for the United Kingdom. The legal basis is consent (Article 6(1)(a)
GDPR), given by submitting the form. The address is used for no other purpose: it is not shared,
sold or combined with any other data, and it has no connection with the App. Emails to the list are
sent without open or click tracking.

Consent may be withdrawn at any time through the unsubscribe link in every email, or by writing to
the Developer. After unsubscribing, the address is kept only as unsubscribed, so that no further
email is sent to it; on request it is deleted entirely. Otherwise the address is kept for as long as
the subscription lasts.

**Storage on the visitor's device.** The Website sets no cookies. If a visitor chooses a theme or a
language on the Website, that choice is kept in the browser's session storage for the current tab
only; it is not sent anywhere and is cleared when the tab is closed.

**The video.** The video on the Website is not loaded until the visitor presses Play. Until then the
Website shows its own still image and makes no request to YouTube. Pressing Play loads the video
from YouTube's privacy-enhanced domain, youtube-nocookie.com; from that point Google may process data
and set cookies under Google's own privacy policy.

**Everything else** on the Website (fonts, images and scripts) is served from the Website itself.
Links to other sites, such as Ko-fi and Instagram, load nothing until they are followed.

**Rights.** The rights listed in Section 8 apply to the email address and to any other personal data
the Developer holds through the Website, and may be exercised by writing to the Developer. The
Website and its mailing list are not directed at children.

## 13. Changes to this Privacy Policy

If the App begins to collect any data, or to send data anywhere other than as described above,
this Privacy Policy will be updated **before** that version of the App is released, and the change
will be indicated in the App. If the Website begins to collect data other than that
described in Section 12, or to use another service to process it, this Privacy Policy will be
updated before that change takes effect. The "Last updated" date at the top of this document shows
when it was last amended.

## 14. Contact

**ivandavy@remediesapp.com**
