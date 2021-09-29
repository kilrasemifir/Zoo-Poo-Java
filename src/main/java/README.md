# Exercice du Zoo en Java

## Présentation
L but de cet exercice est de créer des animaux en utilisant les concepts de la POO.

## Énonce

### Exercice 1 : Les Animaux
Créer une interface ```Animal``` qui contient les méthodes :
* String getNom()
* void nourrir()
* int getAge()

### Exercice 2 : Mon premier animal
Créer un classe ```Chat``` qui implémente l'interface Animal
Le chat peut aussi se reproduire. Ajouter une methode ```Animal reproduire(Animal partenaire)```
Si le partenaire n'est pas un chat, lever une exception montrant son mécontentement.

### Exercice 3 : Les mammifères
Créer une classe ```Chien``` qui implémente l'interface ```Animal```.
Le chien peut aussi se reproduire...
Les chats et les chiens sont deux animaux de type mammifères.
Créer une classe abstraite Mammifère qui implémente animal et qui définie la méthode ```Animal reproduire(Animal partenaire)```.

### Exercice 4 : Animaux de compagnie
Les chien et les chats sont des animaux de compagnie.
Créer une interface AnimalDeCompagnie qui hérite de l'interface Animal et qui ajoute les méthodes :
* String getNom()
Ajouter cette interface aux chien et chat.

Tous les mammifères n'étant pas des animaux de compagnie, seul les chat et chien ont cette caractéristique.

### Exercice 5 : Aquatique
Créer une interface Aquatique avec les méthodes :
* void nager()
Créer une class d'un animal qui peut nager (comme le requin).
Créer une baleine qui est un mammifère et un Aquatique.

### Exercice 6: Volant
Créer une interface Volant qui possède les méthodes :
* void voler()
Créer une classe d'un animal volant.
Créer une classe Chauve-souris.

### Exercice 7: Terrestre
Créer une interface Terrestre qui possède les méthodes :
* void marcher()

Créer une classe d'un animal terrestre.

### Exercice 8 : Les cages
Créer une classe Zoo qui possède les méthodes :
* void ajouter(Animal nouvelAnimal)
* List<Animal> getAnimaux()
* List<Mammifère> getMammifères()
* List<Volant> getVolant()
* List<Aquatique> getAquatique()
* List<Terrestre> getTerrestre()

