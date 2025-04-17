
# 📚 Power BI projekt: Vizualizace čtenářských dat

Ve svém posledním projektu pro Engeto jsem se rozhodla pracovat s vlastními daty – konkrétně s knihami, které jsem v posledních letech přečetla. Dataset jsem připravila pomocí web scrapingu v Pythonu. Tento projekt najdete zde:  
🔗 https://github.com/martikudelova/Books_webscraping_withAI


## 📌 Zadání projektu:
- Rozsah 2-5 stránek
- Použití minimálně 5 různých typů vizuálů
- Filtrování (primárně) pomocí průřezů/slicerů
- Využití interaktivních prvků jako jsou záložky, navigace po stranách, odkazy na webové stránky, ...
- Propojení několika (2+) datových tabulek, buď přes vazby v rámci Power BI nebo přes propojení v Power Query
- Použití vytvořené hierarchie o alespoň dvou úrovních (nepovinné)
- Vytvoření alespoň 1 measure (metrika/míra) a 1 kalkulovaného sloupce/tabulky
- Grafická úprava použitých vizuálů, zvolení správných typů vizuálů a vizuálně přívětivý výsledný report


## 📊 Obsah sestavy:

#### 1. Rozcestník
- Úvodní stránka s logem a navigací do jednotlivých částí.

#### 2. Roční čtení v číslech
- Shrnutí čtenářského výkonu podle let.
- Zobrazení nejkratší, nejdelší a TOP knihy.
- Prstencový graf ukazuje, na kolik procent byl splněn roční cíl 20 knih.
- Tabulka s detaily o přečtených knihách.

#### 3. Nejoblíbenější autoři
- Autoři podle počtu přečtených knih.
- Mapa světa ukazuje národnosti autorů – čím větší bublina, tím více autorů z dané země.

#### 4. Nejoblíbenější žánry
- Karta zobrazuje 5 nejčtenějších a 3 nejméně čtené žánry.
- Možnost filtrování podle roku – pouze roky s vyšší četbou.

#### 5. Vývoj čtení
- Přehled TOP 10 nakladatelství a jejich průměrné hodnocení.
- Spojnicový graf vývoje čtení podle žánrů v jednotlivých letech.
- Lze využít jako inspiraci pro další čtení – např. u nejvyššího hodnocení najít další knihy vydané tímto nakladatelstvím.

#### + Navigace
Na každé stránce je možnost přechodu pomocí šipek nebo klikacího obrázku rozcestníku.



## ❗ Výzvy, se kterými jsem si neporadila (ocením feedback):
- Náhled jako koncový uživatel – kde zapnout režim „čtení“ v desktopové aplikaci?
- Roční čtení: chtěla jsem u TOP/nejkratší/nejdelší knihy zobrazit autora při najetí myší, ale nenašla jsem AI doporučenou možnost Tooltip.
- Roční čtení: zobrazení měsíců i s nulovým počtem přečtených knih v sloupcovém grafu – nechci mít chybějící měsíce v ose X, pokud jsem nic nepřečetla.
