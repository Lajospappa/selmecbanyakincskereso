# Hangszermentők – PRINT (GitHub Pages)

## Használat
1. Másold be a saját képeidet a `images/` mappába, az ott megadott fájlnevekkel.
2. Töltsd fel ezt a mappastruktúrát egy GitHub repository gyökerébe.
3. GitHub Pages: Settings → Pages → Deploy from a branch → Branch: main / root.
4. Nyisd meg a publikált oldalt, majd nyomtatás (A4, Margók: none, Méretezés: 100%, Háttérgrafika: ON).

## Mit javítottam
- A „Megoldás” cikk `start-col` osztállyal mindig új hasáb tetején indul (Firefox/print stabilabb).
- Kivettem a közvetlenül előtte lévő `col-break` üres törő elemet, hogy ne legyen dupla törés.
- Print módban enyhítettem a `break-inside: avoid` használatát (Chrome gyakran ettől akad meg), és csak a kritikus blokkoknál tartottam meg (képek, doboz, `no-split`).
