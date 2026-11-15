COFFEE VILLAGE - CLEAN GITHUB PAGES PACKAGE

UPLOAD:
1. Extract this ZIP.
2. Open the extracted CoffeeVillage_Fresh folder.
3. Upload the CONTENTS of this folder to the ROOT of your GitHub repository Market2026.
   IMPORTANT: index.html must appear beside README_ASSETS.txt at the repository top level.
4. Keep GitHub Pages Settings -> Deploy from a branch -> main -> /(root).

FOLDER:
index.html
README_ASSETS.txt
assets/photos/ (put photo1.jpg ... photo6.jpg here)
assets/music/  (put song1.mp3 ... song3.mp3 here)

3D troubleshooting:
- This version imports Three.js modules from jsDelivr CDN, so the visitor's browser must have internet access to cdn.jsdelivr.net.
- If the 3D scene cannot start, a visible error message is displayed.
- Use current Chrome or Edge and refresh with Ctrl+F5.
- Use https://yourname.github.io/Market2026/ to test after publishing.

CUSTOM LINKS:
Find vanData in index.html and replace each https://example.com with the real shop destination.
HOME cottage can be linked by adding your own URL to its click handler if needed.


git add .
git commit -m "Update Coffee Village 3D website"
git push origin main