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
## 7. Lokális változtatások szinkronizálása a távoli repóba
- git push
## 8. Távoli repó másolása (klónozása) a lokális repóba
- git clone "Távoli repó URL címe"
## 9. Ágak (branches) kezeláse
> Lokális ágak listázása
- git branch
> Lokális és távoli ágak listázása
- git branch -av
> Ág létrehozása (-b és váltása)
- git branch új_ág_neve
- git checkout -b új_ág_neve
> Váltás egy másik ágra
- git checkout másol_ág_neve
> Ág törlése (aktuális ág nem törölhető)
- git branch -d törlendő_ág_neve