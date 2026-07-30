# Privacy Policy — Loci

**Last updated: 18 July 2026**

Loci is a privacy-first, Apple-native notes and "second brain" app for iPhone, iPad, Mac, and Apple Watch. This policy explains what data the app stores, where it is stored, and how it is processed. The guiding principle is simple: **your notes stay on your device, and in your personal iCloud account, unless you explicitly choose otherwise.** Loci does not operate a note-storage or user-account server.

---

## 1. Who we are

Loci is developed and published by Paul Edmondson-Jones. If you have questions about this policy you can reach us at paulrobinjones@gmail.com.

---

## 2. On-device by default

Every core feature of Loci works with zero network access. Editing, import parsing, OCR, on-device transcription, search, and indexing all run locally on your device. On-device is the default path, not a premium fallback. Nothing about your note content is sent anywhere unless a specific, clearly surfaced feature requires it and you have opted in.

---

## 3. Data the app stores

### 3.1 Your notes and content
Loci stores the notes, pages, blocks, folders, collections, tasks, templates, meetings, and attachments you create inside the app in its local SwiftData store. This content belongs to you. It is never sent to our servers — we do not operate any.

### 3.2 Derived AI data (local-only)
To power on-device intelligence, Loci generates derived data such as AI digests and text embeddings. This data is kept in a **separate, local-only store that never syncs and never leaves the device.** It is regenerable, is never treated as the source of truth, and can be rebuilt from your notes at any time.

### 3.3 App preferences
Theme selection, feature toggles, your chosen intelligence mode, and similar settings are stored locally on your device.

---

## 4. AI features and where they run

Loci uses a tiered inference system, ordered most-private first. The default intelligence mode is **on-device only**, and the app never crosses the "leaves device" line without a matching permission you have granted.

- **On-device (default).** Baseline AI — capture, linking, search, summarising, ask-your-notes, OCR, scanning, and transcription — runs entirely on your device. No badge is shown, because nothing left the device.
- **Apple Private Cloud Compute (optional, Loci+).** For heavier requests you may opt in to Apple's Private Cloud Compute. When a request is processed this way, the app shows a **blue** tier badge so you know data left the device. This is opt-in and surfaced, never silent.
- **Third-party models (optional, Loci+).** You may connect third-party model providers. When a request is processed by a third party, the app shows an **amber** tier badge. This is opt-in and surfaced. Any data sent is governed by that provider's own privacy policy.
- **Bring-your-own local models (Loci+).** You can load your own local models, which run on your device.

Tier badges always reflect the tier that *actually* processed the request, never the one requested.

---

## 5. iCloud sync and encryption

If you enable iCloud, Apple CloudKit synchronizes your notes through **your private CloudKit database** in the container `iCloud.com.paul-ej.loci`. This database is accessible only to you — we cannot read it.

Loci marks your content fields (such as note titles, page and block text, folder and collection names, template contents, attachment filenames, and meeting titles) for on-device CloudKit encryption, so those values are encrypted before upload. Attachment bytes, transcripts, and meeting artefacts are stored as encrypted CloudKit assets.

Some sync metadata — record identifiers, relationships, ordering, and timestamps — remains readable by CloudKit because it is needed to synchronize your data across devices.

**End-to-end encryption depends on your Apple Account settings.** When you enable Apple's Advanced Data Protection for iCloud, your encrypted fields and assets become end-to-end encrypted, with keys available only to you. Loci does not claim that ordinary iCloud sync is automatically end-to-end encrypted.

You can manage or disable iCloud sync using Apple's system iCloud controls.

---

## 6. Optional non-Apple storage backends

Loci can optionally sync to a non-Apple destination — such as an iCloud Drive, Dropbox, Google Drive, OneDrive, or local folder ("vault"). When you use one of these, **client-side encryption is on by default**: your data is encrypted on-device with keys held in your device Keychain (or an optional passphrase), and the provider sees only ciphertext. Encryption keys never sync to the provider.

---

## 7. Web capture

If you capture a web page, Loci contacts **only the URL you explicitly submit**. No other browsing data is collected or sent.

---

## 8. GitHub integration (optional)

If you connect GitHub, Loci talks to GitHub directly after you complete a read-only GitHub App authorization. GitHub credentials are stored in your device Keychain. Any repository source index Loci builds is a bounded, locally-derived cache that is excluded from backup. Disconnecting GitHub removes its credential and its repository cache.

---

## 9. Agent and third-party LLM connections (optional, Loci+)

Loci can expose a local read endpoint that lets an external tool or model query your notes. This is **off by default.** When enabled, each connection is bound to the local loopback interface, individually scoped, authenticated with a bearer token, and revocable at any time. Connection activity is audited locally **without recording note content**, and credentials are stored in your device Keychain. Revoking a connection invalidates its credential.

---

## 10. Widgets, Apple Watch, and Share Extension

Loci's home-screen widgets, watch app, watch complications, and share extension read from a shared on-device app group (`group.com.paul-ej.loci`). Data shared this way stays on your device. The share extension queues incoming content into the app group for the main app to process.

---

## 11. Subscriptions

Loci is free to use, including all baseline on-device AI. **Loci+** is an optional auto-renewable subscription that unlocks additional capabilities (Apple Private Cloud Compute, bring-your-own local models, vault-scale AI, automations, and the third-party connection endpoint). All purchases are handled by the App Store through StoreKit. Loci never sees or stores your payment details.

---

## 12. Analytics and advertising

Loci contains **no advertising SDK, no cross-app tracking, no third-party analytics, and no crash-reporting service.** No usage data, device identifiers, or behavioural signals are collected or sent to us or to any third party.

---

## 13. Third parties

Loci does not share your data with any third parties of its own accord. The only external services involved are Apple's own platforms (iCloud, the App Store, Apple Private Cloud Compute) and any service **you** explicitly connect — a non-Apple storage provider, GitHub, or a third-party model provider. Your use of those services is governed by their respective privacy policies.

---

## 14. Data retention, export, and deletion

Your notes remain until you permanently remove them from the Recycle Bin. You can export your data as Markdown, PDF, and attachment packages at any time. iCloud data can also be managed with Apple's system iCloud controls. Uninstalling the app removes the device-local containers through the platform's normal processes.

We have no copy of your notes and cannot delete them on your behalf.

---

## 15. Children

Loci is not directed at children under 13 and we do not knowingly collect data from children. Because your data stays on your device and in your personal iCloud account, the app's data practices are the same regardless of age.

---

## 16. Changes to this policy

If we make material changes to this policy we will update the "Last updated" date at the top and, where possible, notify you through the app. Continued use of Loci after a change constitutes acceptance of the updated policy.

---

## 17. Contact

Questions or requests: **paulrobinjones@gmail.com**
