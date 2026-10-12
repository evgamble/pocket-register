# Pocket Register

The phone companion for the Account Register desktop app: check balances and bills due, and add transactions on the go.

**Open it on your Android phone:** https://evgamble.github.io/pocket-register/ — then use Chrome's menu → *Install app* (or *Add to Home screen*).

## Privacy
This repository holds only the app's code. No financial data is ever stored here or sent anywhere.
- The app opens your own encrypted `register-data.json` from OneDrive using the phone's file picker, and unlocks it with your usual username and passphrase.
- Entries you add are kept encrypted on the phone, then sent as an encrypted `register-inbox-….json` file that you save to your OneDrive Account Register folder. The desktop register imports it the next time you log in.
