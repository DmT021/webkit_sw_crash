# A WebKit crash reproducer

0. Open https://dmt021.github.io/webkit_sw_crash/ in Safari 26. Running a server on localhost also works just fine.
1. Click "Create Blob URL"
2. Click "Copy URL"
3. Open a new tab and paste the url
4. Scroll down to the youtube widget. This will trigger the crash.

Reproducible on iOS (26.0 RC1) and macOS (Safari Technology Preview Release 227 (WebKit 20623.1.5))

Fixed in https://bugs.webkit.org/show_bug.cgi?id=298697
