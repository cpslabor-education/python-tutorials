# Python tutorial (magyarul) - SZE robotlabor
Ez a tárhely a Python leírásokat tartalmazza, ami oktatásban összefoglalóként, vagy rövid isméltőként alkalmazhatóak. Az anyag folyamatosan bővül ahogy a laborhoz köthető tananyagok is.

# Tartalom
A tárhelyen a következő anyagok találhatók:
- [Bevezető, alapok, vezérlési struktúrák](01_Alapok.ipynb)

# Hogyan futtasd

Tölts le a repository-t a zöld _Code_ feliratú gombbal vagy ha van git kliensed akkor:
```
git clone https://github.com/robotlabor-education/python-tutorials.git
```

Ezután menj bele a könyvtárba és nyiss egy terminált. Windowson `Shift+jobb klikk`, utána _Poweshell megnyitása itt_. Ezután írd be a következőt:
```
jupyter notebook
```
Ez meg fogja nyitni az egész mappát, utána ki tudod választani melyik notebook-ot szeretnéd elindítani. Ha egy kiválasztottat szeretnél elindítani akkor a parancshoz add meg argumentumként:
```
jupyter notebook 01_Alapok.ipynb
```

Érdemes csak pár betűt beírni utána a ```Tab``` segítségével kiegészíteni a fájl nevét. Ha a Python hibát dob akkor futtasd le a következő parancsot:
```
pip install jupyter
```