# Cours

On va faire de l'intégration. C'est à dire qu'on va reproduire le plus fidèlement possible une maquette qui nous est fournie en page web (HTML CSS).

## DRY

Dans le monde du développement, on est relativement faignant, on évite le plus souvent possible de nous répéter pour rien : on respecte le principe DRY (Don't Repeat Yourself).

Exemple pas bien:

```css
em {
    color : blue;
}

strong {
    color : blue;
}
````

Bon exemple:

```css

em, strong {
    color : blue;
}
