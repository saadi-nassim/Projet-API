##                                                              Projet_Bases de données -API
***

### Réalisé par :     Nassim SAADI    -    Sid-Ali DJABELLA   -      Ilhem ATROUN 
### Encadré par : Mr Léo SOUQUET 
### Université Paris Est Créteil 
***

#### Présentation de l'API 
Nous avons opti pour l'utilisation de l'API publique Cheapshark qui est un site de comparaison de prix pour les jeux PC numérique. nous suivons les prix dans plusieurs magasins, notamment strram, GreenMangaming , fanatical et bien d'autres, notre api consiste à suivre les propriétés prix + métadonnées pour les jeux d'un magasin donné ainsi les bons plans.


### Imporation de l'API sur python 

![1](https://user-images.githubusercontent.com/75087781/103780027-c21af480-5034-11eb-99e2-d42a2a583845.png)


![2](https://user-images.githubusercontent.com/75087781/103780072-d2cb6a80-5034-11eb-84f2-7b80f827cd27.png)

![3](https://user-images.githubusercontent.com/75087781/103809753-4338b280-505a-11eb-8c1f-d4100def6b7b.png)
### Affichage sous format json avec la fonction suivante 
![image](https://user-images.githubusercontent.com/75087781/103817142-65d0c880-5066-11eb-88bb-9165a2442fe3.png)

### La fonction ci-dessous nous à permet d afficher le dictionnaire de données de de API  (Liste des attributs possible)
![4](https://user-images.githubusercontent.com/75087781/103809769-4c298400-505a-11eb-8a0b-751c33ca8a69.png)

### Affichage en format dataframe 
![5](https://user-images.githubusercontent.com/75087781/103809780-50ee3800-505a-11eb-93bf-092fcbba4897.png)
### On à fais un data cleaning pour afficher les colonnes désirées 
![image](https://user-images.githubusercontent.com/75087781/103817639-5900a480-5067-11eb-94dd-f42d9a7884f6.png)
### Crétion d'une Base de données Game sur SQL Server 
![image](https://user-images.githubusercontent.com/75087781/103811158-c5c27180-505c-11eb-8b04-4d4d413937ee.png)
### Connexion sur notre base de données SQL à partir de jupyter notebook  
![6](https://user-images.githubusercontent.com/75087781/103809792-55b2ec00-505a-11eb-86f5-b7cb7bedb73d.png)
### création d'une table nommée Jeux dans notre base de données SQL 
![8](https://user-images.githubusercontent.com/75087781/103809822-66fbf880-505a-11eb-9104-7edc490220f3.png)
### Notre table avant le remplissage 
![image](https://user-images.githubusercontent.com/75087781/103811030-8562f380-505c-11eb-9c30-724a6f92eb72.png)
### chargement des données avec la fonction suivante à partir de jupyter notebook
![7](https://user-images.githubusercontent.com/75087781/103809802-59df0980-505a-11eb-88f3-a37110faec89.png)

### L'affichage aprés le remplissage de la table Jeux 

![9](https://user-images.githubusercontent.com/75087781/103809831-6bc0ac80-505a-11eb-9eb0-52e05b4e9592.png)
### Test avec une requette sur SQL Server 
![image](https://user-images.githubusercontent.com/75087781/103813964-34093300-5061-11eb-8362-efcbf9cacac0.png)
