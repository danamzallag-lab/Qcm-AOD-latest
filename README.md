# QCM Professionnel - AOD (Anticoagulants Oraux Directs)

Application web interactive de formation pharmaceutique sur les anticoagulants oraux directs.

## Description

QCM professionnel complet comprenant :
- 15 questions théoriques (QCM/QCU) sur les AOD
- 3 cas pratiques d'entretien pharmaceutique
- Système de scoring et feedback détaillé
- Interface moderne et responsive

## Contenu pédagogique

### Thèmes abordés :
- Différences entre les 3 AOD (Apixaban, Rivaroxaban, Dabigatran)
- Schémas posologiques et modalités de prise
- Gestion des oublis de dose (règle 6h/12h)
- Interactions médicamenteuses (AINS, antiagrégants)
- Gestion péri-opératoire
- Surveillance des signes hémorragiques
- Antidotes spécifiques
- Contre-indications

### Cas pratiques :
1. Gestion d'un oubli de dose (Apixaban)
2. Préparation à une extraction dentaire (Dabigatran)
3. Interaction AINS + AOD (Rivaroxaban)

## Déploiement

### Déploiement sur Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/danamzallag-lab/Qcm-AOD-latest)

Ou via CLI :
```bash
npm install -g vercel
vercel
```

### Développement local

```bash
# Cloner le repository
git clone https://github.com/danamzallag-lab/Qcm-AOD-latest.git
cd Qcm-AOD-latest

# Installer serve (optionnel)
npm install -g serve

# Lancer le serveur local
serve .
# ou simplement ouvrir index.html dans un navigateur
```

## Technologies

- HTML5
- CSS3 (Gradients, Animations)
- JavaScript Vanilla (ES6+)
- Responsive Design

## Fonctionnalités

- Interface moderne avec dégradés bleus professionnels
- Barre de progression dynamique
- Validation en temps réel avec feedback
- Explications détaillées pour chaque question
- Système de scoring avec badges
- Cas pratiques interactifs
- Message de félicitation final
- Bouton de redémarrage

## Structure

```
QCM AOD LATEST/
├── index.html          # Application complète (HTML + CSS + JS)
├── package.json        # Configuration du projet
├── vercel.json         # Configuration Vercel
├── .gitignore         # Fichiers à ignorer
└── README.md          # Documentation
```

## Auteur

Dan Amzallag

## Licence

MIT

## Support

Pour toute question ou suggestion, ouvrir une issue sur GitHub.
