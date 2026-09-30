# Exercice fullstack — Une messagerie pour une équipe de support

## L'objectif de l'exercice

Nous vous proposons de créer une petite application web en partant de zéro, avec la stack de votre choix.

Nous souhaitons comprendre comment vous passez d'un besoin métier à une solution : comment vous priorisez, structurez votre projet, vérifiez son fonctionnement et expliquez vos décisions.

**Nous n'attendons pas que vous réalisiez tous les besoins décrits ci-dessous. Le choix du périmètre fait partie de l'exercice.** Le nombre de fonctionnalités livrées n'est pas le critère principal d'évaluation. Une solution simple et maîtrisée, accompagnée d'arbitrages argumentés, répond pleinement à l'objectif.

## Le contexte métier

Une petite entreprise propose un logiciel à ses clients. Trois personnes assurent le support et reçoivent quelques dizaines de demandes par jour.

Aujourd'hui, les échanges sont dispersés. Certaines demandes restent sans réponse, deux personnes répondent parfois au même client, et reprendre une conversation commencée par un collègue est difficile.

L'équipe souhaite disposer d'une messagerie commune. **Sa priorité est de limiter les demandes oubliées et de faciliter la coordination du support**, tout en permettant aux clients d'échanger simplement avec elle.

Vous construisez une première version destinée à être essayée par cette équipe. Aucun système existant n'est à intégrer. Les utilisateurs et les échanges de démonstration sont fictifs.

Cette première version a vocation à servir de base aux évolutions suivantes. D'autres développeurs doivent pouvoir reprendre le projet, y ajouter des fonctionnalités et s'assurer que leurs modifications ne cassent pas les usages déjà livrés. Tenez compte de cette continuité dans vos arbitrages entre périmètre fonctionnel et qualité de réalisation.

## Les besoins exprimés

Voici les demandes recueillies auprès des utilisateurs. Elles ne sont pas classées par priorité et ne constituent pas une liste de fonctionnalités à réaliser intégralement.

| Référence | Besoin exprimé |
| --- | --- |
| A | « En tant que client, je veux démarrer une conversation pour expliquer mon problème, puis retrouver les réponses et poursuivre l'échange. » |
| B | « Au support, je veux retrouver les conversations et leur historique pour comprendre une demande et y répondre. » |
| C | « Je veux repérer rapidement les demandes qui attendent une réponse de notre part. » |
| D | « Je veux savoir quel collègue s'occupe d'une demande et pouvoir la prendre en charge ou la lui confier. » |
| E | « Je veux distinguer les demandes terminées de celles encore à traiter, et pouvoir reprendre une demande si le client revient. » |
| F | « Je veux retrouver un ancien échange à partir de quelques mots dont je me souviens. » |
| G | « En tant que client, je veux joindre une capture d'écran pour mieux expliquer mon problème. » |
| H | « Je veux voir les nouveaux messages arriver sans devoir actualiser la page. » |
| I | « Au support, je veux laisser une note à mes collègues dans une conversation, sans qu'elle soit visible du client. » |
| J | « En tant que client, je veux être prévenu par e-mail lorsqu'une réponse arrive, même si j'ai fermé l'application. » |
| K | « Je veux éviter que deux collègues préparent une réponse au même moment sans le savoir. » |
| L | « En tant que responsable du support, je veux savoir combien de demandes restent à traiter et depuis combien de temps elles attendent. » |

À vous de choisir les besoins à couvrir, leur profondeur et l'ordre de réalisation. Vous pouvez proposer une réponse partielle ou simplifiée à un besoin, à condition de l'expliquer.

Il n'existe pas de combinaison de fonctionnalités attendue en secret. Nous regarderons la cohérence entre le problème métier, vos hypothèses, le temps disponible et la solution présentée.

## Le cadre

### Temps consacré

Consacrez **quatre heures maximum** à l'exercice, en incluant le cadrage, l'installation du projet, le développement, les vérifications et la documentation. Vous pouvez répartir ce temps en plusieurs sessions.

Arrêtez-vous au terme de ce temps, même si tout ce que vous aviez prévu n'est pas terminé. Indiquez simplement le temps approximatif réellement passé et ce qui reste à faire. Une fonctionnalité inachevée peut être un bon point de discussion ; elle ne justifie pas de dépasser le temps prévu.

Nous ne demandons ni présentation formelle ni slides à préparer en complément.

### Liberté technique

Les langages, frameworks, bibliothèques et outils sont libres. Vous pouvez utiliser les générateurs de projet habituels et vous appuyer sur une stack que vous connaissez bien. Un framework fullstack convient autant qu'un frontend et un backend séparés.

Le projet doit pouvoir être lancé localement à partir de vos instructions, sans abonnement payant nécessaire à son évaluation. Un déploiement public n'est pas demandé.

### Un parcours concret

Nous attendons au minimum **un parcours de messagerie utilisable de bout en bout** : envoyer un message depuis une interface web, le traiter côté serveur, le persister et pouvoir le retrouver après actualisation de la page et redémarrage de l'application.

Vous choisissez le reste du parcours et les besoins complémentaires. Les fonctionnalités annoncées comme réalisées doivent être réellement utilisables. Signalez clairement les parties simulées ou incomplètes.

### Une base pour la suite

