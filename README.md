Projektterv és előzetes dokumentáció
1. A projekt bemutatása
A vizsgamunka témája egy edzőterem működését támogató webes alkalmazás, aminek a neve GymManager. A rendszer célja, hogy megkönnyítse az edzőtermek mindennapi adminisztrációját, valamint egyszerűbbé tegye a vendégek számára az edzések és foglalások kezelését.

Napjainkban egy edzőterem működtetése során számos adatot kell nyilvántartani, például a vendégek adatait, a bérletek érvényességét, az edzők beosztását és az edzések időpontjait. Ezek kezelése papíralapon vagy különálló táblázatokban időigényes és nehezen átlátható lehet. A GymManager ezeknek a feladatoknak a digitális kezelésére nyújt megoldást.

2. A program célja és funkciói
A fejlesztés során egy olyan rendszert szeretnénk létrehozni, amely a vendégek és az edzőterem dolgozói számára egyaránt hasznos.

A vendégek a webes felületen megtekinthetik az elérhető edzéseket, az edzők adatait és a különböző bérlettípusokat. Lehetőségük lesz edzésekre jelentkezni, saját foglalásaikat megtekinteni és szükség esetén lemondani.

Az adminisztrációs felület segítségével az arra jogosult felhasználók kezelhetik a vendégeket, az edzőket, a bérleteket és az edzések időpontjait. Új adatokat rögzíthetnek, meglévő adatokat módosíthatnak, illetve törölhetnek.

A rendszer a foglalás létrehozásakor ellenőrzi a szabad férőhelyeket, így megakadályozható, hogy egy edzésre a megengedettnél több vendég jelentkezzen. A program célja továbbá az adatok pontosabb nyilvántartása és az adminisztrációs feladatok csökkentése.

3. A rendszer technikai felépítése
A projekt három fő részből épül fel: a kliensoldali felületből, a szerveroldali alkalmazásból és az adatbázisból.

A szerveroldali alkalmazás C# programozási nyelven, ASP.NET Core Web API használatával készül. Ez felel az adatok feldolgozásáért, az üzleti logika megvalósításáért és a kliens kéréseinek kezeléséért.

A rendszer RESTful architektúrát alkalmaz. A kliens HTTP kéréseken keresztül kommunikál a szerverrel. A GET metódus az adatok lekérésére, a POST új adatok létrehozására, a PUT meglévő adatok módosítására, a DELETE pedig adatok törlésére szolgál.

Az adatok tárolása MySQL adatbázisban történik. Az adatbázisban külön táblákban szerepelnek a vendégek, az edzők, a bérletek, az edzések és a foglalások. A táblák közötti kapcsolatok biztosítják, hogy az adatok megfelelően összekapcsolhatók legyenek.

A kliensoldali felület HTML, CSS és JavaScript segítségével készül. A Bootstrap keretrendszer alkalmazásával a weboldal reszponzív kialakítású lesz, így különböző méretű kijelzőkön, számítógépen és mobiltelefonon is használható.

4. Adattárolás és adatkezelés
Az alkalmazás az edzőterem működéséhez szükséges adatokat strukturált adatbázisban tárolja. A vendégekhez kapcsolódnak a bérleteik és foglalásaik, az edzőkhöz pedig az általuk tartott edzések.

Az adatkezelés során fontos szempont az adatok pontossága és a megfelelő ellenőrzés. A rendszernek figyelnie kell például arra, hogy egy foglalás csak létező vendéghez és edzéshez kapcsolódjon, valamint ne lehessen túllépni az edzés maximális létszámát.

A fejlesztés során törekszünk az átlátható adatbázis-felépítésre és a megfelelő adatkezelési szabályok kialakítására.

5. Műszaki feltételek
A program használatához internetböngészővel rendelkező számítógép, laptop vagy mobiltelefon szükséges. A fejlesztéshez Visual Studio Code, .NET SDK, MySQL adatbázis-kezelő és egy korszerű webböngésző használható.

A szerver futtatásához telepített .NET környezet és elérhető adatbázis szükséges. A pontos verziók és konfigurációs beállítások a fejlesztés során kerülnek meghatározásra.

6. Összegzés
A GymManager egy olyan webes alkalmazás, amely egy valós edzőtermi problémára kínál digitális megoldást. Segítségével egyszerűbbé válik a vendégek, bérletek, edzők és foglalások kezelése.

A projekt megvalósítása során lehetőségem nyílik a C# programozási nyelv, a REST API-k, az adatbázis-kezelés és a reszponzív webfejlesztés gyakorlati alkalmazására. A célunk egy könnyen használható, átlátható és megbízható rendszer létrehozása, amely megfelel a vizsgamunkával szemben támasztott követelményeknek.
