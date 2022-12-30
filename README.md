# RevertFFToolbar
A userChrome.css script to revert the changes to the toolbar in Firefox 110.

## What did Mozilla do this time?
The toolbar received an update on December 22nd which made it look, in my opinion, much worse:
- The dark system theme was made brighter and now does not fit with the dark theme of any OS.
- The text on the selected tab was made bold.

To communicate the difference more clearly, here's a before and after:
![Screenshot_20221230_031835](https://user-images.githubusercontent.com/42720004/210065644-40b02534-01c2-4f1f-97cc-62fae8170f2d.png)
![Screenshot_20221230_032012](https://user-images.githubusercontent.com/42720004/210065654-2d9d7bf4-74a2-4d2b-b43d-d7c7c9fa6b55.png)
(I'm using WaveFox, but it looks the same on the normal one too)

## How do I use this?
- In ``about:config``, set ``toolkit.legacyUserProfileCustomizations.stylesheets`` to ``true`` if you have not already.
- Go to your Firefox profile folder. For convenience, use ``about:profiles``.
- Create a folder named ``chrome`` if it's not there already.
- Drop the ``userChrome.css`` file right in.
- Restart Firefox.
