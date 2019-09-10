# Exercice 4

Cet exercice est la suite de l’exercice de localisation d’un DEA. Modifiez votre programme afin de permettre à l’utilisateur du programme d’encoder les informations degrés, minutes, secondes dans une structure.

Il faut écrire 2 fonctions permettant de faciliter la vie de l’utilisateur :

1. Une fonction convertissant des coordonnées géographiques de degrés décimaux en radians.
```math
radian = dd \times \left( \frac{\pi}{180} \right)
```
2. Une fonction convertissant des degrés, minutes, secondes en degrés décimaux.
- Si les coordonnées sont positives :
```math
dd = Degrees + \left( \frac{Minutes}{60} \right) + \left( \frac{Secondes}{3600} \right)
```
- Si les coordonnées sont négatives :
```math
dd = Degrees - \left( \frac{Minutes}{60} \right) - \left( \frac{Secondes}{3600} \right)
```

Les latitudes Nord et longitudes Est sont positives. Les latitudes Sud et longitudes Ouest sont négatives.