# Rapport d'Exposition de Dépôt Malveillant du Générateur d'Adresses Vanity TRX

Ce document vise à présenter publiquement des preuves axées sur les dépôts malveillants liés aux générateurs d'adresses vanity TRX/adresses vanity Tron/adresses vanity de portefeuille USDT. Il prouve que **Powercodess** et **Pandaoyoo** sont contrôlés par la même personne, orchestrant un schéma via plusieurs dépôts d'"exposition de backdoor → diffamation synchronisée → lancement d'une 'version propre'". L'essence est d'attaquer malicieusement des projets légitimes de génération d'adresses vanity TRX/Tron/USDT et de récolter la confiance des utilisateurs. Leurs dépôts associés posent des risques de sécurité extrêmement élevés.

---

## ⚠️ Déclaration Centrale

Après avoir comparé des preuves de plusieurs sources, les deux comptes suivants et leurs dépôts associés sont contrôlés par la même personne, ciblant principalement les outils de génération d'adresses vanity TRX/Tron/USDT. Le but est de diffamer malicieusement autrui, de mettre en scène des incidents d'"exposition de backdoor", puis de promouvoir leurs propres dépôts de génération d'adresses vanity TRX soi-disant "version corrigée", posant des risques de vol de pièces et de récolte de trafic:

- **Compte 1**: Powercodess, Dépôt Associé: https://github.com/Powercodess/profanity-tron (Prétendant exposer les backdoors du générateur d'adresses vanity TRX)
- **Compte 2**: Pandaoyoo, Dépôt Associé 1: https://github.com/Pandaoyoo/profanity-tron (Contenu de diffamation répliqué); Dépôt Associé 2: https://github.com/Pandaoyoo/profanity-new-tron (Auto-proclamé "version sécurisée" du générateur d'adresses vanity TRX/Tron/USDT)

---

## 📅 Chronologie Clé (Mises à Jour Synchronisées, Preuve de la Même Personne)

