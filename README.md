# SDMIS — Simulateur d'intervention VSAV

Simulateur 3D d'interventions de secours à personne, conçu pour réviser les protocoles de la formation sapeur-pompier.

**[Lancer le simulateur →](https://sacha9214.github.io/sdmis-sim/)**

![Sélection du cas clinique](docs/apercu.png)

## Cas cliniques

| Cas | Priorité | Situation |
|---|---|---|
| Arrêt cardiaque | Rouge | ACR chez un adulte de 58 ans : RCP, défibrillation, RACS |
| Traumatisme grave | Rouge P1 | Chute de 6 m : garrot, rachis, conditionnement |
| AVP incarcéré | Orange P2 | Conducteur incarcéré, volet thoracique |
| Détresse respiratoire | Orange P2 | OAP chez une femme de 72 ans : VNI, furosémide |

## Fonctionnalités

- **Scène 3D** : VSAV avec gyrophares, secouristes et victime animés, signes cliniques visibles sur la peau (cyanose, pâleur, marbrures, sueurs)
- **Bilan MARCH** : hémorragie massive, voies aériennes, respiration, circulation, hypothermie
- **Constantes vitales en direct** : FC, SpO2, PA, FR, glycémie, température, avec seuils d'alerte
- **Déroulé en 6 phases** par intervention, avec journal des événements
- **Vitesse réglable** (×0,5, ×1, ×2) et commandes tactiles (rotation à un doigt, zoom à deux doigts)

## Stack

Un seul fichier `index.html` : HTML, CSS et JavaScript, rendu 3D avec [Three.js](https://threejs.org/) r134. Aucun build, aucune dépendance à installer.

## Lancer en local

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Avertissement

Projet personnel de révision, sans lien officiel avec le SDMIS. Il ne remplace ni la formation ni les référentiels en vigueur.

## Licence

[MIT](LICENSE)
