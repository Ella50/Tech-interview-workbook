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
    1. Felfedezés után be kell kategorizálni a hibát súlyossága alapján. 
    2. Utána történik a hibafeloldás, vagyis a hiba kijavítása. 
    3. Ezután következik az ellenőrzés, hogy a hiba biztos ki lett javítva. 
    4. Ha sikeres az ellenőrzés, akkor a hiba állapota lezárt lesz. 
    5. Ezután készül el a hibajelentés (bug report) a tesztmenedszerek által, hogy a vezetői csapat jelzést kapjon a hibakezelés folyamatáról.

 <img src="https://www.guru99.com/images/TestManagement/testmanagement_article_4_4.png" width="450" height="340">

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
    A tesztjelentés célja, hogy összefoglalja és átadja a tesztelési tevékenységre vonatkozó információkat a tesztelési tevékenység során és annak végén. A vizsgálati tevékenység során elkészített tesztjelentést más néven tesztelőrehaladási jelentésnek, míg a tesztelési tevékenység végén elkészített tesztjelentést összefoglaló tesztjelentésnek is nevezik. A tesztmenedzser rendszeresen készít tesztelőrehaladási jelentéseket az érdekeltek számára.
    A tipikus összefoglaló tesztjelentések tartalmazhatják az alábbiakat:
        - Az elvégzett tesztelés összefoglalás
        - Tájékoztatás a tesztelési időszak alatt történtekről
        - A tesztelési tevékenységek ütemtervét, időtartamát vagy a ráfordításokat (és az eltéréseket is)
        - Azok a tényezők, amelyek blokkolták vagy továbbra is blokkolják a haladás
        - A tesztelés és a termékminőség állapota 
        - Fennmaradó kockázatok
        - Hibák, tesztesetek
        - Erőforrás-fogyasztás mérőszámai


#### ✅ Mit tartalmaz egy hibajelentés?
    • Azonosító
    • A bejelentett hiba címe és rövid összefoglalása
    • A hibajelentés dátuma, a kibocsátó szervezet és a szerző
    • A tesztelem (az éppen tesztelt konfigurációs elem) és a környezet azonosítója
    • A fejlesztési életciklus fázisa(i), amelyben a hibát észlelték
    • A hiba reprodukálását és megoldását lehetővé tevő leírás, beleértve a naplófájlokat, az adatbázis mentéseket, képernyőképeket vagy felvételeket (ha volt ilyen a teszt végrehajtása során)
    • Elvárt és tényleges eredmények
    • A hiba súlyosságának (severity) hatóköre vagy mértéke az érdekelt felek érdekeit tekintve
    • A javítás sürgőssége/prioritása
    • A hibajelentés állapota (pl. nyitott, elhalasztott, duplikált, megoldásra váró, ellenőrző tesztelésre váró, 
    újranyitva, lezárt)
    • Következtetések, ajánlások és jóváhagyások
    • Globális problémák, például olyan területek, amelyekre a hibából eredő változás hatással lehet
    • Változási előzmények, mint például a projektcsapat tagjai által a hibával kapcsolatos lépések, hogy 
    elkülönítsék, javítsák és ellenőrizzék azt
    • Hivatkozások, beleértve a problémát feltáró tesztesetet is

#### ✅ Hogyan rangsorolnál egy hibát?
    4 típusba sorolnám a hibákat:
       - Kritikai: A hibát a lehető leghamarabb meg kell szüntetni, mivel az súlyosan érinti a rendszert, és a javításig nem használható
       - Magas: A termék lényegére, fő részére van káros hatással
       - Medium: Másodlagos funkcióval van hiba
       - Alacsony: Minimálisan van hatással a termék működésére

<img src="https://www.guru99.com/images/TestManagement/testmanagement_article_4_7.png" alt="image" width="450" height="340">


## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
    Tesztesetek, amelyeket érdemes automatizálni:
        - Időigényes tesztek – amelyeket manuálisan nehéz vagy sokáig tart végrehajtani.
        - Amelyek pontos adatbevitelhez vagy konzisztens végrehajtáshoz kötöttek
        - Nagy mennyiségű adatot használó tesztek
        - Többször változó tesztadatokkal végrehajtandó tesztek
        - Kritikus funkciók automatizált ellenőrzése

    Tesztesetek, amelyeket nem érdemes automatizálni:
        -Ritkán futtatott tesztek
        - Folyamatosan változó felhasználói felület tesztelése 
        - Kreativitást, intuíciót vagy emberi észlelést igénylő tesztek –
        - Olyan tesztek, ahol a hibák csak nem várt módon lépnek fel 
        - Tesztrögzítéssel létrehozott, lineáris szkriptek nagyszámú teszthez 

#### ✅ Írj le egy jó automatizált tesztet! (Mitől lesz jó?)
    - Stabil és megbízható (Nem bukik el hamisan, nem hagy hibákat észrevétlenül)
    - Ismételhető
    - Nem függ manuális előkészületektől vagy véletlenszerű tényezőktől
    - Gyors (néhány másodperc alatt fut le)
    - Olvasható és karbantartható (világos szerkezet, beszédes elnevezések)
    - Könnyen frissíthető, ha a rendszer változik
    - Független más tesztektől
    - Így párhuzamosan is futtathatók és nem zavarják egymást
    - Egyértelműen értékelhető
    - Pontosan tudjuk, hogy mi a siker és mi a hiba kritériuma
    - Valós üzleti értéket tesztel
    - Olyan funkciót tesztel, amit a felhasználók ténylegesen használnak
    - Automatikusan futtatható 
    - Emberi beavatkozás nélkül végigfuthat
    - Jól dokumentált
    - Paraméterezhető és adatvezérelt


