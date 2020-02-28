# 2IMV10
Preprocessing Images

Standaard input: Preprocess(r"folders\abe.jpg", save=True, scale=1, amount=0.0001, keep_percentage=0.01, lowThreshold=100, highThreshold=255, kernel_size=(5,5), iterations=1)

De parameters:
  - Save: maakt folder aan met de tijd, en daarin 3 bestanden: de image zelf, een array van zwarte pixels en een settings.txt met alle waardes van de variables + image size.
  - Scale: (Integer >= 1) schaal van resizen van de image
  - Amount: (Float (0 =< i =< 1) percentage zwarte noise je wil
  - Keep_percentage (Float 0 =< i =< 1): percentage zwarte puntjes dat je wil houden
  - lowThreshold (Integer 0 =< i =< 255): lage threshold van Canny operator
  - highThreshold (Integer 0 =< i =< 255): hoge threshold van Canny operator
  - kernel size: (Oneven Tuple: 1 =< i =< ~11 ofzo): kernel size voor dilaten (dikker maken) van de edges
  - iterations: (Integer >= 1): aantal iterations van de dilation algoritme. Standaard: 1

Je moet code wel even aanpassen met juiste string voor je documents enzo. In de code zelf kan je ook de thresholds tunen voor de canny edge detection

