# Devoir-Robotique-EIC---Bras-robotique-plusieurs-degr-s-de-libert-
Explication du fonctionnement de mon bras robotisé

1. Présentation du projet
Mon projet consiste à réaliser un bras robotisé composé de trois servomoteurs, contrôlés par une carte Arduino Uno dans Tinkercad. Ce bras peut effectuer plusieurs mouvements pour simuler la manipulation d'un objet.
2. Rôle de chaque servomoteur
	ServoBase (broche 9) : permet de tourner la base du bras vers la gauche ou vers la droite.
	ServoBras (broche 10) : permet de faire monter et descendre le bras.
	ServoPince (broche 11) : permet d'ouvrir et de fermer la pince pour saisir ou relâcher un objet.

3. Les degrés de liberté
Un degré de liberté correspond à un mouvement indépendant qu'un mécanisme peut effectuer. Mon bras robotisé possède 3 degrés de liberté, car il utilise trois servomoteurs qui réalisent chacun un mouvement différent : la rotation de la base, la montée et la descente du bras, ainsi que l'ouverture et la fermeture de la pince.

4. La séquence du programme loop()
Au début du programme, le bras se place en position de repos. Ensuite, la base tourne vers la gauche, le bras monte à 90°, puis la pince se ferme pour simuler la saisie d'un objet. La base tourne ensuite vers la droite, la pince s'ouvre et le bras revient à sa position de repos. Cette séquence est répétée automatiquement grâce à la fonction loop() de l'Arduino.


ce projet me permet de comprendre comment programmer et coordonner trois servomoteurs pour réaliser des mouvements indépendants avec un bras robotisé.


	Lien du Devoir: https://www.tinkercad.com/things/6sHYRGzCeVU-cool-amberis