#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
    A Selenium webalkalmazások automatikus tesztelésére szolgáló keretrendszer. Ez széles körben használható és az egyik legismertebb nyílt forrású teszteszköz.

    A Selenium IDE egy Firefox add-on amely a böngésző interakciók egyszerű felvételére és lejátszására képes. Ez egy beépített fejlesztői környezet, melynek jelentése, hogy az applikáció segít neked szoftvereket fejleszteni a segédprogramokon keresztül.

    A Selenium WebDriver mind a nyelvi kötésekre, mind az egyes böngészővezérlő kódok implementációira vonatkozik. Ezt általában egyszerűen WebDriverként emlegetik. Vezérli a böngészőt, ahogyan azt egy felhasználó tenné, akár helyben, akár egy távoli gépen a Selenium szerver használatával.

#### ✅ Hogyan lehet azonosítani a webes elemeket?
    1. Azonosító (id)
    2. Név
    3. Osztály
    4. Címke (tag)
    5. Link
    6. XPath


#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
    Implicit várakozással, ami beállít egy általános maximális időt minden elemkereséshez.
    Explicit várakozással egy adott feltétel teljesüléséig várakozik.

    NoSuchElementException:	(elem nem található) Túl gyorsan keresi, még nem jelent meg

    TimeoutException: (várakozási idő alatt nem jelent meg az elem)	Hosszú betöltési idő vagy hibás lokátor miatt

    ElementNotVisibleException: (elem létezik, de nem látható) Az oldal még nem teljesen töltődött be



#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
    A POM és a Keyword Driven Testing összehasonlításakor figyelembe kell venni a komplexitást, az újrafelhasználhatóságot, az olvashatóságot és a skálázhatóságot. A POM több kódolási készséget és erőfeszítést igényel a beállításához és karbantartásához, de nagyobb rugalmasságot és kontrollt kínál a tesztlogika és a végrehajtás felett. A Keyword Driven Testing egyszerűbb és könnyebben megvalósítható, de korlátozhatja a teszt lefedettségét és funkcionalitását. Az újrafelhasználhatóság mind a POM, mind a Keyword Driven Testing előnye, mivel csökkenti a kód duplikációját és a karbantartási költségeket. A POM olvashatósága javul az objektumorientált elvek miatt, amelyek elválasztják a felhasználói felület elemeit a tesztlogikától. A Keyword Driven Testing a teszteseteket olvashatóbbá teszi a természetes nyelv és a leíró kulcsszavak használatával. Végül a skálázhatóságot mind a POM, mind a Keyword Driven Testing támogatja, mivel képesek kezelni dinamikus webalkalmazásokat, különféle típusú alkalmazásokat, különböző böngészőket.


#### ✅ Mi a különbség a TDD és BDD között?
    Fókusz: A TDD elsősorban a kód tesztelésére, míg a BDD a rendszer viselkedésének és interakcióinak tesztelésére összpontosít.
    Nyelv: A TDD-t általában programozási nyelvekkel valósítják meg, míg a BDD-hez egy természetesebb nyelvi formátumot használnak.
    Közönség: A TDD főként a fejlesztőket célozza meg, míg a BDD a fejlesztők, tesztelők és érdekelt felek közötti együttműködést foglalja magában.
    Tesztesetek: A TDD az egységtesztekre, míg a BDD az elfogadási tesztelésre és a végpontok közötti forgatókönyvekre helyezi a hangsúlyt.


#### ✅ Mi az API tesztelés és miért hasznos?
    Az API-tesztelés a szoftvertesztelés egy olyan formája, amely elemzi az API-t, és biztosítja, hogy az az elvárásoknak megfelelően teljesíti funkcióit. (szoftver komponensei közti kommunikáció, válaszidő, adathelyesség)
    Hasznos, mert segít a szoftverfejlesztési életciklus minden szakaszában. Automatizálható és skálázható. Emellett gyors és stabil, mert nem függ a felhasználói felülettől.

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
    Az adatvezérelt tesztelés egy szoftvertesztelési módszer, amelyben a tesztadatokat táblázat vagy táblázat formájában tárolják. Az adatvezérelt tesztelés lehetővé teszi a tesztelők számára, hogy egyetlen tesztszkriptet vigyenek be, amely képes tesztelni egy tábla összes tesztadatát, és a tesztkimenetet ugyanabban a táblában várja. Táblázatvezérelt tesztelésnek vagy paraméterezett tesztelésnek is nevezik.
    Fontos, mert a tesztelők gyakran több adatkészlettel rendelkeznek egyetlen teszthez, és az egyes adatkészletekhez egyedi tesztek létrehozása időigényes lehet. Az adatvezérelt tesztelés segít az adatok elkülönítésében a tesztszkriptektől, és ugyanazok a tesztszkriptek futtathatók a bemeneti tesztadatok különböző kombinációihoz, és a teszteredmények hatékonyan generálhatók.


<img src="https://www.guru99.com/images/1/032318_1019_WhatisDataD1.png" alt="image" width="550" height="220">


#### ✅ Mik a kihívások és ajánlott eljárások a dinamikusan betöltött webes elemekkel?

#### ✅ Mik a mobil tesztautomatizálás kihívásai?

## Haladó témák
<img src="https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/05/DevOps-in-a-Selenium-Testing.png" alt="image" width="320" height="220">

#### ✅ Mi a különbség a CI és CD között?
#### ✅ Írj le egy Continuous Delivery folyamatot!
#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!
#### ✅ Mi a Docker és miért hasznos?