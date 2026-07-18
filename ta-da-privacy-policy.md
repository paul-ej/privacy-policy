# Privacy Policy — ta-da

**Last updated: 18 July 2026**

Ta-da is a task-management and note-taking app for iOS. This policy explains what data the app collects, where it is stored, and how it is used. There are no hidden data practices — everything the app knows about you stays on your device or in your personal iCloud account, **except the specific items you choose to share with family members you invite** (see section 5, Family sharing).

---

## 1. Who we are

Ta-da is developed and published by Paul Edmondson-Jones. If you have questions about this policy you can reach us at paulrobinjones@gmail.com.

---

## 2. Data the app stores

### 2.1 Task and project data
Ta-da stores tasks, projects, subtasks, notes, due dates, priorities, tags, estimated durations, recurrence rules, and completion history that you create inside the app. This data belongs to you and is never sent to our servers (we don't have any).

### 2.2 Focus session data
When you run a focus session the app records the start and end time, duration, associated task, Pomodoro count, and your chosen music provider. This is used to show you summaries and trends inside the app.

### 2.3 Streaks and habit data
The app tracks your current and longest streak, last active date, a rolling 7-day history, and grace-day usage to power the streak feature.

### 2.4 Apple account information (optional)
If you choose to sign in with Sign In with Apple, the app stores your Apple-provided user ID, display name, and email address in the iOS Keychain on your device. Sign-in is optional — you can use ta-da without an account.

### 2.5 Subscription status
Whether you hold a Ta-Da! Together subscription is recorded in local device storage so the app can unlock Together features without a network call. No payment details are ever seen or stored by the app; all purchases are handled by the App Store.

### 2.6 App preferences
Theme selection, notification settings, and feature toggles are stored locally on your device.

### 2.7 Notes and attachments
Ta-da's notes feature stores the note text, handwriting/drawing, embedded photos, file attachments, links, folders, and tags you create. Photos, drawings, and file attachments are held in the app's local storage and, if iCloud is enabled, sync as CloudKit assets in your private database. Ta-da enforces a size limit on file attachments to keep sync efficient.

---

## 3. Data the app reads but does not store

### 3.1 Apple Health (optional)
If you grant permission, ta-da reads workout activity, active energy burns, and sleep data from Apple Health. This data is used only to decide whether to award a grace day on days you were physically active or recovering — it is never written back to Health, never stored by the app beyond the current session, and never transmitted anywhere.

You can revoke this permission at any time in **Settings → Privacy & Security → Health → ta-da**.

### 3.2 Apple Reminders and Calendar (optional)
If you grant access, ta-da can import tasks from Apple Reminders and events from Apple Calendar. The app reads this data on demand; it is not stored independently and is not shared.

---

## 4. iCloud sync

If you are signed in to iCloud on your device, ta-da stores your task and note data in a private CloudKit container (`iCloud.com.paul-ej.ta-da`). This container is accessible only to you — we cannot read your CloudKit data. Apple's iCloud terms of service govern how Apple stores and protects this data.

You can disable iCloud sync in **Settings → [your name] → iCloud → ta-da**.

---

## 5. Family sharing — Ta-Da! Together (optional)

Ta-Da! Together, part of the subscription, lets you share tasks with family members. It is **off by default** and only ever shares the specific items you choose. It is the one feature where data leaves your private space and becomes visible to other people — the people you invite.

**What is shared.** When you assign or share a task, that task's content (its title, notes, and location) is mirrored into a shared household area in your private iCloud account using Apple's CloudKit sharing (`CKShare`). Invited members who accept see those shared tasks in their own copy of the app. If you use the "cheer" and shared-rhythm features, a cheer message and a presence signal (your display name and which recent days you were active) are shared with household members too.

**Inviting members.** Invitations are sent as a standard iCloud share link through Apple's system share sheet (for example via Messages or Mail). We do not run any invitation server.

**Choosing who to assign.** When you assign a task to someone, ta-da uses Apple's system contact picker. This picker runs outside the app, so **ta-da does not request access to your Contacts** and cannot browse your address book. Only the single contact you pick is returned to the app — their name, one email or phone handle, and their contact photo (used to show an avatar). This is stored with the task so the assignment can sync.

**What others can see.** Members you invite can see the tasks you share into the household and the cheer/rhythm signals described above. They cannot see your other tasks, notes, focus sessions, or any data you have not shared. You can stop sharing or leave a shared household, which removes the shared copy from your device.

---

## 6. Link previews

When you add a link to a note, ta-da uses Apple's Link Presentation framework to fetch a rich preview (title and icon). This contacts **only the URL you entered**, directly from your device. No other browsing data is collected, and the preview request is not routed through us.

---

## 7. Widgets and Siri

Ta-da shares a summary of your streak count, completed tasks, open tasks, and next task with its home screen widget via an iOS app group. This data never leaves your device.

If you use Siri Shortcuts to create tasks by voice, your spoken input is processed by Apple's on-device speech recognition. Ta-da only receives the resulting text; it does not record or retain audio.

---

## 8. Apple Music (optional)

If you choose to play Apple Music during a focus session, ta-da requests playback permission. The app does not access your library metadata, listening history, or account details — it only starts and stops playback.

---

## 9. Analytics and advertising

Ta-da contains **no analytics SDKs, no advertising SDKs, and no crash-reporting services**. No usage data, device identifiers, or behavioural signals are collected or sent anywhere.

---

## 10. Third parties

Ta-da does not sell your data or share it with any third-party advertisers or data brokers. The only external services involved are:

- **Apple's own platforms** — iCloud and CloudKit (including CloudKit sharing for Ta-Da! Together), the App Store, Apple Health, Apple Music, Siri, and the system share sheet used to send invitations. Your interactions with these are governed by Apple's privacy policy.
- **Family members you invite** — who receive the specific shared items described in section 5.
- **A website you link to** — which receives a request only when you add its URL to a note (section 6).

---

## 11. Data retention and deletion

All data is stored on your device and, if enabled, in your personal iCloud account. To delete everything:

1. Delete the app from your device — this removes local data and Keychain entries.
2. To remove iCloud data, go to **Settings → [your name] → iCloud → Manage Account Storage**, find ta-da, and delete its data.
3. To stop sharing with family, remove assignments or leave the shared household inside the app; this removes the shared copies on your device. Content already delivered to a member's device remains under their control.

We have no copy of your data and cannot delete it on your behalf.

---

## 12. Children

Ta-da is not directed at children under 13 and we do not knowingly collect data from children. Because no data leaves the device or personal iCloud account without your explicit action, the app's data practices are the same regardless of age.

---

## 13. Changes to this policy

If we make material changes to this policy we will update the "Last updated" date at the top and, where possible, notify you through the app. Continued use of ta-da after a change constitutes acceptance of the updated policy.

---

## 14. Contact

Questions or requests: **paulrobinjones@gmail.com**
