# Shotlist

**Every screenshot has a job. Shotlist does it, then clears the screenshot away.**

Shotlist is a mobile app concept built for Wire Wars'26 (IIM Calcutta). It reads every screenshot on the phone, works out why you took it, does the task for you, and archives the screenshot once that task is done.

## What it does
- **Capture → Act:** recognises a screenshot within a second and offers a one-tap action. For example, a train ticket becomes a calendar entry, a bill becomes a reminder, and an OTP is copied to the clipboard.
- **Lifespan:** each screenshot expires when its job is done. OTPs go after 10 minutes, tickets once the trip ends, and bills once they're paid.
- **Sunday Sweep:** a weekly clean-up that groups old screenshots by reason (used codes, finished trips, near-duplicates, blurry shots). Anything swept can be restored for 30 days.
- **Autonomy controls:** set each category to Ask, Suggest or Auto. Shotlist only acts on its own when it is at least 85% confident. A sensitive-content guard stops it acting automatically on bank, ID or password screenshots.
- **Privacy-first:** it only reads the Screenshots folder, and all processing happens on the phone.

## Live prototype
Open `index.html` in a browser. It is a fully clickable, single-file prototype.

The **Model Lab** tab runs real open-source models in the browser:
- [Tesseract.js](https://github.com/naptha/tesseract.js) for OCR
- [chrono-node](https://github.com/wanasit/chrono) for date parsing
- A keyword-based intent scorer with a confidence gate

The production design plans to use Google ML Kit text recognition, MobileCLIP image tagging and libphonenumber, all running on the phone.

All sample data in the prototype is fictional.

## Team Shotlist
| | Role |
|---|---|
| **Mahak Fahad** | Team leader, backend and AI/ML |
| **Roshini R** | Frontend and design (UI/UX) |

B.E. Computer Science and Engineering, Chennai Institute of Technology, batch of 2029.