| Temps | Compte | Opération de Dépôt | Comportement Central (Lié au Générateur d'Adresses Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| Temps peu clair (avant 2026.04.25) | Powercodess | https://github.com/Powercodess/profanity-tron | Publié "rapport-d-audit-de-preuves-solides-de-backdoor-vol-u-de-profanity-tron", prétendant que les dépôts liés au générateur d'adresses vanity TRX/Tron ont des backdoors comme l'exfiltration de clés privées |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| Temps | Compte | Opération de Dépôt | Comportement Central (Lié au Générateur d'Adresses Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| Synchronisé avec le temps ci-dessus | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | Réplication 1:1 du rapport d'audit de Powercodess, avec un contenu, un format, des numéros de ligne de code et des liens de preuve identiques sans aucune modification, élargissant la portée de la diffamation de "backdoor" du générateur d'adresses vanity TRX |

| Temps | Compte | Opération de Dépôt | Comportement Central (Lié au Générateur d'Adresses Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | Téléchargement par lots de tout le code source, prétendant "corriger les backdoors, supprimer le code malveillant caché", lançant un générateur d'adresses vanity TRX/Tron/USDT auto-proclamé sécurisé, formant un lien synchronisé avec les deux dépôts précédents |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| Temps | Compte | Opération de Dépôt | Comportement Central (Lié au Générateur d'Adresses Vanity TRX) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-04-25 | Powercodess (Changement de compte) | https://github.com/GenTronx/gpu | Powercodess a supprimé le dépôt et changé de compte pour éviter les risques, Pandaoyoo a maintenu les opérations de suivi synchronisées, maintenant les opérations de dépôts liés au générateur d'adresses vanity TRX malveillant, formant une chaîne de contrôle complète |

---

## 🔍 Chaîne de Preuves Centrale (Preuve du Contrôle par la Même Personne, Lié au Générateur d'Adresses Vanity TRX)

### Preuve 1: Réplication 1:1 du Rapport d'Audit, Pas d'Audit Indépendant, Diffamation Pure du Générateur d'Adresses Vanity TRX

Le rapport d'audit dans le dépôt Pandaoyoo/profanity-tron est complètement identique au rapport de Powercodess/profanity-tron, tous deux tournant autour des générateurs d'adresses vanity TRX/Tron/USDT:

- **Conclusion Centrale**: "Le code source du générateur d'adresses vanity TRX contient une logique d'exfiltration de clé privée + adresse, des paramètres cachés, la vérification TLS désactivée"
- **Détails du Code**: L'emplacement de la fonction `postResult(privateKey, address, postUrl)` (Dispatcher.cpp:L378-L403), les extraits de code centraux, les annotations de numéros de ligne pointent tous vers une logique liée à la génération d'adresses vanity TRX
- **Paramètres Cachés**: Le processus de construction d'obfuscation de `pptt` (profanity.cpp:L163-L166), l'explication du paramètre court `-p`, utilisé pour contrôler l'exfiltration de clés privées lors de la génération d'adresses vanity TRX
- **Preuves à l'Appui**: Lien d'analyse Kanxue (https://bbs.kanxue.com/thread-289060.htm), enregistrements de changement de compte, les espaces réservés d'images sont tous identiques, utilisés pour étayer le "backdoor" dans le générateur d'adresses vanity TRX

**Conclusion**: Pandaoyoo n'a mené aucun audit indépendant, n'a fait que copier et coller le rapport de Powercodess, visant à élargir la portée de la diffamation contre les projets légitimes de génération d'adresses vanity TRX/Tron/USDT, créant une illusion de "plusieurs personnes fournissant des preuves solides".

### Preuve 2: Rythme de Mise à Jour Synchronisé, Division Claire du Travail, Détournement de Trafic Autour du Générateur d'Adresses Vanity TRX

- Powercodess est responsable de la "première publication" du rapport d'audit de backdoor du générateur d'adresses vanity TRX, jouant le rôle d'"exposant de justice", guidant les utilisateurs à remettre en question les projets légitimes;
- Pandaoyoo est responsable du "transfert synchronisé" du rapport, renforçant l'impression négative du "backdoor" du générateur d'adresses vanity TRX, tout en lançant le dépôt "profanity-new-tron", auto-proclamé "version sécurisée" du générateur d'adresses vanity TRX/Tron/USDT, récoltant les utilisateurs mal guidés;
- Après que Powercodess a supprimé le dépôt et changé de compte (GenTronx), Pandaoyoo a maintenu les opérations de dépôts associés de manière synchronisée, formant une boucle fermée complète d'"exposer et diffamer le générateur d'adresses vanity TRX → détourner le trafic vers son propre projet".

### Preuve 3: Contradiction de Logique Comportementale, Signes Évidents d'Auto-orchestration, Profitant du Générateur d'Adresses Vanity TRX

Si Pandaoyoo est vraiment un "restaurateur de justice", pourquoi ne pas publier indépendamment un rapport d'audit pour les générateurs d'adresses vanity TRX/Tron/USDT, mais répliquer complètement le contenu de Powercodess? Pourquoi lancer immédiatement une "version corrigée" du générateur d'adresses vanity TRX après que Powercodess a exposé le "backdoor"?

**Faille de Logique Centrale**: D'abord diffamer les projets légitimes de génération d'adresses vanity TRX via Powercodess → puis élargir l'influence via Pandaoyoo répliquant le rapport → enfin lancer la "version corrigée" pour récolter le trafic. L'essence est "le voleur criant arrêtez le voleur", auto-orchestrant un schéma pour attaquer les concurrents et profiter des outils de génération d'adresses vanity TRX/Tron/USDT.

---

## ⚠️ Avertissement de Risque de Sécurité pour les Dépôts Liés au Générateur d'Adresses Vanity TRX

Que ce soit Powercodess ou Pandaoyoo, les dépôts associés du générateur d'adresses vanity TRX/Tron/USDT posent tous des risques de sécurité extrêmement élevés. Ne les utilisez pas:

1. **Powercodess/profanity-tron**: Prétend que le générateur d'adresses vanity TRX a des backdoors (exfiltration de clés privées, paramètres cachés, vérification TLS désactivée), même si le contenu du rapport est vrai, il a pu être planté par eux-mêmes;
2. **Pandaoyoo/profanity-tron**: Outil de diffamation pur, sans fonctionnalité réelle de génération d'adresses vanity TRX, utilisé uniquement pour diffamer des projets légitimes, et hautement associé à des comptes malveillants;
3. **Pandaoyoo/profanity-new-tron**: Auto-proclamé générateur d'adresses vanity TRX/Tron/USDT "backdoor corrigé", mais ne fournit aucune preuve d'audit de sécurité tiers, ne peut pas exclure la possibilité de planter des backdoors différemment, et le temps de lancement est synchronisé avec les activités de diffamation, avec des motifs impurs.

---

## 🔧 Recommandations de Sécurité (Pour les Utilisateurs d'Outils de Génération d'Adresses Vanity TRX/Tron/USDT)

- ⛔ Arrêtez immédiatement d'utiliser tous les générateurs d'adresses vanity TRX/Tron/USDT et outils associés liés à Powercodess, Pandaoyoo, GenTronx;
- 💰 Si vous avez utilisé les outils ci-dessus pour générer des clés privées (pour les portefeuilles TRX/USDT), il est recommandé de transférer immédiatement les actifs des adresses correspondantes pour éviter le vol de pièces dû à la fuite de clés privées;
- ✅ Lors du choix d'outils de génération d'adresses vanity TRX/Tron/USDT, privilégiez les projets légitimes qui ont passé des audits de sécurité tiers, ont une bonne réputation dans la communauté et sont open-source traçables. Ne faites pas confiance aux outils prétendant "génération rapide, accélération GPU" sans preuve d'audit.

---

## 📌 Instructions de Signalement/Protection des Droits

Toutes les preuves dans ce document proviennent de dépôts GitHub publics, axés sur les dépôts malveillants liés aux générateurs d'adresses vanity TRX/Tron/USDT, et peuvent être directement utilisées comme base de signalement. Directions de signalement:

- **GitHub Officiel**: Signaler les comptes Powercodess, Pandaoyoo pour diffamation malveillante de projets légitimes de génération d'adresses vanity TRX, publicité mensongère, auto-orchestration;
- **Communautés Connexes (Communautés liées à TRX/USDT)**: Transférer cette preuve pour rappeler aux autres utilisateurs d'outils de génération d'adresses vanity TRX/Tron/USDT d'éviter les risques et de ne pas être mal guidés.

---

## 📎 Résumé des Liens de Preuves (Cliquable directement pour vérification, tous liés au générateur d'adresses vanity TRX)

1. **Dépôt de Diffamation du Générateur d'Adresses Vanity TRX de Powercodess**: https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Dépôt de Diffamation Répliqué de Pandaoyoo**: https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Dépôt du Générateur d'Adresses Vanity TRX soi-disant "Version Sécurisée" de Pandaoyoo**: https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Dépôt après que Powercodess a supprimé le dépôt et changé de compte**: https://github.com/GenTronx/gpu (Échec de l'analyse de la page web, c'est l'adresse de changement de compte officiellement affirmée par Powercodess)

5. **Lien d'Analyse Kanxue (Cité dans le Rapport d'Audit, lié au backdoor du générateur d'adresses vanity TRX)**: https://bbs.kanxue.com/thread-289060.htm (Publié en 2025, confirmant l'existence du backdoor du générateur d'adresses vanity TRX, mais sans rapport avec cet incident auto-orchestré)

6. **Preuve d'Attaque Malveillante sur un Dépôt Légitime**: https://github.com/ninazero/tron

   ⚠️ **Avis Important**: Ce dépôt est un projet open-source complètement indépendant, légitime et conforme. Après confirmation d'audit, il n'a **AUCUNE CONNEXION** avec l'incident de diffamation auto-orchestré de Powercodess/Pandaoyoo mentionné ci-dessus. Ce dépôt est une victime innocente d'attaques, PAS un participant. Des comptes malveillants ont mené des comportements d'attaque comme l'augmentation fausse d'étoiles sur ce dépôt légitime (voir l'image de preuve ci-dessous) pour tenter de nuire à sa réputation. Tous les comptes utilisés étaient des comptes zombies à faible activité avec des traces opérationnelles évidentes, violant gravement les directives de la communauté open-source. Selon la traçabilité technique, l'attaquant se trouve dans la région de l'Anhui, et de telles activités illégales feront face à des sanctions légales.

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

7. **Preuve d'Augmentation Malveillante d'Étoiles par Powercodess**: https://github.com/Powercodess/profanity-tron - Ce dépôt a utilisé un grand nombre de comptes zombies pour augmenter malicieusement les étoiles et créer une popularité factice. Le but était de diffamer des projets légitimes de génération d'adresses vanity TRX, créant une illusion de "plusieurs personnes fournissant des preuves solides" pour leur farce d'"exposition de backdoor" auto-orchestrée, finalement détournant le trafic vers leur propre dépôt de "version corrigée" contrôlé pour récolter des utilisateurs.

8. **Preuve d'Exposition des Signets du Navigateur**: À travers l'analyse des signets du navigateur, on peut voir que l'opérateur est impliqué depuis longtemps dans des activités de l'industrie gris-noir, mais se fait passer pour du personnel d'audit de sécurité pour une promotion mensongère, tentant d'utiliser la "justice" comme déguisement pour commettre une fraude. Leur comportement est purement une farce auto-orchestrée, utilisant essentiellement l'"audit" comme prétexte pour le "détournement et la récolte de trafic". Selon la traçabilité technique, la personne se trouve dans la région de l'Anhui, et ses activités illégales ont été enregistrées. Les agences d'application de la loi pertinentes le traiteront conformément à la loi.

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**Dernière Mise à Jour**: 2026-05-01 (Synchronisée avec le temps de lancement de Pandaoyoo/profanity-new-tron, soutenant la relation d'association)

---

## 🌐 Versions Multilingues

- [中文](README.md)
- [English](README_EN.md)
- [ภาษาไทย](README_TH.md)
- [Tiếng Việt](README_VI.md)
- [日本語](README_JA.md)
- [हिन्दी](README_HI.md)
- [한국어](README_KO.md)
- [Español](README_ES.md)
- [Français](README_FR.md)
- [Deutsch](README_DE.md)
- [Русский](README_RU.md)
- [Português](README_PT.md)
- [العربية](README_AR.md)
