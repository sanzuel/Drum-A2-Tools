# Drummer Pro - Gawing APK via GitHub

## Paano mag-build ng APK (libre, walang PC)
1. I-upload lahat ng files na ito sa GitHub repo mo (drum-pro-tools) - i-overwrite mo yung luma
2. Pumunta ka sa repo > tab na Actions
3. Piliin mo 'Build APK' > Run workflow > Run workflow
4. Wait 3-5 minutes hanggang maging green check
5. Pindutin mo yung run > sa baba, sa Artifacts, i-download mo yung `Drummer-Pro-APK`
6. I-extract mo, makikita mo `app-debug.apk` - i-install mo sa OnePlus 15R mo (Allow unknown apps)

## Ano laman?
- www/index.html = buong app
- www/wood.wav = real Wood sound
- www/cowbell.wav = real Cowbell sound
- www/manifest.json + icon
- .github/workflows/build-apk.yml = auto-build ng APK

## Live web version
https://sanzuel.github.io/drum-pro-tools/
