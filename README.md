---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #0f172a
# ... (style inchangé)
---

# Refonte Inscription SoliCode  
Sprint 1 – Interface publique

**Réalisation :** Yousra Akajou  
**Encadrement :** M. ESSARRAJ Fouad

---

## Objectif Sprint 1

Créer une interface publique **statique** et **responsive** fidèle à la maquette :

- Hero + valeurs du centre
- Catalogue formations Web & Mobile
- Navigation responsive (menu burger mobile)
- Formulaire contact + carte intégrée
- Accessibilité & animations subtiles

---

## Méthodologies utilisées

- **SCRUM**  
![SCRUM](imgs-presentation/scrum.jpg)

- **Design Thinking**  
![w:800 Design Thinking](imgs-presentation/designThinking.jpg)

---

## Fonctionnalités livrées

- Navigation responsive desktop/mobile
- Hero avec CTA inscription
- Bloc statistiques (KPI)
- Menu mobile + icône utilisateur
- Mode clair/sombre persistant 
- Smooth scroll (Lenis) + back-to-top
- Icônes Lucide + animations Motion One

---

## Use Case

![Use case](imgs-presentation/uc.png)

---

## Laboratoire utilisé

Spatie

---

## Maquette de référence

![Maquette](imgs-presentation/maquette.png)

---

## Points techniques principaux (index.html)

- Configuration Tailwind (soliBlue, soliYellow, fonts)
- Lucide icons initialisation
- Smooth scroll global Lenis (anchors)
- Animations d’entrée Motion One (inView, hero, scroll progress)
- Gestion thème clair/sombre (localStorage)
- Logique ouverture/fermeture menu mobile
- Bouton back-to-top lié à Lenis

---

# Des retours ??