# Conversion énergétique dans une cavité résonante — Du vent à l'électricité

**TIPE — Travaux d'Initiative Personnelle Encadrés**  
Auteur : O. Denis  
Année : 2024–2025

---

## Résumé

Ce projet étudie l'amplification de vibrations mécaniques dans un résonateur de Helmholtz couplé à une lame vibrante, dans le but de convertir l'énergie du vent en électricité via un matériau piézoélectrique (quartz). L'approche combine modélisation théorique, simulation numérique et validation expérimentale.

**Problématique :** Comment optimiser la conversion d'énergie mécanique en énergie électrique par résonance couplée dans une cavité de Helmholtz, sous hypothèse de flux d'air constant ?

---

## Positionnement thématique

- Physique — Mécanique
- Physique — Physique de la matière
- Informatique — Informatique pratique

**Mots-clés :** résonance couplée · résonateur de Helmholtz · piézoélectricité · vibration · conversion énergétique

---

## Structure du dépôt

```
tipe-resonant-cavity/
├── docs/                  # Fiches MCOT (FR + EN), bibliographie annotée
├── experiments/           # Protocoles expérimentaux, mesures, résultats bruts
├── presentation/          # Diaporama de soutenance (.pptx), simulation, données
└── README.md
```

---

## Principes physiques clés

### Résonateur de Helmholtz
Fréquence de résonance :

$$f = \frac{v}{2\pi} \sqrt{\frac{A}{LV}}$$

- $v$ : vitesse du son (~343 m/s)
- $A$ : section du col
- $L$ : longueur du col
- $V$ : volume de la cavité

### Résonance couplée
Interaction entre une lame vibrante et la cavité pour maximiser l'amplitude des déplacements mécaniques. La synchronisation des fréquences propres des deux systèmes est critique.

### Piézoélectricité
Contrainte mécanique → polarisation électrique (effet direct, utilisé ici en générateur). Efficacité dépendante du matériau, du placement et des pertes par dissipation mécanique.

---

## Chronologie (DOT)

| Période | Étape |
|---|---|
| Sep. 2024 | Familiarisation avec la récupération d'énergie piézoélectrique |
| Sep.–Oct. 2024 | Étude de la résonance couplée et des résonateurs de Helmholtz |
| Nov. 2024 | Conception théorique du protocole — choix des canettes comme résonateurs |
| Déc. 2024 | Calcul des fréquences de résonance, préparation matériel |
| Jan. 2025 | Premiers tests expérimentaux — résultats concluants |
| Jan.–Fév. 2025 | Tests de couplage — expériences non concluantes |
| Mars 2025 | Système lame vibrante + cavité Helmholtz — résultats convaincants |
| Mai–Juin 2025 | Vérification des hypothèses, tests en conditions réelles |

---

## Références bibliographiques

1. Boyer A., Leblanc C., Molinier A., Sauvage L. — *Résonateurs de Helmholtz : résonances acoustiques et optimisation des cavités* — Olympiades de Physique, École Alsacienne (2011)
2. Hoang T. — *Dispositif de récupération d'énergie piézoélectrique : modélisation, fabrication et caractérisation* — Thèse, Université de Tours, GREMAN (2019)
3. Zhang Q. — *Récupération de micro-énergie renouvelable par couplage multiphysique* — Thèse, Université de Grenoble, LOCIE (2011)
4. Sabat R. — *Métasurface acoustique par couplage entre résonateurs de Helmholtz* — Thèse, Université de Lorraine (2017)
5. Ahmed-Seddik B. — *Systèmes de récupération d'énergie vibratoire large bande* — Thèse, Université de Rennes 1 (2020)
6. Bruneau M. — *Acoustique des cavités : modèles et applications* — Rapport CNRS (2018)
7. Damy G., Gauthier M. — *Production d'énergie à partir de la houle* — CNEXO-COB (1981)
