# Modélisation et simulation d'un microgrid autonome PV / Batterie

Ce projet présente la modélisation et la simulation sous MATLAB/Simulink d'un microgrid hybride autonome associant une source photovoltaïque et un stockage par batterie Lithium-Ion.

### Ce qui a été développé :
- **Algorithme MPPT (Perturb & Observe) :** Écriture d'une fonction MATLAB personnalisée pour piloter le hacheur et extraire la puissance maximale du champ PV.
- **Régulation de tension :** Mise en place d'une boucle de contrôle PI pour stabiliser le bus DC à 320V face aux variations de production et de charge.
- **Gestion du stockage :** Simulation de la charge et décharge de la batterie Lithium-Ion avec suivi en temps réel de l'état de charge (SOC).
- **Étage de puissance :** Dimensionnement des convertisseurs DC-DC à MOSFETs et génération des signaux de commande PWM (10 kHz et 5 kHz).

### Outils & Environnement
MATLAB / Simulink, Simscape Electrical (powergui).


