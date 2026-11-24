# AM_Inventory_PWA - https://hwaymanANL.github.io/AM_Inventory_PWA/

Static PWA for APS Inventory Stock page. Hosted on GitHub Pages (Microsoft) for PWABuilder packaging.

**No inventory data here** - app fetches live from https://argonnedoe.sharepoint.com/sites/APSDesigners/_api/web/lists/getbytitle('AM_LAB_INVENTORY') at runtime on tablet via authenticated WebView.

## Deploy
1. Push this folder to GitHub repo `hwaymanANL/AM_Inventory_PWA` (main branch, root)
2. GitHub > Settings > Pages > Source: Deploy from branch > main / (root) > Save
3. Wait 1-2 min, verify https://hwaymanANL.github.io/AM_Inventory_PWA/ shows APS Stock
4. Enter that URL at https://www.pwabuilder.com > Package for Android > Download APK

## Long term
Move same files to ANL GitLab Pages when account ready - same process, just `Settings > Pages` in GitLab.

Local source: `C:\Users\hwayman\PycharmProjects\APS_Inventory\optionB\src\`
