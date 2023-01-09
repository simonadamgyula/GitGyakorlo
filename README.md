# Verziókezelés alapjai
## 1. git letöltése
- [git for windows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)
## 2. Kondigurációs parancsok
- git config --global user.name simonadamgyula
- git config --global user.email simon.adam.gyula@students.jedlik.eu
- git config --global credential.helper wincred
## 3. Ropository létrehozása
- git init
## 4. Állomány hozzáadása a stage-hez (staging area)
> A stagen lévő állományokról tudunk allapotfelvételt (commit-ot) készíteni  
> Üres mappa nem kerül a stage-re
- git add "állomány_neve"
- git add . (az összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
- git commit -m "commit message"
## 6. Git állapot és log lekérdezése
- git status
- git log