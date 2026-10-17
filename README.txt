SmartTap Design Studio - how to run
===================================

WHAT IS IN THIS FOLDER
  index.html   the app (open this file)
  qrcode.js    QR code library (MIT license, Kazuhiko Arase). Keep it next to index.html.

1) RUN THE APP ON A COMPUTER (works offline, no install)
  a. Unzip the file (Windows: right-click > Extract All).
  b. Open the folder and double-click index.html. It opens in Chrome, Edge or Firefox.
  c. Keep index.html and qrcode.js in the same folder.

2) USE IT
  a. Standard mode: under "1. Add a shop", type the shop name and paste the shop's
     Google review link, then press "Add shop and create QR".
     The QR code opens that Google review link directly. No redirect or short link is used.
  b. Tap the shop in "2. Your shops" to preview its stand.
  c. Press "Stand PNG" for one stand, or "Print sheet" to put every shop's stand on one page
     (the shop name is printed under each stand, outside the design).
  d. Write the SAME Google review link on the NFC tag, then lock it.
  e. Custom mode lets you change colours, logo, text and themes, and uses the shop name.

  IMPORTANT: because the QR holds the review link itself, make each stand only after you have
  that shop's link. If the link changes later, the printed QR will not change.

  Downloads go to your normal Downloads folder.
  Your shop list is saved inside THIS browser on THIS computer only.
  Press "Download backup (CSV)" now and then. Clearing browser data erases the list.

3) RUN IT ON A PHONE (pick one)
  Option A - free hosting: go to app.netlify.com/drop, drag this whole folder into the page,
    and open the link it gives you on your phone.
  Option B - same Wi-Fi: on the computer, open a terminal in this folder and run
    python3 -m http.server 8000
    then on the phone open http://YOUR-COMPUTER-IP:8000

NOTES
  - The "Review us on Google" image is the picture you supplied. For the best print quality use
    the official artwork from your Google Business Profile marketing kit.
  - Deleting a shop here does not change a stand you already printed.
