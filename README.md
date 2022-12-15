# Présentation OpenSource et Logiciels Libres
Présentation académique pour les étudiants de la filière EMI sur le campus de ECAM LaSalle à Lyon. Travail collaboratif avec Nicolas Flandrois, cette version est un fork de [la version html](https://github.com/NicolasFlandrois/Linux-Intro-ECAM-Presentation) de N.Flandrois.

## Utilisation
Le fichier au format pdf est construit via Beamer sans animations javascript et peut donc être utilisé avec n'importe quel lecteur, y compris via le navigateur.

## Thème Beamer
Les quatres fichiers `.sty` permettent la mise en page  du fichier ``.tex``. Dans le cas où le logo doit être changé, les lignes suivantes doivent être modifiées :

- Dans ``beamerinnerthemeecamrs.sty`` :

```
\node at (0.5\paperwidth,1) {\newlogo{path/to/img}{options}};
```

- Dans ``beamerouterthemeecamrs.sty`` :

```
\node at (1.5,0) {\newlogo{path/to/img}{options}};
```

## To Do
- Repenser la mise en page du thème pour paraître plus moderne
- Mettre à jour les logos des logiciels libres
