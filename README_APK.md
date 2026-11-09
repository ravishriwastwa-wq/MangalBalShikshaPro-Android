# APK kaise banayein

## Tareeka 1: GitHub (bina kuch install kiye)
1. github.com par naya repository banayein aur is folder ki saari files upload karein
   (.github folder samet).
2. Repository ke "Actions" tab me "Build APK" khud chalega (ya "Run workflow" dabayein).
3. Run poora hone par neeche "Artifacts" se `MangalBalShikshaPro-apk` download karein,
   zip kholein -> `app-debug.apk` phone me install karein.

## Tareeka 2: Android Studio
Folder ko "Open" karein -> Build > Build APK(s). APK: app/build/outputs/apk/debug/

## Dhyan dein
- App ki HTML file Tailwind, FontAwesome, Google Fonts, confetti CDN se load karti hai,
  isliye pehli baar internet chahiye. Offline chalane ke liye in files ko download karke
  assets folder me rakhna hoga.
- Yeh debug APK hai (install ke liye theek). Play Store ke liye signed release build chahiye.
