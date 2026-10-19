# CardRewards public data feed

This repository publishes public, source-linked Indian card terms and merchant offers for the CardRewards Android app. It contains no wallet, transaction, SMS, or personal data.

The app fetches [`feed.json`](feed.json) over HTTPS once per day when opened. Each offer has a short expiry and disappears from recommendations after that date. A published feed does not discover new terms by itself: updates need research and validation before publication.

Source project validator: `python tools/validate_update_feed.py`.
