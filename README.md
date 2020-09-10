<p align="center">
    <img src="ios/Hackathon/Images.xcassets/out-logo.imageset/splashscreen_1024.png" height="128"/>
</p>

---

# Odpalanie poszczególnych repo

## Front-end


### ⚠ Aplikacja narazie kompiluje się tylko na Mac'ach z [Xcode'em](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
API URI jest w pliku [src/constants/Api.ts](src/constants/Api.ts)
```bash
npm i
npx pod-install ios
open ios/Hackathon.xcworkspace
```

Po otwarciu projektu, skompilować na symulatorze lub na prawdziwym urządzeniu.


## Back-end (wszystkie)
Wymagana jest wersja 3.* [Python'a](https://pl.python.org/)  
Instalacja wymaganych zależności, zależnie od systemu operacyjnego  
Windows:  
```
.\dev-scripts\windows\requirements.ps1  
```
Linux:  
```
./dev-scripts/linux/requirements.sh  
```
Uruchomienie serwera  
```
py api.py  
```
lub
```
python3 api.py
```


# Przyszłość aplikacji
W przyszłości mamy zamiar rozbudować go o parę fajnych funkcji:
  - aplikacja dla użytkowników
    - zgłaszanie ewakuacji przez użytkownika
    - mapa z drogą ewakuacji
    - powiadomienia o ewakuacji
  - wsparcie dla gości
  - interaktywna mapa podczas ewakuacji w panelu administratora

