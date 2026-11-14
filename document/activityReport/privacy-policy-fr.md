# Activity Report — Politique de confidentialité

*Dernière mise à jour : 28 octobre 2026* · [English version](privacy-policy.md)

Activity Report est une app macOS qui rédige votre stand-up quotidien à partir de votre activité GitHub, de vos réunions, de vos rappels et de vos propres notes. Elle est conçue pour que vos données restent sur votre Mac.

**En bref : le développeur ne collecte aucune donnée. Pas de compte, pas de statistiques d'usage, pas de publicité, pas de pistage. L'app ne communique qu'avec GitHub, avec votre propre jeton, pour lire votre activité.**

## Ce que l'app lit, et où cela va

| Donnée | Pourquoi | Où elle va |
|---|---|---|
| Votre jeton d'accès personnel GitHub | Lire votre activité GitHub | Conservé dans le trousseau macOS. Envoyé uniquement à GitHub (`api.github.com`), en HTTPS. |
| Votre activité GitHub : événements, pull requests, reviews, équipes | Rédiger le rapport et lister vos pull requests | Demandée à GitHub avec votre jeton, affichée dans l'app. Jamais envoyée ailleurs. |
| Les événements de votre calendrier pour le jour du rapport | Lister vos réunions | Lus sur votre Mac via le Calendrier macOS (EventKit). Jamais envoyés. |
| Vos rappels | Lister ce qui est terminé et ce qui est prévu | Lus sur votre Mac via les Rappels macOS (EventKit). Jamais envoyés. |
| Vos notes (*Next*, *Blockers*) et les textes de stand-up copiés | Les conserver un an, et rédiger les bilans | Enregistrés dans le dossier de l'app sur votre Mac, supprimés après un an. |
| Vos pull requests sur une période allant jusqu'à un an | Rédiger un bilan, quand vous le demandez | Demandées à GitHub avec votre jeton, puis résumées sur votre Mac par Apple Intelligence (le modèle d'Apple intégré à l'appareil). Jamais envoyées ailleurs. |
| Vos réglages (langue, organisations, liens de tickets, formats) | Mémoriser vos choix | Enregistrés dans les préférences de l'app sur votre Mac. |

macOS demande l'accès au calendrier et aux rappels la première fois ; vous pouvez le retirer à tout moment dans Réglages Système › Confidentialité et sécurité.

Quand vous copiez le texte de stand-up, il est placé dans le presse-papiers pour que vous le colliez, par exemple dans Slack ou Google Chat. Ce qu'il devient ensuite dépend de vous et de ces services.

## Ce que reçoit le développeur

Rien. L'app ne contient aucun code de statistiques, de rapport de plantage ou de publicité, et n'envoie rien au développeur. Si vous choisissez, dans les réglages de macOS, de partager les rapports de plantage avec les développeurs, Apple peut transmettre des rapports anonymes au développeur, selon la [politique de confidentialité d'Apple](https://www.apple.com/fr/legal/privacy/).

## Tiers

- **GitHub** reçoit les requêtes que l'app fait avec votre jeton, comme pour tout client GitHub. Voir la [déclaration de confidentialité de GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
- **Apple** distribue l'app et traite tout achat fait via l'App Store. Voir la [politique de confidentialité d'Apple](https://www.apple.com/fr/legal/privacy/).

## Conservation et suppression

- Les notes et les textes copiés sont supprimés automatiquement après un an ; vous pouvez aussi supprimer une copie depuis l'écran Historique.
- Le jeton peut être remplacé dans Réglages › GitHub, ou supprimé avec l'app Trousseau d'accès (élément « ActivityReport.GitHubToken »).
- Supprimer l'app et son dossier (`~/Library/Containers/com.benjdum59.ActivityReport`) efface tout ce qu'elle a enregistré. Vous pouvez aussi révoquer le jeton sur GitHub à tout moment, dans Settings › Developer settings › Personal access tokens.

## Enfants

L'app est un outil de travail et ne s'adresse pas aux enfants.

## Modifications

Si cette politique change, la nouvelle version sera publiée à cette adresse, avec sa date.

## Contact

Pour toute question sur cette politique : benjammin.dumont.pro@gmail.com
