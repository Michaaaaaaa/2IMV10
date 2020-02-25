# 2IMV10
Preprocessing Images

Voorbeeld input is dit bijvoorbeeld: Dither(r"C:\Users\micha\OneDrive - TU Eindhoven\00. Studie Relevant\2IMV10\Python\img\abe.jpg", scale=1, amount=0.001, save=False)

De parameters:
  - Scale: van het resizen van de image
  - Amount: voor percentage zwarte noise je wil
  - Save: maakt folder aan met de tijd, en daarin 3 bestanden: de image zelf, een array van zwarte pixels en een settings.txt met de waardes voor amount & scale
  
Je moet code wel even aanpassen met juiste string voor je documents enzo. In de code zelf kan je ook de thresholds tunen voor de canny edge detection