Prévoyez un moyen simple et reproductible de vérifier les comportements essentiels du périmètre retenu. Un développeur qui reprend le projet doit pouvoir effectuer ces vérifications et détecter une régression sans devoir reconstituer lui-même tous les scénarios à essayer.

Réfléchissez également à la manière dont ces vérifications pourraient accompagner chaque changement partagé dans le dépôt. À vous de choisir ce que vous mettez en place dans le temps disponible et d'expliquer ce que vous reportez. Un périmètre réduit et fiable est préférable à davantage de fonctionnalités fragiles.

### Simplifications possibles

Vous pouvez fournir des utilisateurs et conversations précréés. Une inscription et une authentification complètes ne sont pas nécessaires : un sélecteur d'utilisateur de démonstration convient. Si vous simplifiez l'identification ou les droits d'accès, expliquez les limites et ce qui serait nécessaire avant une utilisation réelle.

L'interface doit permettre de comprendre et d'utiliser le parcours choisi. Une identité visuelle élaborée n'est pas attendue.

Pour toute ambiguïté, vous pouvez nous poser une question ou prendre une hypothèse explicite. Il n'est pas nécessaire de bloquer votre progression en attendant une réponse.

## Utilisation de l'IA

**L'utilisation d'outils d'IA est autorisée et fortement recommandée.** Vous êtes libre de les utiliser pour réfléchir, générer du code, déboguer, tester ou documenter.

Vous restez responsable de la solution présentée : vous devez pouvoir expliquer son fonctionnement, discuter ses limites et la modifier pendant l'entretien.

Indiquez brièvement les outils utilisés, ce que vous leur avez confié et comment vous avez vérifié le résultat. Un exemple de proposition corrigée ou écartée peut nourrir la discussion. Aucun historique exhaustif de prompts n'est demandé, et aucun outil payant particulier n'est attendu.

## Ce que vous devez remettre

Créez votre propre **dépôt Git privé** et donnez accès à la personne qui vous a transmis l'exercice. Si le sujet est publié dans un dépôt public, créez un dépôt indépendant pour votre solution plutôt qu'un fork public.

Votre dépôt doit contenir le code et un README concis permettant de :

- lancer le projet : prérequis, configuration, commandes et éventuelles données de démonstration ;
- essayer le parcours retenu et identifier les fonctionnalités réalisées, partielles ou écartées ;
- comprendre vos priorités : valeur métier, effort estimé, dépendances et compromis ;
- comprendre vos principaux choix techniques et la structure du projet ;
- relancer les vérifications du projet, comprendre les comportements qu'elles protègent et connaître leurs limites ;
- connaître le temps approximatif consacré, votre usage de l'IA et la prochaine amélioration que vous privilégieriez.

Quelques paragraphes ou tableaux suffisent. Documentez les décisions qui comptent pour votre solution. Si votre périmètre a changé pendant l'exercice, expliquez brièvement pourquoi.

Ne commitez aucun secret ni aucune donnée personnelle réelle. Fournissez des valeurs d'exemple pour la configuration nécessaire.

## La restitution — 45 minutes

L'entretien se déroule à partir de votre application et de votre code :

1. **Démonstration — 10 minutes** : présentez le parcours retenu, ce qui fonctionne et les limites.
2. **Discussion — 20 minutes** : expliquez vos arbitrages métier, vos choix techniques, vos vérifications et l'utilisation de l'IA. Nous lirons ensemble certaines parties du code.
3. **Petite évolution — 15 minutes** : nous introduirons une contrainte liée à votre solution et vous proposerons de réfléchir à son impact, puis de commencer une adaptation ensemble. L'IA reste autorisée. Terminer l'évolution n'est pas une condition de réussite.

Prévoyez un environnement dans lequel vous pouvez lancer et modifier votre projet. Nous nous intéressons autant à votre façon de raisonner et de vérifier qu'au résultat obtenu.

## Les critères d'évaluation

| Critère | Ce que nous cherchons à comprendre |
| --- | --- |
| Compréhension métier et priorisation | Vos choix servent-ils l'objectif du support ? Les renoncements et hypothèses sont-ils argumentés ? |
| Maîtrise de la réalisation | Le parcours annoncé fonctionne-t-il de bout en bout ? Comprenez-vous le code et les échanges entre interface, serveur et stockage ? |
| Architecture proportionnée et maintenabilité | Les responsabilités et le modèle de données sont-ils clairs ? Un autre développeur peut-il reprendre et faire évoluer le projet ? La complexité est-elle justifiée par les besoins retenus ? |
| Qualité d'usage et robustesse | Le parcours est-il compréhensible ? Les entrées invalides, erreurs et cas limites pertinents sont-ils pris en compte ? |
| Fiabilité dans la durée | Comment protégez-vous les comportements essentiels contre les régressions ? Les vérifications sont-elles pertinentes, reproductibles et faciles à exécuter à chaque changement ? |
| Recul et communication | Savez-vous expliquer les compromis, reconnaître les limites et adapter votre solution à une nouvelle contrainte ? |
| Maîtrise de l'IA | Comment évaluez-vous, corrigez-vous et validez-vous ce que les outils produisent ? |

**Nous accordons une importance particulière à la justification des décisions et à leur cohérence avec le code livré.** Aucun framework, nombre de couches, taux de couverture ou volume de code n'est attendu. Les choix seront discutés dans le contexte de cette première version et du temps imparti.
