

| TESZTESET | Tesztelt követelmény | Előfeltételek (kiindulási állapot) | A teszt lépései | Elvárt kimenet/eredmény |
| :---: | :---: | :---: | :---: | :---: |
| **#0** | a GT4500 torpedóival lehet tüzelni | van legalább 1 torpedó a hajóban | tüzelünk egy torpedót (pl. TORPEDO,SINGLE) | a TORPEDO parancs eredménye SUCCESS |
| **#1** | a GT4500-on ha csak primary elérhető | csak a primary van feltöltve 2 torpedóval | tüzelünk három torpedót (TORPEDO,SINGLE) utasítással | 1.: SUCCESS, 2.: SUCCESS, 3.: FAIL |
| **#2** | a GT4500-on ha csak secondary elérhető | csak a secondary van feltöltve 2 torpedóval | tüzelünk három torpedót (TORPEDO,SINGLE) utasítással | 1.: SUCCESS, 2.: SUCCESS, 3.: FAIL |
| **#3** | a GT4500-on ha a failure rate 1.0 | secondary és a primary is fel van töltve 1-1 torpedóval | tüzelünk kettő torpedót (TORPEDO,SINGLE) utasítással | 1.: SUCCESS, 2.: FAIL, 3.: FAIL |
| **#4** | a GT4500-on ha ALL módban tüzel, de csak az egyik elérhető | csak a primary van feltöltve 1 torpedóval | tüzelünk kettő torpedót (TORPEDO,ALL) utasítással | 1.:SUCCESS, 2.:SUCCESS, 3.:FAIL |
| **#5** |  |  |  |  |












