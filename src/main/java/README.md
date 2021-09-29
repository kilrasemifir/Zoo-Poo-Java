# Exercice du Zoo en Java

## Pr�sentation
L but de cet exercice est de cr�er des animaux en utilisant les concepts de la POO.

## �nonce

### Exercice 1 : Les Animaux
Cr�er une interface ```Animal``` qui contient les m�thodes :
* String getNom()
* void nourrir()
* int getAge()

### Exercice 2 : Mon premier animal
Cr�er un classe ```Chat``` qui impl�mente l'interface Animal
Le chat peut aussi se reproduire. Ajouter une methode ```Animal reproduire(Animal partenaire)```
Si le partenaire n'est pas un chat, lever une exception montrant son m�contentement.

### Exercice 3 : Les mammif�res
Cr�er une classe ```Chien``` qui impl�mente l'interface ```Animal```.
Le chien peut aussi se reproduire...
Les chats et les chiens sont deux animaux de type mammif�res.
Cr�er une classe abstraite Mammif�re qui impl�mente animal et qui d�finie la m�thode ```Animal reproduire(Animal partenaire)```.

### Exercice 4 : Animaux de compagnie
Les chien et les chats sont des animaux de compagnie.
Cr�er une interface AnimalDeCompagnie qui h�rite de l'interface Animal et qui ajoute les m�thodes :
* String getNom()
Ajouter cette interface aux chien et chat.

Tous les mammif�res n'�tant pas des animaux de compagnie, seul les chat et chien ont cette caract�ristique.

### Exercice 5 : Aquatique
Cr�er une interface Aquatique avec les m�thodes :
* void nager()
Cr�er une class d'un animal qui peut nager (comme le requin).
Cr�er une baleine qui est un mammif�re et un Aquatique.

### Exercice 6: Volant
Cr�er une interface Volant qui poss�de les m�thodes :
* void voler()
Cr�er une classe d'un animal volant.
Cr�er une classe Chauve-souris.

### Exercice 7: Terrestre
Cr�er une interface Terrestre qui poss�de les m�thodes :
* void marcher()

Cr�er une classe d'un animal terrestre.

### Exercice 8 : Les cages
Cr�er une classe Zoo qui poss�de les m�thodes :
* void ajouter(Animal nouvelAnimal)
* List<Animal> getAnimaux()
* List<Mammif�re> getMammif�res()
* List<Volant> getVolant()
* List<Aquatique> getAquatique()
* List<Terrestre> getTerrestre()

