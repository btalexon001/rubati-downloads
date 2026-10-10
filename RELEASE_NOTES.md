# Rubati 1.0.0 beta 1 — Android build 4

**BETA — unpublished draft. Not approved for public download.**

Prepared release tag: `v1.0.0-beta.1`. The signed Android APK identifies
itself as Rubati **1.0.0 (4)**, package `ke.co.renta.app`.

## Download identity

- APK: `rubati-v1.0.0-beta.1.apk`.
- Size: 66,886,156 bytes (63.79 MiB).
- SHA-256: `5a575f7533793d9e9e6300fb0a81eaed55c2653070aca8f6e70c6b88b1563a23`.
- Android 7.0 or later.
- Release signing certificate SHA-256:
  `e045c45012e7fafdb71099a40c9bd40eaf6bb79da3640da91589334c13cb6ba3`.

This preparation uses the existing Samsung-tested APK without rebuilding or
re-signing it. Build 4 corrects the account-deletion disclosure: the 180-day
message retention rule is distinguished from automatic scheduled cleanup,
which is not currently active.

## Acceptance evidence and limitations

Recorded Samsung checks covered launch/navigation, existing-account login and
authentication persistence, guest discovery/search empty states, the
verification disclosure and incomplete-form safeguard, advertising preview,
and the corrected account-deletion disclosure with Cancel. Notification
registration was checked; this does not establish push delivery. No immediate
crash or ANR was observed in the bounded startup checks.

The following complete workflows remain **NOT TESTED end to end**:

- Landlord verification submission and its persisted disclosure evidence.
- Payment confirmation and listing publication; no real test payment was made.
- Two-way tenant/landlord messaging and private attachment access.
- Reporting, blocking and unblocking between accounts.
- Firebase push delivery.
- Irreversible disposable-account deletion and recovery.
- Public listing details with eligible inventory.

Opening a screen or passing local regression tests does not establish a full
production workflow PASS. Required acceptance limitations must be resolved or
explicitly considered by the owner before public distribution. This draft is
not a certification of complete launch readiness.

## Privacy, deletion and support

- [Privacy Policy](https://btalexon001.github.io/rubati-downloads/privacy-policy.html)
- [Account Deletion](https://btalexon001.github.io/rubati-downloads/account-deletion.html)

Automatic identity-image, message and moderation cleanup, and abandonment
notices, remain disabled. No automatic retention-deletion schedules are active.
The published pages explain retention rules and the monitored request route.

The app is free to download. Existing advertising and verification fees still
apply to the relevant services. Do not make payments solely to test this beta
without the owner's explicit approval.

Installation: [INSTALL.md](https://github.com/btalexon001/rubati-downloads/blob/main/INSTALL.md).
Support/privacy: [rubatiapp.ke@gmail.com](mailto:rubatiapp.ke@gmail.com).

APK publication requires separate explicit owner approval. No public APK,
Google Play upload or automatic cleanup activation is part of this preparation.
