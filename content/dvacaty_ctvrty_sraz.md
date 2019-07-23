Title: Dvacátý čtvrtý sraz - 
Date: 2019-04-02 18:00:00
Modified: 2019-04-02 18:00:00
Author: Anežka Müller

Na začátku jsme se věnovaly testovacímu frameworku, který připravuje Karolina. Při jeho vymýšlení a programování narazila na několik oblastí, které bude potřeba vyřešit, aby byl plošně aplikovatelný v rámci celé hry.
Framework bude pracovat s porovnáváním stavů hry, jejichž základem je mapa složená z jednotlivých políček. Mapy vytváříme v editoru Tiled a v současnou chvíli je součástí každé mapy kompletní tileset, takže obsahuje zbytečně velké množství dat. Řešily jsme tedy otázku, zda by se to nedalo vyřešit nějak lépe. Jako vhodné řešení se nabízí vyexportování tilesetu do samostatného JSON souboru, který si pak budou jednotlivé mapy z tohoto souboru načítat. O tomto způsobu vytváření map jsme uvažovaly už v počátcích projektu, v té době a tehdejším stavu projektu ale pro nás bylo jednodušší tileset kopírovat přímo do mapy. Nyní jsme však o velký kus dál a načítání z externího souboru je pro nás efektivnější řešení. 
Dalším faktorem testovacího frameworku je samotné porovnávání. Celkem jednoduše lze porovnat výchozí a konečný stav na mapě, hůře se ale porovnávají atributy jednotlivých robotů. 
Poslední téma, které Karolina otevřela, bylo zadávání příkazů pomocí karet, konkrétně to, v jaké formě psát jednotlivé příkazy. 
