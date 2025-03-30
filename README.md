# 076_Comparing_City_Sizes  
📊 Geometriai összehasonlítás 🐍pythonban: Budapest és 10 másik magyar város 🏙️

Hétvégi térinformatikai (GIS) vizualizációs projektem: Budapestet hasonlítsuk össze 10 másik hazai várossal területük alapján — mindezt szép, átlátható ábrákban, egyetlen grafikonban. Lásd a csatolt képet.

💡 Hogyan működik a kód?

🔍 A OpenStreetMap adatbázisából lekérdezem a városok geometriai határait az osmnx könyvtár segítségével.

🗺️ Az összes várost az EOV (EPSG:23700) vetületi rendszerbe helyezem át, amely pontos távolság- és területszámítást tesz lehetővé Magyarországon.

📐 Budapest középpontjához igazítom a többi város kontúrját, így egy térképen tudom őket elhelyezni, arányosan és egymáshoz viszonyítva.

📊 Az eredményeket egy 5x2-es subplot struktúrában jelenítem meg: minden kis térképen Budapest a háttér, a másik város zölden, átlátszóan jelenik meg.

🔢 Minden ábra alatt megjelenik a két város területe (km²-ben), illetve az arány, pl. „Szeged: 281 km², Budapest: 525 km² → 53%”.

👩‍💻 Könyvtárak: matplotlib, geopandas, osmnx

 📌 Városok: Szolnok, Szeged, Debrecen, Miskolc, Pécs, Győr, Székesfehérvár, Zalaegerszeg, Sopron, Kecskemét



 #GIS #Python #DataVisualization #GeoPandas #OpenStreetMap #osmnx #matplotlib #Hungary #UrbanData #Budapest #DataAnalysis #DataScience #DataEngineering
