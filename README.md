# PPE Monitoring - licence service

This repository publishes one file: `ppe-licence.json`.

Installed copies of PPE Monitoring read it to learn whether they are still enabled. It is signed with the owner's Ed25519 key, which is not in this repository and never leaves the owner's machine; each installation verifies the signature against a public key compiled into the software, so this file cannot be forged or edited usefully.

It contains installation ids (random, meaningless on their own), whether each is enabled, and an optional note shown on that site's dashboard. No client names, no site data, no personal data, no secrets.

Tret Software Engineering Services

