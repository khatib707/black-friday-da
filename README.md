# WebEngage campaign assets

Arabic RTL spin-the-wheel campaign for WebEngage. Paste `campaign.html` into WebEngage; images are hosted in this repository and loaded through public GitHub raw URLs.

The wheel, 5% discount panel (`assets/result5.png`), and 15% cashback panel (`assets/result7.png`) were updated from the supplied `NEW DA Black Friday.fig` design: https://www.figma.com/design/JPnM5p3JhZ1YnV8ErubSiM/NEW-DA-Black-Friday. The wheel retains the design's rotation so its segments match the existing prize selection. Updated image references include a cache version.

The subsequent `NOV Black Friday DA.fig` update changes only the loss panel (`assets/result4.png`): it removes the congratulatory heading and moves the illustration up by 22 design pixels. The wheel and other artwork are unchanged from the previous file. The loss-panel image reference includes its own cache version.

Prize probabilities and coupon logic are unchanged. Codes are still hardcoded `TEST-*` placeholders; Google Sheets / Apps Script allocation is not implemented here. The current shopping URL is `https://daralamirat.com.sa/`.

Keep the HTML below 10,000 characters. Publishing changes to GitHub updates the hosted assets, but does not update HTML already pasted into WebEngage or deploy Google Apps Script.
