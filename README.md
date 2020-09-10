# out.

## Odpalanie poszczególnych repo
### Front-end
Aby uruchomić aplikację należy mieć pobranego [Xcode'a](https://apps.apple.com/us/app/xcode/id497799835?mt=12), bądź innego emulatora
```
npm i
npm run ios
```
W razie problemów można spróbować 
```
npx pod-install ios
```
### Back-end (wszystkie)
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
