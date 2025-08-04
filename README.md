# Használati útmutató  

## Rövid leírás
Ez a játék Tóth Benedek Vitéz szakdolgozata. A játék egy egyszerű 3D-s belső nézetű (FPS) lövöldözős játék. A játék célja, hogy megöld az összes piros fickót.

## Fontos infók  
**A program csak Windows operációs rendszeren működik.**   

Cikkek arról, hogy a Windows és a böngésző miért érzékeli vírusnak a programot:  
- [Microsoft cikk](https://support.microsoft.com/hu-hu/windows/vírus-és-veszélyforrás-kezelés-a-windows-biztonságban-1362f4cd-d71a-b52a-0b66-c2820032b65e)  
- [Stack Overflow cikk](https://stackoverflow.com/questions/48946680/how-to-avoid-the-windows-defender-smartscreen-prevented-an-unrecognized-app-fro)

## Letöltés  
A fájl letöltésére két lehetőség van. Az első az egy egyszrű letöltés tömörített mappa formájában. A második git használatával történik.

**Egyszerü letöltés:**  
Ezt Chrome böngészőben fogom végig mutatni. Lehet, hogy más böngészőkben ez nem pontosan így néz ki.  
![Letöltés gomb](/docs/Download.png)  
Előfordulhat, hogy a böngésző letiltja a letöltést, mert veszélyesnek érzékeli:  
![Böngésző letíltja a letőltést](/docs/DownloadError2.png)  
Ekkor nyomjunk a kis nyílra, amely felhozza az alábbi menüt:  
![Letöltés engedélyezése](/docs/DownloadError3.png)  
Ezután lehet hogy maga a Windows fogja letiltani a program letöltését:  
![Windows letíltja a letöltést](/docs/DownloadError4.png)  
Kattints erre a felugró ablakra, amely megnyitja a Windows beállításait. Innen minket ez a rész érdekel:  
![Windows beállítások menü](/docs/DownloadError5.png)  
Ezt a gombot megnyomva megjelenik ez a menü:  
![Védelmi előzmények](/docs/DownloadError6.png)  
Ez a művelet rendszergazdai beleegyezést kérhet, ezt engedélyezzük. Majd a következő menü fog megjelenni:  
![Veszélyes program](/docs/DownloadError7.png)  
**Fontos, hogy győződjünk meg arról, hogy a zölddel jelölt mezőben valóban a megfelelő fájl elérési útja található.**  
Ha itt is rendszergazdai beleegyezést kér, azt is engedélyezzük.  
Lehetséges, hogy a fájl nem lesz ott a letöltések között, mivel a Windows törölte. Ekkor újra le kell tölteni. Második próbálkozásra már nem lesz probléma a letöltéssel.  
Utolsó lépésként a tömörített fájlt csomagoljuk ki.  

**Letöltés Git haszálatával:**  
``` bash
git clone https://github.com/vitezninja/Super-Shot-Build.git
```
## Futtatás  
A letöltött mappában található `Super Shot.exe` nevű fájl futtatásával lehet elindítani a játékot. Az első futtatás után egy figyelmeztetés jelenhet meg, amely szerint a program potenciálisan veszélyes lehet.  
![Tűzfal riasztás](/docs/Firewall.png)  
Ezt fogadjuk el, mert minden nem megbízható programnál ez megjelenik.  

Az első elínditás lehet, hogy egy kicsit több ideig eltarthat. Kérlek legyél türelmes ne probáld megint elinditani mert akkor kétszer fog futni a program.
