CX POCKET CALCULATOR - OFFLINE INSTALL ON IPHONE

The app is index.html plus these support files. To run offline it must be
served once from an https web address; after that it works with no signal.

Option A - Netlify Drop (easiest, about 2 minutes, free)
 1. On a computer go to https://app.netlify.com/drop
 2. Drag this whole cx-calc folder onto the page. You get an https link.
    (Sign up free if you want the link to stay permanently.)
 3. Go to step 4 below.

Option B - GitHub Pages (free, permanent)
 1. Create a new public repository and upload every file in this folder.
 2. Settings > Pages > Deploy from branch > main / root > Save.
 3. After a minute your link is https://<username>.github.io/<repo>/

Then on the iPhone
 4. Open the link in Safari (must be Safari).
 5. Tap Share > Add to Home Screen > Add.
 6. Open it once from the home screen while you have signal. It is now
    cached and works offline.

Updating later
 - Upload the new index.html and sw.js together (sw.js carries the cache version),
   then open the app once with signal.

Your data
 - Saved instruments are stored on the phone, inside the home-screen app.
   Use Instruments > Copy backup now and then and paste it somewhere safe.
   iOS can clear website data if the app goes unused for many weeks.
