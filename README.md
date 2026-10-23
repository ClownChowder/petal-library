# Petal Library

Offline companion for explicit reading/listening position handoffs between [Petal Reader](https://github.com/ClownChowder/books-story-series) and [Petal Voice](https://github.com/ClownChowder/petal-voice).

Current personal preview: [0.1.1](https://github.com/ClownChowder/petal-library/releases/tag/v0.1.1), version code 2. Choose matching editions, review the approximate whole-book position, confirm a move, and Undo if the destination has not changed. Connection requires explicit consent; Disconnect clears Library’s remembered pair and Undo record. Signature and package checks protect both directions of app communication. Controls disable while a move is in flight.

Library requests no Internet or storage permission, disables Android backup, and copies no ebook/audio content. It stores only the selected pair and one Undo record privately. Reader and Voice retain their own pre-existing features and permissions.

Download petal-library.apk from [Releases](https://github.com/ClownChowder/petal-library/releases/latest). Full corresponding source is attached as petal-library-source.zip. This is a release-index repository: GitHub’s automatic tag archives do not contain the app source. CHECKS.txt, verification.json, source-manifest.json, credits and SHA256SUMS accompany every verified preview.

Tested with Reader 1.8.0-petal.7 and Voice 26.10.3-petal.6: 182 fresh host tests across those apps, synthetic two-pair handoff/Undo, correct-book opening, consent cancellation/reconnect, rotation recovery and unauthorized callers/replacement companions on disposable emulators. Library lint retains 14 warnings. Physical performance/battery and live assistive technology remain unqualified. Position alignment is approximate, not sentence-level.

Android package app.petallibrary; minimum Android 8/API26. Personal debug signer SHA-256: 386f097ea7de3749f0b0cc87e433d0f8a8a70cebb1848d7e7cb4bd5f60cff2b4. Keep the same signer for updates. Obtainium repository: https://github.com/ClownChowder/petal-library ; exact APK filter: `^petal-library\.apk$`.

Credentials, personal books/audio, databases and raw private logs are excluded from publication. Upstream Reader/Voice credits and licenses remain in their own source archives.
