# PFA — Conception d'un redresseur monophasé à thyristors

Projet de fin d'année (ENIT, génie électrique) : étude, simulation et conception d'un redresseur monophasé commandé à thyristors (BT152-800R) avec son circuit de commande (driver de gâchette).

## Contenu

| Dossier / fichier | Description |
|---|---|
| `Simulation_LTspice/` | Simulations LTspice : simple alternance, double alternance, pont complet (`SIM_finale/sim_PONT.asc`), train d'impulsions de commande |
| `kicad-redresseur/redresseur/` | Projet KiCad du redresseur : schéma, PCB, nomenclature (`.csv`), export PDF |
| `kicad-redresseur/librairie/Kicad/` | Symboles, empreintes et modèles 3D utilisés |
| `datasheets/` | Fiches techniques des composants (BT152, 2N2222, …) |
| `travail demandé/` | Cahier des charges et présentation |
| `PFA2_THYPON_FINALE.pdf`, `dim_Driver.pdf` | Rapport / dimensionnement du driver |

## Outils
- LTspice
- KiCad

## Notes
Les fichiers de résultats LTspice (`*.raw`) ne sont pas versionnés : relancer la simulation pour les régénérer.
Les librairies composants SamacSys / Ultra Librarian ne sont pas incluses (licence interdisant la redistribution) ; elles se téléchargent gratuitement sur componentsearchengine.com.

## Auteur
Rami Dridi — ENIT
