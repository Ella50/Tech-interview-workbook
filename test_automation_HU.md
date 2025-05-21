# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
    A munkatermékek és kód  hibamegelőzés céljából történő kiértékelése. 
    Igazolja, hogy az összes meghatározott követelmény teljesült-e. 
    A meghibásodások és hibák megtalálása és ezáltal a nem megfelelő szoftverminőség kockázati szintjének csökkentése

    Nem garantálja a hibamentességet és a renszer sikerességét

#### ✅ Mik a tesztelési alapelvek?
    1. A tesztelés a hibák jelenlétét mutatja, nem a hiányukat (nem képes igazolni, hogy nincsenek hibák)

    2. Nem lehetséges kimerítő teszt (mindenre kiterjedő tesztelés a nem lehetséges + kockázatelemzés, tesztelési technikák használata és priorizálása szükséges)

    3. A korai tesztelés időt és pénzt spórol (statikus, dinamikus teszttevékenységeket korán el kell kezdeni -> költséges változtatások csökkentése vagy eliminálása)

    4. Hibafürtök megjelenése (megjósolt hibafürtök és a tesztelés vagy működés során ténylegesen megfigyelt hibafürtök fontos bemenetként szolgálnak a tesztelési erőforrások összpontosítása érdekében alkalmazott kockázatelemzés számára)

    5. Kísérd figyelemmel a féregirtó paradoxont (a tesztek egy idő után már nem hatékonyak a hibák megtalálásában)

    6. A tesztelés függ a körülményektől

    7. A hibamentesség egy téveszme (lehetetlen minden tesztet lefuttatni és minden hibát megtalálni + nem biztosítják a rendszer sikerességét)

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
    A komponenstesztelés a külön tesztelhető komponensekre összpontosít. Célja a kockázat csökkentése a hibák megtalálása és csökkentése.
    A fejlesztő felelős a kiírásért


#### ✅ Mik a tesztszintek, és mi a különbség köztük?
    Komponenstesztelés - külön tesztelhető komponensekre összpontosít
    Integrációs tesztelés - komponensek közötti kölcsönhatásokra összpontosít
    Rendszertesztelés - teljes rendszer képességeire összpontosít
    Elfogadási tesztelés - egész rendszer képességeire összpontosít 

#### ✅ Mi a különbség a verifikáció és a validáció között?
    Verifikáció: specifikált követelményeknek való megfelelés ellenőrzése
    Validáció: rendszer felhasználói igényeknek való megfelelés ellenőrzése

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
    Funkcionális - rendszer által végzendő funkciók kiértékelése
    Nemfunkcionális - rendszerek használhatóságának, biztonságának vizsgálása
    Fehér doboz - rendszer belső szerkezete alapján származtatja a teszteseteket
    Ellenőrző - célja megerősíteni, hogy az eredeti hiba sikeresen javítva lett 
    Regressziós - nem szándékolt hatások észlelésére szolgáló tesztek


#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
    Fehér doboz:a teszt tárgyának belső struktúrája vagy a kódja elemzésén alapul, a teszt tárgyán belüli feldolgozásra koncentrál
    Fekete doboz: tesztelés tárgyának bemeneteire és kimeneteire 
koncentrál, a belső szerkezetre történő hivatkozás nélkül
    Szürke doboz: részleges információ a belső szerkezetről


#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
    Felhasználói elfogadási tesztelés: felhasználók által a rendszeren végzett teszt mely valós vagy szimulált éles működési környezetben validálják azt, hogy a rendszer a leendő felhasználók számára alkalmas lesz-e a használatra.

    Rendszertesztelés: fejlesztők által a rendszeren végrehajtott elfogadási tesztelés, hogy megfelel-e az adott szempontoknak


#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
    Regressziós tesztelés: 
    változtatások után történő ellenőrzés a meglévő funkciók helyes működésének

    Újratesztelés:
    hiba javítása után történő ellenerző teszt

    Füsttesztelés:
    alapvető funkcionalitásnak való megfelelés gyros ellenőrzése


#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
    Statikus - a munkatermékek manuális vizsgálatára, ténylegesen nem hajtja végre a kódót, hibát közvetlenül találja meg, munkatermékek konzisztenciájának és belső minőségének javítására fókuszál

    Dinamikus - hibák okozta meghibásodásokat azonosítjuk a szoftver futtatása, a kívülről látható viselkedésekre fókuszál

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
    Vízesés-modell: 
    fejlesztési tevékenységek egymás után fejeződnek be (akkor kezdődnek el a teszttevékenységek, ha minden fejlesztési tevékenység befejeződött)

    V-modell:
    egyes tesztszintekhez kapcsolódó tesztek végrehajtása egymás után történik (átfedés történhet), korai tesztelés elvét valósítja meg

    Agilis fejlesztési modell:
    alkalmazható a front-end felhasználói interfész, illetve a funkcionalitás (UI) fejlesztésére és tesztelésére; tesztelés már az iterációk közben és a fejlesztési folyamat integrált része a tesztelés


<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">







## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!

#### ✅ Mit tartalmaz egy hibajelentés?

#### ✅ Hogyan rangsorolnál egy hibát?


## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?

#### ✅ Írj le egy jó automatizált tesztet!

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?

#### ✅ Hogyan lehet azonosítani a webes elemeket?

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!

#### ✅ Mi a különbség a TDD és BDD között?

#### ✅ Mi az API tesztelés és miért hasznos?

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?

