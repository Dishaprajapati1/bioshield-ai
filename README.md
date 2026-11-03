# BioShield AI

[Open the public demo](https://dishaprajapati1.github.io/bioshield-ai/)

The Pages site is a read-only static preview. Its metrics and records are synthetic; it does not connect to the Flask backend or collect face data.

## Local dashboard

[Open the local dashboard](http://127.0.0.1:5000/dashboard)

This address works only on your computer while the Flask server is running. It is not a public link; other readers will open their own local machine.

## Source snapshot

Download [`BioShield-AI-source.zip`](BioShield-AI-source.zip) for the Flask prototype source. The archive intentionally excludes the local SQLite database and uploaded profile or audit images. Demo seed records use fictional placeholder data.

## Security

This is an educational prototype, not an internet-ready biometric service. The Flask dashboard and user, task, and log management APIs do not have authentication. Do not deploy the Flask app publicly or use real biometric or personal data until appropriate access control, storage, retention, and production security are implemented and reviewed.
