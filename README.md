# AnimalFootprintRecognition
   
   
   U fajlu DataAugmentation.ipynb se nalazi kod korišćen za augmentaciju trening podataka.
   U fajlu AnimalFootprintRecognition.ipynb je kod za treniranje cnn i predikciju.
   
   Za pokretanje treniranja mreže ili predikcije nad testnim skupom podataka potrebno je AnimalFootprintRecognition.ipynb
   fajl otvoriti u [Google Collab](https://colab.research.google.com/notebooks/intro.ipynb) okruženju i upload-ovati skup podataka nad kojim se vrši treniranje/predikcija. 
   Skup podataka se nalazi u folderu Data.
   
### Tim
   Ana Mijailović SW13/2016

### Definicija problema
   Određivanje kojoj životinji pripadaju prepoznati otisci sa slike.

### Skup podataka
   Skup podataka obuhvata otiske 10 odabranih životinja (medved, mačka, pas, kokoška, krava, patka, konj, zec, 
   pacov, veverica).
   Kolekcija je kreirana od slika pronađenih na internetu na kojima su otisci na različitim podlogama(snegu,pesku... ).

### Metodologija
  Za prepoznavanje kojoj životinji pripada trag koristi se konvoluciona neuronska mreža.

### Evaluacija
  Skup podataka podeljen je na trening, validacioni i test skup.
  Za merenje performansi korišćen je accuracy nad testnim skupom.
  
