# Introduction à la virtualisation et à la conteneurisation

**Machines physiques**: ordinateurs, smartphones etc
**Serveurs**: Ce sont des ordinateurs spéciaux (généralement sans claviers et écrans), dont le but est de servir les autres ordinateurs (encore appelés clients) sur internet. Ils effectuent les tâches suivantes : 
- Hébergement des sites web
- Effectuer des analyses de données
- etc
**Rappel sur les composants d'un ordinateur :**
- hardware (partie physique):
   - CPU
   - Carte mère 
   - Stockage
   - etc
- Software (partie logicielle):
    - Système d'exploitation
    - Les logiciels
    - etc 
Les machines physiques présentent des limitations lorsqu'on décide de les utiliser pour faire plus d'une chose à la fois. Voici quelques limitations des machines physiques :

-**Les machines physiques sont coûteuses :** lorsqu'on veut faire plusieurs choses à la fois, on voudra naturellement soit augmenter les capacités de la machine ou payer d'autres machines. Cela requiert donc un investissement
- **Les machines physiques ont besoin de maintenance :** Pour effectuer des mises à jour du système, on a besoin d'un temps d'inactivité, ce qui a pour effet d'interrompre des activités importantes.
- **Les machines physiques sont complexes à mettre à l’échelle :** Lorsqu'une machine a besoin de plus de ressources, on doit remplacer l'entité de ses composantes. Ce qui peut être un processus complexe et gourmand en temps.

La solution à ces limitations est de créer une machine virtuelle à l'intérieur de sa machine physique.

**Définition d'une machine virtuelle :** une machine virtuelle est un ordinateur simulé à l'intérieur d'un ordinateur réel. C'est un logiciel qui fait semblant d'être une machine physique. Il possède son propre système d'exploitation et ses propres applications.

**Avantages d'une machine virtuelle :**
- On peut installer plusieurs machines virtuelles, indépendamment les unes et des autres, pour effectuer plusieurs tâches distinctes.
- Les machines virtuelles sont totalement isolées les unes des autres.
- Les machines virtuelles permettent l'utilisation de plusieurs systèmes d'exploitation sur la même machine.
- Capable de s'adapter a l'evolution des besoins en ressources de manieres efficace et flexible.

**La virtualisation :** est le processus par lequel une version simulée d'une ressource informatique se créée. Il y a plusieurs niveau de virtualisation, allant des composants de l'ordinateur jusqu'a l'ordinateur tout entier