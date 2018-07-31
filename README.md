# BitShares Graphene Wallet

 
BitShares itself is not a company, it’s a Decentralized Autonomous Community (DAC) of friendly FinTech people of all ages wanting freemarket solutions to secure life, liberty and property for all. BitShares software uses the Delegated Proof Of Stake (DPOS) consensus protocol which cannot be blocked, taken down or centralized by asic or quantum computing hardware. 
 
Send any amount.. anywhere.. for just a few cents.. and in only 3 seconds!
 
* Works with all Smartcoin enabled Point Of Sale (POS) systems at merchants worldwide 
* Absolute Security; BitShares blockchain based, End-to-End Encryption, BrainKey, multi-signature account permissions, auto-encrypted Backups, auto-close, auto-timeout and PIN verifications
* No Bluetooth, NFC, merchant wireless service or special hardware is required 
* Use QR Codes to Send locally (uses your phone’s camera to scan their QR Code)
* Use QR Codes to Receive locally (displays your QR Code so your friend can scan it) 
* Receive eReceipts automatically via merchant QR codes
* 10,000+ transactions per second (TPS) which is more than Visa and Mastercard combined! 
* Send and Receive Smartcoins (bitUSD, bitEUR, bitCNY, bitBTC, bitSILVER, etc)
* Send and Receive User Issued Assets (UIAs) - (OPENPOS, OBITS, OPENBTC, COFFEE, etc) 
* Supports a large Memo field with sending payments (for personal notes or notes to the recipient)
* Share the BitShares Wallet app with friends and get reward$
* Choose friendly account names; No more long cryptic addresses or numbers
* Totally Open-Source Software (OSS) and verifiable on Github
* Contacts can be organized by BitShares account address or nickname label. Notes and Avatars are supported too!
* Quickly and Easily share your payment address via email, chat, wireless, social media and telephone
* Monitor all Balances and Transactions in real-time; UI/UX never needs a refresh
* Now in 22 languages! 

## Roadmap 
 
* Implement Overdraft Protection, Rewards Card features, Filter and export Transactions to multiple file formats for accounting, etc. (v1.1)
* Recurring and Scheduled Payments feature for auto-paying bills, subscriptions, etc (v1.2)
* “Finder” - Google Maps integration; Find local Smartcoin friends, merchants, jobs and BitShares Meetups (v2)
* Stealth Transactions (blinded addresses AND amounts for the ultimate in privacy!) (v2)
* Rollout of next POS module (instantly connects >50K supermarkets, restaurants and retail shops!) (v2.1)
* “Exchange” - Buy and Sell Smartcoins/UIAs/Bitcoins/Altcoins on the internal Exchange (DEx) directly (v3)
* Android Wear and Apple Watch support (v4)

## Building
### Prerequisites
1. Go to project root directory 
2. `cd dev`
3. `unpack node_modules_bsw.zip`, so that node_modules directory appears in `dev` directory 
4. `cd app/dl/`
5. `npm install`
6. `cd ../../..` 
7. `npm install cordova -g`
8. Install Android SDK
9. `cordova platform add android`

### Web build
1. Go to project root directory 
2. `cd dev`
3. `npm run build`
4. `set port = 5000` (optional) 
5. `http-server` 
6. Remove cookies, localstorage and web databases for localhost to clear applicaton settings (optional) 
7. Open [localhost:5000](http://localhost:5000)

### Android build
1. Go to project root directory
2. `cd dev`
3. `npm run buildprod`
4. `cd ..`
5. If any changes of external resources (css, images etc) occured since last build, manually copy these folders from `dev\app\assets\` to `www\assets`
6. Copy `index_android.html` to `index.html` (overwriting old `index.html`).
7. `cordova build android --debug`
8. Resulting .apk file is in `platforms\android\build\outputs\apk`

### iOS build

#### Platform installation:

1. Copy the whole project folder (except platforms/ folder) to your Mac
2. Install XCode 7.x 
3. Open terminal window for root project folder
4. `cordova platform add ios`
5. Copy `index_ios.html` to `index.html` (overwriting old `index.html`).
6. Copy `Intl.js` to `www/assets/` (next to `socialSharing.js`)


#### Test build

1. On a Windows machine, run `npm run build` against dev/ folder.
2. Copy www\assets to the relevat folder on your Mac.
3. Open OS X terminal for root project folder
4. `cordova build ios --debug`
5. Select `platforms\bitshareswallet.xcodeproj`. Project should open in XCode
6. Select 'Generic device' and 'Debug\Archive'
7. Create ad-hoc build 
8. Install the .ipa file to your iOS device

## Pleeeeease Donate 

Please consider donating to the BitShares Wallet project so the Developers can afford to keep this wallet secure, bug free, ad free and constantly improving. (BTS account: bitshares-munich) 

Thank you! :) 

## BitShares Munich 

* http://BitShares-Munich.de 
* http://vk.com/BitSharesMunich 
* http://meetup.com/BitShares-Munich (meet us in person!)
* http://facebook.com/BitSharesMunich 
* http://pinterest.com/BitSharesMunich 
* http://youtube.com/BitSharesMunich-de (explanation videos too!)
* http://google.com/+BitSharesMunich-de 
* http://xing.com/companies/BitSharesMunich 
* http://linkedin.com/company/BitShares-Munich 
 
## FAQ, Technical Support, Bug Reports and Features requests 
 
http://bitsharestalk.org 
