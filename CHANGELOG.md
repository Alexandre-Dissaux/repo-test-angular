# Changelog

Toute modification liée au code exécuté en production sera documenté dans ce fichier.

Le présent format s'appuie sur [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

Ce fichier ne doit pas être mis à jour directement, il faut utiliser le fichier
`CHANGELOG-UNRELEASED.md`.
Par la suite les changements de `CHANGELOG-UNRELEASED.md` sont reversés dans ce
fichier lors de la création d'une nouvelle release.

## [1.36.0] - 2021-12-09

- SEJ-1613: TVE/DCEM : Désactivation du feature flag de l'habilitation local séjour
- SEJ-1578: Liste déroulante qui ne permet pas de transferer les demandes
- ANTM-473: Restituer titre sejour en cours de validite
- ANTM-621: Erreur de libelle sur le bouton tout replier
- SEJ-1428: DCEM - Décision - Correction du wording de modale de fixation de rdv
- SEJ-1161: Historique des changements de pays exclus
- SEJ-1403: DCEM - Ajout de la date a la creation du compte usager mineur
- SEJ-1562: TVE - Instruction - correction du bloquage due au non validation de l'adresse
- TRV-521: Problème dates union et naissance
- SEJ-766: DCEM - Gestion des demandes de date de report dépassées
- ANTM-197: Renommer la tuile Procédure Dublin en "Dublin sortant"
- SEJ-765: DCEM - créer la bannette DCEM à remettre
- SEJ-1612: [AGENT] - reparation des tests qui ne passent pas
- ANTM-195: Création du nouveau rôle "Instructeur Dublin"
- SEJ-1410: DCEM - historique des demande de report de rendez-vous

## [1.35.1] - 2021-12-06

- SEJ-1713: [PROD] Mécanisme anti-rejeu à mettre en place

## [1.35.0] - 2021-12-02

- SEJ-1442: DCEM - Instruction - Correction deux prénoms enfant mineur
- TRV-522: Instruction : Absence du bouton "Demander un complément"
- ANTM-463: Accéder à la fonctionnalité "Enregistrer un signalement OP" pour les BPI
- SEJ-614: DCEM - Décision - Dates de validite
- SEJ-1392: DCEM - [AGENT] - instruction manque liens personels et familiaux quand parent_2 present
- SEJ-1510: Fix wording Statut Demandeur
- SEJ-1311: Message date_validite_anterieur sur page de decision
- SEJ-1402: TVE Flux AGDREF: flux 32
- SEJ-1331: DCEM - Instruction - Enfant mineur bénéficiaire - anomalie champ "Nature du lien avec le demandeur"
- ANTM-585: Création du nouveau rôle "Responsable national Dublin"

## [1.34.1] - 2021-11-29

- SEJ-1612: [AGENT] - reparation des tests qui ne passent pas
- ANTM-616: Correctif Disparition bouton identite approchante mayotte

## [1.34.0] - 2021-11-24

- SEJ-623: [AGENT] DCEM - Gestion des demandes de report de RDV
- ANTM-570: Extraction CSV Ajustements mineurs suite recette interne
- TRV-475: Mise à jour de la page "Aide"
- ANTM-307: Ecran de suivi des usagers SOP : écran fiche détail (Mesures administratives)

## [1.33.1] - 2021-11-18

- ANTM-602: Disparition des informations lors de la validation de l'état civil N° AGDREF connu du SI
- ANTM-606: Erreur tuile GU lorsqu'un usager n'a pas de nom

## [1.33.0] - 2021-11-16

- SEJ-1430: [AGENT] DCEM - Décision : Messager d'erreur bloquant pour fixer un rdv en préfecture
- SEJ-1369: [AGENT] DCEM - Instruction bloque par la non validation de l'adresse
- SEJ-1409: Multiprocédure - page décision
- SEJ-1076: DCEM - Gestion des demandes de report de RDV
- SEJ-1143 : créer le volet Statut du titulaire dans l'entête
- ANTM-153: Souligner la page du menu sur laquelle l'utilisateur se trouve
- SEJ-1235: recuperation composant pays exclus
- SEJ-622: DCEM - Délivrance du DCEM
- SEJ-624: [AGENT] DCEM - Finalisation de l'instruction
- SEJ-1210: DCEM/TVE - Donnees Connues Titulaires rafraîchissement

## [1.32.0] - 2021-11-09

- ANTM-590: Statut erroné sur tableau de suivi SOP
- ANTM-176: Correction du mauvais message d'erreur
- ANTM-226: Champ de recherche dans la modale d'ajout de document
- SEJ-1308: Impossible d'enregistrer la page décision
- ANTM-421: Retirer la(les) photo(s) du planning des GUDA
- TRV-516: Déclaration changement SF : Page d'instruction bloquée (Pas de conjoint)
- ANTM-572: Problème au niveau des pages sur lesquelles s'ouvrent les tuiles GU enregistrement et Demande d'asile
- ANTM-507: Données de transmission des documents écrasées par les sauvegardes suivantes
- SEJ-611: [AGENT] DCEM - Page d'instruction : récupération historique DCEM et affichage des infos du mineur
- SEJ-1077: Instruction - La demande de CJN expire au bout de quelques jours
- SEJ-1182: TVE - Page instruction : Informations de contact
- ANTM-179: Formulaire de premier accueil : boutons à masquer
- ANTM-517: Modifier les references CESEDA des natures de decision
- ANTM-359: Ajout des nouvelles habilitations dans la recherche avancée utilisateurs
- SEJ-1172: Cacher le bouton "Rechercher l'identité"
- ANTM-480: Statut de BPI dans le tableau de résultat
- ANTM-481: Ecran de détail des usagers SOP : Statut de BPI dans la fiche détaillée

## [1.31.0] - 2021-11-04

- SEJ-724: TVE - Page de décision : calcul des durées de validité
- SEJ-722: TVE - Adapter la page de décision
- SEJ-600: DCEM - Page d'instruction : Liens personnels et familiaux
- SEJ-693: TVE - page d'instruction : etat civil ajout des données du bénéficiaire
- TRV-461: Décision - correction orthographique corriger le statut de la décision
- TRV-143: Instruction - Affichage des informations du changement de l'usager "situation familiale"
- ANTM-476: Probleme de payload flux
- SEJ-1236: retour à la branche develop de lib-ui
- SEJ-610: DCEM - Page de décision : Fixer un RDV, envoyer la convocation
- ANTM-510: Impossible de valider le recueil dans la tuile GU Enregistrement pour une demande d'asile en rééxamen 2
- ANTM-499: Impossible d'enregistrer un nouveau modèle quotidien et hebdomadaire - Tuile prise de RDV
- SEJ-625: DCEM - Page d'instruction : Création / mise à jour du compte du mineur
- SEJ-1123: TVE - Instruction : volet liens personnels et familiaux
- SEJ-594: [AGENT] DCEM - Page d'instruction : Etats civils - données parent / représentant - Cas 1 et 2
- ANTM-509: Messages d'erreurs qui n'ont pas lieu d'être lors de la génération du numéro étranger

## [1.30.1] - 2021-10-27

ANTM-387: [PROD] Erreur de sauvegarde à la création d'une habilitation

## [1.30.0] - 2021-10-27

- SEJ-1237: DCEM - Décision - Le bouton fixer un rdv ne doit être visible que pour dcem
- SEJ-1206: Activation du nouveau rôle Consultation Locale Séjour
- SEJ-1137: Fix null pointer in titulaire object, replaced with get lodash
- SEJ-1201: Rajouter le bouton historique dans la page d'instruction DCEM/TVE
- ANTM-489: Message affiché lors de la sauvegarde de modification apportée à la fiche d'un usager dont l'état civil a été validé par l'OFPRA
- SEJ-1212: Agent - Afficher les dates de début et fin de validité pour autre que dcem
- TRV-462: Page instruction et décision : le lien < RETOUR redirige sur l'accueil
- SEJ-607: Agent - DCEM : Page de decision implementer valider ou rejeter decision
- ANTM-502: Tuile "Consultation Usager" - masquer l'alerte pour les utilisateurs non habilités SOP
- ANTM-500: Pages d'erreur non implémentées
- ANTM-466: Message d'erreur pour saisir l'entretien Dublin pour un mineur KO sur le nouveau portail
- ANTM-490: Problème de payload flux lors de la modification des langues comprises et langue d'audition à l'OFPRA
- SEJ-710: Page instruction - adresse
- ANTM-493: Bouton vue locale et globale qui ne devrait pas appraitre pour le gestionnaire national
- TRV-402: Mise en place de la barre de recherche et des filtres
- ANTM-488: Décision définitive - Pays exclus
- SEJ-689: Page instruction - information de la demande
- SEJ-714: TVE - Page d'instruction : Motif de la demande (cas remplacement d'un TVE en cours de validité pour un motif de perte, vol ou détérioration)
- SEJ-713: TVE - Page instruction : Motif de la demande (cas remplacement TVE en cours de validité ou arrivé à expiration)
- ANTM-497: Mode d'affichage des heures de l'AR en 12h au lieu de 24h

## [1.29.1] - 2021-10-21

- ANTM-492: Réafficher les champs Nom et Prénom du représentant pour un enfant dans un recueil familial

## [1.29.0] - 2021-10-18

- SEJ-1148: Masquage du nouveau rôle Consultation Locale Séjour
- TRV-447: ajout de la mise à jour du statut en cliquant sur le tableau des demandes
- TRV-427: Instruction - Mise à jour du statut agent Encadrant
- ANTM-453: Les flux inerec-usager.etat_civil.modifie et dna-usager.etat_civil.modifie passent en CANCEL quand on utilise le nouveau portail
- ANTM-474: Ecran de suivi des usagers SOP : ajout de filtres dans la recherche avancée
- ANTM-406: Retirer l'habilitation de gestion pour les GU SOP
- SEJ-995: FMPT - Absence des informations des enfants en charge
- TRV-429: Ajout d'un panel des conteact dans l'instruction
- SEJ-687: TVE - Page d'instruction : Observations du demandeur
- SEJ-416: Ajout d'une nouvelle habilitation Séjour
- SEJ-964: FAMPT - Instruction KO si l'accueillant est inconnu de l'ANEF
- SEJ-601:[AGENT] DCEM - Page d'instruction : Situations particulières
- SEJ-729: DCEM - Adapter la page d'instruction

## [1.28.0] - 2021-10-13

- TRV-481: Décision - Prise de décision sans validation des changements
- ANTM-449: Gestion des erreurs pour un numéro étranger de moins de 10 caractères KO
- SEJ-612 : DCEM - Page d'instruction : Rechercher l'identité approchante
- TRV-439: Instruction ajout du bouton enregistrer quiter
- TRV-455: CDS état civil : message d'erreur bloquant inadapté sur la validation de la demande
- ANTM-444: Demande d'asile - Case à cocher non alignée avec son texte
- SEJ-566: DCEM - Page d'instruction : Informations de la demande (hors données du mineur)
- TRV-449: CDS état civil : supprimer le contrôle sur les champs "Prénom"
- ANTM-440: Ajustement sur les champs nom et prénom du représentant pour les MNA et le champ personne morale pour les non MNA
- SEJ-597: DCEM - Page d'instruction : contrôles sur le n° étranger du mineur
- ANTM-360: Modale signalement & Enregistrement en BDD : Gestion du signalement multiple
- ANTM-447: Ne pas proposer le choix "Adresse inconnue" sur la création/modification d'un site
- TRV-445: CDS Adresse - Disparition des données connus après validation de l'instruction
- ANTM-433: Saisie de l'adresse inconnue
- SEJ-994 : création de la pioche DCEM-TVE
- TRV-419: Instruction - Gestion de la demande de complément document manquant
- TRV-325: ajout du bouton enregistrer quitter dans la page de demande de changement decision
- ANTM-302: Réceptionner l'AR de traitement par l'OFPRA

## [1.27.0] - 2021-09-30

- TRV-433: Instruction : Champ "Date de naissance" et "Pays de naissance" incorrects
- NAT-582: faille à la récupération des pièces jointes
- ANTM-431: [Recueil nouveau portail] Bloquer la saisie du n° étranger à 10 caractères
- TRV-326: Ajouter le lien "Réaffecter"
- ANTM-171: PDF RDV - usager seul et mention "Chez"
- TRV-422: Instruction - Gestion du formulaire
- ANTM-306: Ecran de suivi des usagers SOP : écran accueil (extraction CSV)
- ANTM-420: Anomalie affichage détail usager SOP
- SEJ-604: [AGENT] DCEM - Page d'instruction : Adresse
- ANTM-121: Liste des recueils - Message erroné quand pas de résultats en GU/RGU
- ANTM-276: Faute d’orthographe sur la bannette informations filtre
- ANTM-413: Entretien Dublin - Ajouter un document - Animation de chargement ne s'arrête pas
- ANTM-364: Modale "Validation état civil" : confirmer le rattachement d'un mineur à un parent non connu de la brique Asile
- ANTM-407: SOP - Ajustement textes
- ANTM-368: Ecran de suivi des usagers SOP : écran accueil (recherche simple + avancée)
- ANTM-380: Message bloquant pour saisir le mineur en type de procédure "Dublin"
- ANTM-305: Ecran de suivi des usagers SOP ecran fiche detail donnees usager

## [1.26.0] - 2021-09-23

- ANTM-363: [Mineur rejoignant] Affichage du champ « N° étranger du représentant » (nouveau portail)
- ANTM-391: Modifier les messages d'erreur si le parent rattaché est en procédure Dublin
- ANTM-396: Accéder à la fonctionnalité "Signaler un OP" pour les DA et les BPI
- ANTM-393: Retrait de l'habilitation de gestion pour les partenaires
- ANTM-375: Ecran de suivi des usagers SOP : écran fiche détail (données DA)
- SEJ-565: DCEM - Ajouter la thématique DCEM
- ANTM-366: Ecran de suivi des usagers SOP : écran accueil (accès + contenu)
- SEJ-732: [Agent] DCEM - Créer tous les nouveaux statuts

## [1.25.2] - 2021-09-20

- TRV-392: CDS - Mettre en place un contrôle sur les habilitations
- SEJ-971: PROD Etudiant - PT Disparition du bouton 'Valider la décision' - Profil Encadrant & Instructeur Décideur
- SEJ-894: Duplicata  : taxe et droits
- TRV-394: Correctif du tableau de changement de situation

## [1.25.1] - 2021-09-13

- SEJ-916: Duplicata - recuperation des libelles agdref

## [1.25.0] - 2021-09-09

- TRV-370: Corriger l'adresse envoyé après l'instruction
- TRV-322: bug cloturer la demande
- ANTM-361: Modale signalement - Permettre de modifier service a l origine du signalement
- ANTM-377: Ecran de suivi des usagers SOP : écran fiche détail (socle technique)
- TRV-320: Correctifs de la page de décision
- ANTM-353: Diverses problématiques sur gestion des habilitations
- SEJ-875: Duplicata - Justificatif Photo Deteriore et date de vol manquant
- SEJ-914: DUPLICATA - Ajout justificatif signature portail agent
- TRV-359: Correctif page d'instruction (etat-civil)
- TRV-323: Correctifs Page d'instruction
- TRV-321: Revert ticket TRV-243
- SEJ-893: Duplicata - Correction du scroll en cas d'erreur sur page de décision
- SEJ-648: VISITEUR - Motif de séjour - Assurance maladie : corriger le texte
- TRV-296: PROD - Fix Cumul de critères de recherche ("utilisateurs actifs")
- TRV-324: Correctifs Tableau d'affichage agent
- SEJ-392: FAMPT - verification date demandeur n'est pas superieure a date accueillant
- SEJ-476: DCEM/TVE Composant Enfant mineur bénéficiaire
- SEJ-759: Correction du numéro d'ordre transmis à AGDREF
- ANTM-372: Restituer alerte sur suivi dossier du parent ayant un mineur rejoignant en procédure Dublin
- TRV-221: Décision - Affichage état-civil

## [1.24.0] - 2021-09-01

- ANTM-371: Restituer alerte sur suivi dossier du mineur rejoignant en procédure Dublin
- TRV-221: Décision - Affichage état-civil
- SEJ-479: Creation du composant DonneesConnuesTitulaireComponent
- TRV-141: Instruction - Affichage des informations du changement de l'usager "état civil"
- SEJ-748: Signalement/Duplicata: Le relaod de la déclaration est mal fait aprés le click de "Reprendre instruction"
- SEJ-747: [DUPLICATA/SIGNALEMENT]: Fix CSS pour les boutons en bas de la page Instruction/Décision
- SEJ-757: Duplicata et Signalement : espacer les différents champs
- SEJ-749: Signalement/Duplicata: Supprimer le bouton "Prendre une décision négative"
- ANTM-333: Restituer l'alerte du signalement dans la tuile "Consultation Usager"
- ANTM-330: Enregistrer le signalement en BDD dans la fiche usager
- TRV-147: Gestion du bouton "clôturer la demande"
- ANTM-311: Tuile DA - Restituer le motif de décision
- ANTM-329: Modale "Signaler un OP"
- ANTM-300: Accéder à la fonctionnalité Signaler un OP
- SEJ-696: Signalement - Implémenter les boutons du bas de page sur la page de décision
- SEJ-673 : DUCPLICATA - appel du flux AGDREF à l'ouverture de la demande
- SEJ-579: Signalement/Duplicata: implementer justificatifs en readonly
- SEJ-511: Erreur dans la console lors d'une instruction
- ANTM-334: PROD - Possibilité de sauvegarder un entretien dublin avec des états traversés vides
- SEJ-573: Signalement/Duplicata: implementer boutons bandeaux
- SEJ-513: [Agent] Signalement - Compléter le contenu de la page de décision
- SEJ-672: Duplicata - finaliser les actions d'instruction
- TRV-267: Séjour - Accueil : harmoniser les différentes pioches
- SEJ-653: Duplicata / signalement : adapter les règles de gestion des boutons bas de page sur la page d'instruction
- SEJ-578: Duplicata - Implémenter les boutons du bas de page sur la page de décision

## [1.23.0] - 2021-08-16

- TRV-273: fix réinitialisation de mot de passe
- SEJ-632: Visiteur - Type du titre de séjour pour une demande de renouvellement de CRA
- SEJ-628: PT Membre famille, erreur "Vous devez être affecté à cette demande pour réccupérer les informations de l'acceuillant"
- TRV-144: [Instruction]- Gestion du changement de site/agent sur une demande
- TRV-243: Contrôle accès demande de changement - usager vlsts
- SEJ-651: VISITEUR - Etape 4 & étape 5 : absence des éléments LPF
- SEJ-407: Signalement - Justificatifs perte, vol, deterioration
- ANTM-299: Création des habilitations pour SOP
- TRV-11: Récupération de la liste des demandes de changement
- SEJ-665: Duplicata - Finaliser afficher et instruire l'accordéon Motif de la demande
- SEJ-585: Duplicata - intégrer les declarations PVD aux listes de demandes des bannettes
- SEJ-666: correction du décalage sur la date de declaration dans le motif de la demande
- SEJ-457: Duplicata/Signalement - creation du composant générique details adresse
- SEJ-408: Duplicata - afficher et instruire l'accordéon Motif de la demande
- SEJ-489: Duplicata - Compléter le contenu de la page de décision
- TRV-148: Instruction - Bouton "valider l'instruction" changement adresse
- ANTM-317: [Demande d'Asile] Erreur de gestion Parents / Enfants sur l'ATDA (nouveau portail)
- TRV-251: demande de changement : Correction durée du titre statut actuel
- SEJ-598: créer un composant générique état civil readonly
- TRV-195: Décision - Affichage des éléments décisionnels
- SEJ-620: Correction de la récupération de la demande dans le portail Agent
- TRV-197 : Instruction - Bouton "demander un complément" changement adresse
- ANTM-245: Rapatrier la génération des ATDA côté backoffice
- SEJ-548: Duplicata/Signalement - créer le composant Infos Contact en lecture seule et l'intégrer dans la page
- SEJ-590: Duplicata/signalement : Implémenter les boutons bas de page sur la page d'instruction
- TRV-248: Modification du nom du champs type du changements en type_changements
- SEJ-454: Duplicata/Signalement - créer le composant Observation demandeur en lecture seule et l'intégrer dans la page
- SEJ-504: PT : dans l'onglet LPF, absence des informations concernant l'enfant à charge
- TRV-139: Ajout le nombre des demandes de changement par bannette et dans la pioche “demandes de changement”
- SEJ-596: Duplicata / signalement : refactorer les pioches DUP/SIG et démarrage des déclaration A_TRAITER
- SEJ-429: Duplicata - Creation du motif de duplicata
- SEJ-488: Signalement - Creation du motif de signalement
- SEJ-582: Duplicata / signalement : Initier la page Décision
- TRV-142: Instruction - Affichage des informations du changement de l'usager "adresse"
- SEJ-591: Nouvelle collection pour les déclarations PVD
- SEJ-569: Duplicata / signalement : Réorganiser le bandeau des écrans d'instruction et décision

## [1.22.0] - 2021-07-21

- SEJ-529: PT Membre famille, erreur "Vous devez être affecté à cette demande pour réccupérer les informations de l'acceuillant"
- TRV-140: Instruction - Affichage d'une demande de changement
- TRV-194: Décision - Affichage d'une demande de changement
- ANTM-133: Ecart sur AtDA au niveau de l'autorité de délivrance en édition GD
- SEJ-546: Duplicata / Signalement - Initier Page Instruction Declaration Pdv
- SEJ-487: Duplicata / Signalement - Initier les pioches
- ANTM-56: Mise à jour référentiels motif RDV et motif annulation recueil
- TRV-138: Ajout de la pioche changement de situation
- SEJ-399: Visiteur - Afficher/instruire les justificatifs de l'accordéon RESSOURCES
- SEJ-308: Visiteur - Adapter la page de décision

## [1.21.0] - 2021-07-07
- SEJ-499: ANEF "Pref Ultra-marines" problèmes liés à la date de naissance des usagers
- TRV-176: Filtre utilisateur actif/inactif
- TRV-226: Message inadapté sur la page de triage + corrections wording
- SEJ-508: DUPLICATA - Mettre à jour les thématiques
- SEJ-307: Afficher/instruire les justificatifs de l'accordéon MOTIF_VISITEUR
- SEJ-494: VISITEURS créer la pioche
- ANTM-151: Look&feel N°1 : optimisations majeures
- SEJ-495: VISITEURS - Mettre à jour la thématique
- SEJ-469: FAMPT - Validation de l'instruction impossible
- SEJ-396: Développer les champs de l'accordéon Ressources
- SEJ-306: Développer les champs de l'accordéon MOTIF_VISITEUR

## [1.20.2] - 2021-06-24

- ANTM-278: Données contentieux non sauvegardées en base

## [1.20.1] - 2021-06-23

- SEJ-434: FAMPT - Impossible de valider l'adresse pour le rappatriement du dossier
- SEJ-469: FAMPT - Validation de l'instruction impossible

## [1.20.0] - 2021-06-09

- ANTM-252: Dublin - Date Notif Accord implicite non sauvegardée en BDD
- SEJ-240: Créer une extraction des demandes avec décision favorable pour fabrication des titres de séjour
- SEJ-414: PTINV Radio bouton affiché à tort
- SEJ-319: Problème de caractères et montant ressources non visible
- SEJ-394: PTINV Créateur d'entreprise : la valeur des champs "origine des ressources" n'est pas récupérée
- SEJ-126: PTART adapter la page de décision
- SEJ-284: PTINV créateur d'entreprise étape 2 : incohérence sur info demandée
- SEJ-94: Développer les champs de l'accordéon MOTIF_PTART
- SEJ-240: Créer une extraction des demandes avec décision favorable pour fabrication des titres de séjour

## [1.19.0] - 2021-06-02

- TRV-182: Mise à jour du guide utilisateur agent
- ANTM-136: Modale d'alerte de sauvegarde affichée à tort en lecture seule pour accès à DA depuis Dublin
- ANTM-222: Le GD ne doit pas pouvoir modifier la tuile DA
- ANTM-232: Double chargement de page suite à la clôture d'une DA
- ANTM-149: Bouton retour
- ANTM-139: Consulter la convocation - séparation des prénoms
- ANTM-140: Consulter la convocation - n'afficher que les enfants demandeurs ou présents au moment de la demande
- ANTM-142: Consulter la convocation - mauvais affichage du nombre d'enfants
- TRV-80: Gestion du référentiel thématique
- ASL-128: PRD 45 flux declaration_fuite vers DNA absent
- ART-18: Changelog - Nouvelle règle d'écriture
- ANTM-218: Tuile DA - Impossible d'éditer le PDF DA sans avoir sélectionné une langue
- ANTM-146: Les attestations ne se génèrent plus suite à un renouvellement

## [1.18.3] - 2021-05-27

- SEJ-372: Entreprise innovante instruction du justificatif caractère innovant
- SEJ-370 : FAMPT : Internal Server Error quand agent non affecté sur la demande
- SEJ-366: Justificatif affiché à tort sur la page récap et sur le portail agent
- SEJ-380 : Erreur 500 sur l'appel de l'API detenteur PT
- SEJ-376: FAMPT Cas conjoint Informations sur le détenteur saisies par l'usager non affiché dans motif de séjour
- SEJ-369 : Supprimer requête info accueillant pour formulaire autre que fampt

## [1.18.2] - 2021-05-21

- SEJ-367: Fix d'un champ mal renseigné accordéon PTINV
- SEJ-256: FAMPT - Contrôles de recevabilité cohérence titre séjour accueillant
- SEJ-278: FAMPT - Contrôles de recevabilité Durée de validité du titre - partie 1
- SEJ-116: FAMPT - Contrôles de recevabilité Cohérence titre de séjour de l'accueillant
- SEJ-329: fix le champ origine des ressources N/A
- SEJ-364: PTINV Mandataire social - Date de fin de contrat non affiché pour un CDD
- SEJ-356: Toutes procédures - Corriger l'index du mois des champs date
- SEJ-358: PTRI - étape 2 : Information complémentaire obligatoire
- SEJ-127: FAMPT adapter la page de décision
- SEJ-273: creer composant générique infos connues détenteur pt
- SEJ-347: Évolution - Mettre à jour le montant de rémunération brute annuelle pour certaines TP
- SEJ-95: Afficher/instruire les justificatifs de l'accordéon MOTIF_PTART
- SEJ-321: FAMPT - Impossible d'intervenir sur les justificatifs du bloc Motif de séjour

## [1.18.1] - 2021-05-17

- **Séjour** SEJ-266: Vérification d'orthographe inadaptée sur les champs de saisie
- **Séjour** SEJ-205: développer les champs de l'accordéon  MOTIF_FAMPT
- **Séjour** SEJ-206: Afficher les justificatifs MOTIF_FAMPT
- **Séjour** SEJ-310: PTINV faute de frappe sur un label

## [1.18.0] - 2021-05-12

- **Asile** ANTM-172: Ne pas afficher le conjoint par défaut dans l'entretien Dublin
- **Séjour** SEJ-268: Onglet Motif de Séjour : le texte dépasse le cadre attendu
- **Transverse** TRV-80: Gestion du référentiel thématique
- **Asile** 128: PRD 45 flux declaration_fuite vers DNA absent

## [1.17.0] - 2021-04-30

- **Séjour** SEJ-258: PTSQ Ajouter justificatif Attestation Employeur pour Primo
- **Asile** ANTM-185 : Mise à jour des références CESEDA dans la liste des motifs de qualification
- **Asile** ANTM-22: Migration du service d'appel au FNE + modale de recherche d'identité
- **Séjour** SEJ-232: fix lien retours toutes les demandes
- **Asile** 21: Migration de la page selection de rdv
- **Séjour** SEJ-202: Corriger le référentiel de taxe par titre
- **Sejour** 8110: Afficher/instruireles justificatifs de l'accordéon MOTIF_PTINV
- **Séjour** SEJ-123: Adapter la page décision PTINV
- **Séjour** 8104: implement mandataire fields ptinv
- **Séjour** SEJ-235: PTSQ - Demande d'un usager avec visa : copie du visa non restitué
- **Sejour** SEJ-125: adapter la page de décision PTRI
- **Séjour** 228: Modifier le montant minimum du salaire brut PTSQ
- **Séjour** SEJ-234: PT - Impossible de valider une demande lorsque célibataire
- **Séjour** SEJ-236: PT - L'adresse n'est pas saisie automatiquement lors de l'ouverture d'une demande
- **Transverse** TRV-113: Gestion du changement de mot de passe
- **Transverse** TRV-111: Bug fix: retirer le droit d'ajouter les rôles gest séjour depuis admin nat
- **Asile** 125: Fix de la page blanche au clic sur le lien de DA des fiches usagers
- **Asile** 130: Fix de la page blanche au clic sur le lien de DA Dublin des procédures Dublin
- **Asile** 145: Fix de l'accès aux DA pour les gestionnaires nationaux
- **Séjour** SEJ-177: Le pays de l'union n'est pas restitué
- **Séjour** SEJ-190: Ajouter informations enfants à charge dnns l'instruction PT
- **Séjour** SEJ-204: ANO fix l'habilitation d'agent du bloc motif sejour PTSQ
- **Transverse** TRV-75: bug fixes: gestion des thematiques
- **Séjour** SEJ-194: PTSQ PTCQ Champs trop court
- **Séjour** 124: Adapter page decision PTCH

## [1.16.0] - 2021-04-21

- **Transverse** TRV-34: ajout de la gestion des pioches par thématiques
- **Séjour** 07: Afficher justificatifs motif séjour PTRI
- **Transverse** TRV-89: correction bugs dans l'interface profil utilisateur
- **Séjour** 8107: creation des champs de l'accordéon PTINV
- **Transverse** TRV-104: ajout du libellé du type document FNE
- **Transverse** TR-52: Affichage des informations récupèré via l'appel FNE
- **Transverse** TRV-97: Retour plage de rendez-vous
- **Séjour** 8168: Afficher/instruire les justificatifs de l'accordéon MOTIF_PTCH
- **Séjour** 7865: Transfert de demande : limiter les sites en fonction du formulaire de la demande

## [1.15.0] - 2021-04-08

- **Transverse** TRV-87: fixer la gestion  des utilisateurs avec des différents sites
- **Transverse** TRV-85: ajout du rôle consultant IGA
- **Asile** 18: Migration de la modale "Modifier l'adresse" de la fiche usager
- **Transverse** TRV-81: corrections bugs liés à l'interface plages-rdvs
- **Asile** 20: Migration des pdf convocation au rdv
- **Transverse** TRV-77: Mise à jour du guide utilisateur agent
- **Transverse** 8173: Gestion de la redirection des pages migrées
- **Sejour** 8104: implement motif ptinv fields
- **Asile** 19: Migration de l'impression du recueil
- **Transverse** TRV-53: Récupération des enfants lors de la consultation d'usager
- **Transverse** TRV-72: Suppression de la tuile consultation FNE
- **Séjour** 77: PTSQ Adapter la page de décision
- **Asile** 17: Migration de la modale "Transférer l'usager"
- **Asile** 25: Migration de la consultation de la convocation
- **Transverse** TR-49: Page de réinitialisation du mot de passe, anomalie popin
- **Asile** 7710: Migration de la re-prise de rdv
- **Séjour** 8106: Développer les champs de l'accordéon MOTIF_PTCH
- **Transverse** TRV-63: correction des routes de la navbar
- **Sejour** 67: Adapter la validation de l'instruction
- **Séjour** 8112: Afficher/instruire les justificatifs des accordéon EC_PT et MOTIF_PTSQ
- **Asile** 6612: Migration de la page formulaire de premier accueil
- **Transverse** 7673: Attribuer une thématique aux rôles agent "Séjour"
- **Asile** 6981: Migration de la fiche usager
- **Transverse** 50: Correction anomalie message succès création d'un agent
- **Asile** 6610: Migration de la liste des dossiers

## [v1.14.1] - 2021-04-01

- **Asile** 126: Fix de l'affichage des enfants sur l'attestation de DA des parents

## [v1.14.0] - 2021-03-22

- **Séjour** 8461: Débloquer la validation de l'instruction
- **Dublin** 8339: PRD Idf - Création d'un 2ème champ email
- **Asile** 38: Filtre de la recherche standard KO
- **Asile** 8445: Migration - consultation telemofpra
- **Asile** 8431: Bouton "Editer une attestation" dans fiche DA pour GD ne doit pas apparaître
- **Transverse** 8456: Modification affichage des informations de l'usager
- **Transverse** 8441: corriger les permissions du consultant Immi Pro
- **Séjour** 8273: Développer les champs de l'accordéon LPT_PT
- **Séjour** 8455: Rectification de la visualisation de la liste de demandes
- **Séjour** 8303: Améliorer l'affichage du tableau "Liste Des demandes
- **Séjour** 8272: Développer les champs de l'accordéon MOTIFS PTSQ
- **Asile** 8264: Evolution du PDF de l'AtDA
- **Transverse** 8063: Pop-in blocage de compte
- **Séjour** 8084: Développer les champs de l'accordéon EC_PT
- **Transverse** 8299: fix l'url de navigation vers la list des utilisateurs
- **Transverse** 8135: Ajout de l'historique des demandes et droit séjour
- **Transverse** 8300: Cumul message d'anomalie page de connexion

## [v1.13.0] - 2021-03-09

- **Transverse** 8225: Transverse - Page de login - gestion du FF authorize_navigator_to_save_password
- **Asile** 6294: Migration du service d'appel au FPR + modale
- **Asile** 8259: AtDA non disponible pour les GD (Dublin)
- **Séjour** 7944: Adapter la page d'instructions pour afficher les accordéons
- **Transverse** 8063: mise en place d'alias pour les imports
- **Transverse** 8132: consultation fne
- **Séjour** 8222: Refacto de la page instruction pour adapter les accordéons aux nouveaux formulaires
- **Séjour** 7837: Ajouter une colonne Formulaire dans la liste des demandes
- **Transverse** 8228: Page de login - Pop-in d'initialisation du mot de passe
- **Transverse** 8164: pop-in déconnexion pour inactivité

## [v1.12.0] - 2021-02-24

- **Asile** 8186: Recherche avancée - ajout des filtres "Département de domiciliation", "Orientation régionale", "Région d'orientation"
- **Dublin** - 8189: Liste des procédures Dublin - ajout de la pastille "ORIENTATION REGIONALE"
- **Asile** 8188: Recherche avancée - ajout des filtres "Orientation régionale", "Région d'orientation"
- **Transverse** 8227: Page de login - Pop-in de réinitialisation du mot de passe
- **Transverse** 6901: Page de login reinitialisation du mdp - session expirée
- **Transverse** 7938: Utilisateurs - Ajout d'habilitation rôle national
- **Asile** 6952: Migration édition PDF du planning GU
- **Asile** 6644: Migration planning GU
- **Transverse** 6900: Transverse - Page de login - pop-in mdp oublié
- **Séjour** 7924: Afficher le formulaire et la catégorie juridique dans le bandeau de la demande
- **Transverse** 8181: Immipro - Gestion Affichage de la liste complète dans le multi select de département
- **Transverse** 8183: fix l'affichage du calendrier en mode mensuel
- **Asile** 6727: Migration de la page edition d'AtDA (fusionner avec la tuile DA)
- **Transverse** 6917: affichage usager
- **Tranverse** 8023: ajouter les rôles ImmiPro

## [v1.11.0] - 2021-02-10

- **Asile** 8170: Erreur accès portefeuille des documents
- **Transverse** 8024: creation du site plateforme
- **Séjour** 7911: Cloturer une demande adresse trop long
- **Transverse** 7939: Migration plages rdv (affichage selecteur de site pour utilisateur support nat)
- **Asile** 7465: Messages d'erreur liés aux pushs arrêté de transfert
- **Transverse** 7789: Migration plages rdv (appliquer les modele )
- **Transverse** 7892: Montée de version Node10 vers Node12
- **Séjour** 8021: Délivrer ADP tant que la demande n'est pas à un statut semi-final ou final
- **Transverse** 7790: Migration plages rdv (suppression et gestion de la limite)
- **Transverse** 8123: Association d'un site sur un rôle administrateur local
- **Séjour** 8090: Correction impossibilité d'enregistrer une saisie lors d'une modification de décision
- **Transverse** 7786: Migration plages rdv (calendrier principal)
- **Transverse** 7788: Migration plages rdv (Migration des boutons configuration des modèles)
- **Séjour** 7990: Fix affichage de mauvaise page après retour sur la liste des demandes
- **Transverse** 6899: Transverse - Migration de la page login
- **Séjour** 7732: Indiquer que le jour et/ou le mois de la date d'entrée en France du demandeur sont inconnus
- **Asile** 7906: Migration de la page de recueil (2)

## [v1.10.0] - 2021-01-27

- **Transverse** 8093: Mise à jour du guide utilisateur Séjour
- **Séjour** 7985: Améliorer l'affichage du libellé du document additionnel ajouté
- **Asile** 6966: Migration de la modale des conditions d'entrée
- **Dublin** 7770: Onglet "Requête": Permettre la modification des champs EM et articles
- **Transverse** 6916: migration consultation usager, affichage tableau de résultat
- **Transverse** 7222: Migration Asile edition utilisateurs
- **Asile** 7348: Migration du Push de notification à l'upload du doc de l'arreté de transfert
- **Séjour** 7980: Fix le libellé d'impossibilité de prise d'empreintes

## [v1.9.0] - 2021-01-13

- **Asile** 6955: Migration du PDF édition d'attestation
- **Asile** 6965: Migration de la modale d'édition d'attestation
- **Séjour** 7855: Filtres avancés - Bannette Expiration proche - Retour demandes
- **Asile** 6951: Asile - Migration de la page du recueil
- **Asile** 6972: Migration du pdf d'edition de la demande d'asile
- **Séjour** 7844: Ne pas afficher le message de site AEF différent du site AGDREF quand l'instruction est validée
- **Transverse** fix-6898: Migration de la page d'accueil
- **Séjour** 7622: Permettre la pioche de la demande suivante en cas d'échec d'ouverture.
- **Asile** 6964: Migration de la modale de requalification
- **Séjour** 7280: Erreurs dans la console à la navigation sur le portail agent séjour
- **Transverse** 6898: Migration de la page d'accueil
- **Séjour** 7741: La première sélection du "Type de document" n'est pas pris en compte (modale "Documents additionnels")

## [v1.8.0] - 2020-12-16

- **Transverse** 6915: migration consultation usager
- **Asile** 6963: Migration de la demande d'asile (détail)
- **Transverse** 6918: Migration Asile Historique TelemOFPRA
- **Asile** 7740: Migration du component photo pour recueil, DA et usager
- **Transverse** 7500: Rechercher une demande via une saisie v2
- **Séjour** 7677: Filtres avancés sur le champs "Décision de" n'est plus conservé après avoir cliquer sur Retour à la liste des demandes
- **Séjour** 7728: Séjour - Collection usager - Rallonger les longueurs max des noms et prénoms
- **Transverse** 6920: Migration Asile Orchestrateur des échanges - Affichage v1
- **Asile** 6642: Migration de la liste des recueils
- **Séjour** 7709: En cas d'erreur lors de la pioche, le loader de bouton ne disparaît pas
- **Asile** 6980: Migration de la liste des usagers
- **Asile** 6522: Gestion des dates dans aef-portail-agent
- **Séjour** 7499: Conditions supplémentaire sur l’action "Valider l'adresse" et historiser l'action
- **Séjour** 7665: Perte de filtre sur la bannette "Expiration proche"

## [v1.7.0] - 2020-12-02

- **Séjour** 7725: Ajouter contrôles champs adresse sur "Valider l'adresse"
- **Dublin** 7623: Lier l'id de la procèdure dublin à l'id du recueil et à celui du numéro Eurodac
- **Séjour** 7612: passage de Node8 à Node10
- **Transverse** 6923: Migration Asile Orchestrateur des échanges - Affichage v2 - liste des boutons d'action
- **Séjour** 6824: Supprimer un document additionnel uploadé
- **Séjour** 5886: Ajouter un document additionnel sur la demande
- **Transverse** 6924: Migration Asile Orchestrateur des échanges - Affichage v2 - liste des messages
- **Dublin** 7590: Migration Asile/Dublin: Procedure Dublin Look & Feel
- **Asile** 6971: Migration du pdf d'extraction des decisions
- **Asile** 7696: Asile Ajout de la cloture pour l'onglet "demande à cloturer"
- **Transverse** 6910: Consommation de timbre - Consommation de timbre
- **Transverse** 6909: Consommation de timbre - Pop-in recherche FNE
- **Transverse** 6908: Consommation de timbre - Saisie du numéro Etranger
- **Dublin** 7445: Look & Feel
- **Transverse** 6924: Migration Asile Orchestrateur des échanges - Affichage v2 - liste des messages
- **Séjour** 7514: Perte des filtres à l'action "retour à la liste des demandes"
- **Séjour** 7618: Fix Pagination affichée KO lorsque je reviens à la liste via "Retour"
- **Asile** 6973: Migration de la clôture groupée des demandes d'asile
- **Asile** 7435: Ajouter multi PJ pour fuite, détention et recours de première instance

## [v1.6.1] - 2020-11-18
- **Séjour** 7644: Valider l'adresse / flux S12d "Mettre à jour l'adresse" et le site gestionnaire dans AGDREF

## [v1.6.0] - 2020-11-18

- **Séjour** 7550: Cas Titre - La récupération de la biométrie Visabio est lancée à la première ouverture
- **Séjour** 7641: Revert la 7342
- **Séjour** 6856: Saisir une adresse en outre mer
- **Séjour** 7488: Améliorer le retour à la liste des demandes
- **Asile** 7444: Router vers la conf nginx dans tous les liens des portails agent
- **Séjour** 6599: Afficher la modale "complément reçu"
- **Séjour** 7596: L'export de la liste des demandes ne fonctionne pas quand on filtre sans trier
- **Transverse** 6904: Migration Asile : création d'un nouveau utilisateur
- **Asile** 6726: Migration de la liste d'édition d'attestations
- **Séjour** 7543: Enregistrer l'agent qui a pris la décision ou clôturé la demande
- **Séjour** 7342: Empêcher la production d'une ADP quand le document de séjour en cours expire dans plus de 15 jours
- **Asile** 7446: Recherche sur liste: retour à la page 1
- **Transverse** 6921: Migration Asile Orchestrateur des échanges - Affichage v2 - Bannettes .
- **Dublin** 6649: Migration de la page procédure Dublin
- **Transverse** 7545: Rendre le spinner générique
- **Transverse** 6924: Migration Asile Orchestrateur des échanges - Affichage v2 - liste des messages

## [v1.5.0] - 2020-11-04

- **Séjour** 7551: Informer l'agent du nombre maximal de résultats dans l'export
- **Séjour** 7341: Renommer le bouton "Libérer la demande" en "Se désaffecter de la demande"
- **Séjour** 7411: Permettre de filtrer les lignes d'historique
- **Séjour** 7501: Exporter la liste des demandes
- **Séjour** 6812: Ajouter un bouton pour rouvrir l'instruction d'une demande
- **Séjour** 7308: Erreur dans la console lorsque je commence mon adresse par &
- **Dublin** 7427: Migration de la création de l'entretien dublin
- **Séjour** 7336: Afficher le nombre de résultats sur la liste des demandes

## [v1.4.0] - 2020-10-26

- **Séjour** 7274: État de la biométrie - Cas de l'indisponibilité Visabio non géré
- **Transverse** 6919: Migration Asile affichage des files du broker.
- **7441**: Dublin - Ajout du filtre "GU - Enregistrement" dans la recherche avancée des recueils
- **Transverse** 7401: Affichage du menu horizontal

## [v1.3.0] - 2020-10-21

- **Séjour** 7489: Menu Aide : changer le fichier guide utilisateur Sejour v2
- **Transverse** 4843: Rechercher une demande via une saisie
- **Transverse** 7401: Affichage du menu de navigation horizontal
- **Asile** 6976: Afficher le champ "département de domiciliation" dans le tableau des procédures Dublin + extraction
- **Dublin** 6654: Migration de l'entretien dublin dès lors qu'il existe déjà + édition du résumé et validation
- **Séjour** 7463: Perte du tri et de la pagination au clic surretour
- **Séjour** 7217: Ajouter des loaders Portail Agent (suite)
- **Séjour** 7481: Menu Aide : changer le fichier guide utilisateur Sejour
- **Séjour** 7345: Modifications historisation de l'enregistrement la demande
- **Séjour** 7442: Bannettes - Toutes les demandes apparaissent lorsque je trie la liste
- **Séjour** 7191: Améliorer l'action "retour à la liste des demandes
- **Asile** 6962: Migration de la page des demandes d'asile (liste)
- **Séjour** 6927: Ouvrir la demande en cliquant sur son numéro dans la liste
- **Sejour** 6630: Renommer l'attribut prise_empreinte_possible du champ biometrie de la collection usager
- **Séjour** 7409: Modification du format des dates de lecture dans l'historique
- **Dublin** 7351: Suppression de filtres dans la recherche avancée dublin
- **Séjour** 7335: Revoir les colonnes des bannettes (ajout d'une colonne "Numéro de demande")
- **Dublin** 6756: Migration de l'envoi de messages et de l'édition de PDFs

## [v1.2.0] - 2020-10-01

- **Séjour** 7344: Afficher la date d'entrée en France quand elle est vide
- **Séjour** 7338: Ajouter les guides utilisateurs sur la page Aide
- **Séjour** 7251: Fix le non affichage du bouton "Enrôler la biométrie" quand la demande est en lecture seule
- **Transverse** 7347: fix lien utilisateur visible à tort
- **Séjour** 7333: Informer l'agent du succès de la prolongation de l'instruction + loader sur le bouton "Valider" de la modale de prolongation
- **Séjour** 5175: Visualiser l'historique des actions sur la demande
- **Séjour** 7291: Les boutons "Enrôler la biométrie" et "Confirmer la décision" se dégrisent trop tôt
- **Séjour** 7259: Le message d'info de création du numéro étranger dans AGDREF ne s'affiche plus
- **Séjour** 6878: ADP - Modifier les contrôles de dates
- **Transverse** 6903: Migration Asile affichage liste des utilisateurs
- **Transverse** 6911: Migration de la page historique consommation de timbre
- **Séjour** 7281: Ajouter un motif de délivrance d'une ADP
- **Transverse** 6903: Migration Asile affichage liste des utilisateurs

## [v1.1.0] - 2020-09-24

- **Séjour** 7300: Bouton Valider instruction et Cloturer la demande provoquent une erreur au statut "Instruction en attente"
- **Transverse** 6907: Migration tableau de paramétrage
- **Séjour** 7289: Filtres - Les jours ne sont pas alignés avec les bonnes dates dans le calendrier
- **Séjour** 7233: le bouton "Valider l'instruction" qui reste grisé lorsque je ferme la modale "Impossibilité de prise d'empreintes"
- **Transverse** 6902: Migration de la page Aide
- **Séjour** 7199: Seul le picto relatif au dépot doit être rouge. Les autres pictos de la ligne restent noir
- **Dublin** 6655: Migration de la page requête
- **Transverse** 6906: migration menu paramétrage
- **Transverse** 7254: correction de l'ano des bannettes mes demandes


## [v1.0.1] - 2020-09-21

- **Séjour** 7290: Empêcher la validation de l'instruction lorsqu'on est en attente de l'etat cjn

## [v1.0.0] - 2020-09-11

- **Séjour** 7192: Appliquer une limite de taille sur les champs de saisie transmis à AGDREF à la validation de l'instruction
- **Séjour** 7219: Modifier le libellé du justificatif "Copie du titre de séjour ou du visa ou de l’attestation de validation du VLS-TS"
- **Séjour** 7218: Les boutons primaires sont grisés sur une demande après clôture de la précédente demande
- **Séjour** 6937: Afficher une modale si l'agent a coché impossibilité de prise d'empreintes
- **Séjour** 7190: Infos de la précédente demande non rafraîchies à l'ouverture
- **Transverse** 7169: correction de l'ano des bannettes mes demandes
- **Séjour** 7203: Décicion - Ne pas précocher la majoration
- **Séjour** 6924: Griser certains boutons sur les pages d'instruction et de decision
- **Dublin** 6651: Migration de la page de suivi
- **Séjour** 7189: L'attestation de décision est téléchargeable au clic sur le logo "ANEF | AEF"
- **Séjour** 7171:  Fix lenteurs relatives à l'affichage des bannettes
- **Transverse** 7165: libellé asile dans header et redirection en fonction du role
- **Séjour** 6674: Fix le non affichage du bouton "Enrôler la biométrie" quand la demande est en lecture seule
- **Séjour** 6888: l'instruction des justificatifs n'est pas sauvegardée lors d'une erreur AGDREF à la validation de l'instruc
- **Séjour** 7164: Les mauvais justificatifs s'affichent quand on accède à une demande en changement l'id dans l'URL
- **Séjour** 6936: Mauvais affichage du picto hors délai dans le bandeau de la demande
- **Séjour** 6967: Après avoir réinitialisé les filtres, la liste ne contient plus les bonnes demandes
- **Dublin** 6721: Migration de l'ajout de document
- **Séjour** 7144: Fix navigation au clavier sur le composant Etalab
- **Séjour** 7048: Améliorer la pop-up habilitations
- **Asile** 6257: Ajout d'une ancre d'erreur
- **Séjour** 6567: Fix Duplication des ressources saisies par l'usager au rechargement de la page instruction
- **Séjour** 6769: Filtre demande par date de dépôt et date d'expiration du titre non fonctionnel
- **Séjour** 6872: Des appels internet sont effectués au chargement des pages
- **Séjour** 7061: Afficher le délai d'administration sur les pages de la demande quand il est a zero

## [v0.11.0] - 2020-08-19

- **Transverse** 5286: Pop-in habilitations
- **Séjour** 5775: Afficher le compelement recu ephoto
- **Séjour** 6708: Ctrl recevabilité : Alerter l'agent à la confirmation de la décision
- **Séjour** 6938: Afficher un message si l'agent applique une majoration
- **Séjour** 6926: Masquer temporairement le bouton Transférer sur la page décision
- **Séjour** 6728: Ctrl recevabilité : Alerter l'agent à l'ouverture de la demande
- **Archi**: Mise à jour de la branche par defaut de l'ui-lib
- **Dublin** 6248: Ajout de nouveaux filtres dans la recherche avancée
- **Séjour** 6838: Le bouton "Reprendre l'instruction" qui est actif alors que je ne suis pas affecté sur la demande
- **Transverse** 6862: Affichage date format US sur calendrier filtres avancés
- **Dublin** 6656: Migration du portefeuille de documents
- **Séjour** 5999: Ajouter une bannette "Expiration proche"
- **Asile/Dublin** 6943: Correction de l'affichage des tableaux
- **Séjour** 5465: Calculer et afficher le délai d'administration
- **Transverse** 6412: Modifier la route pour les bannettes par défaut pour rôle séjour Central

## [v0.10.0] - 2020-08-05

- **Transverse** 6847: Modification de l'indicateur sbna lors d'une demande de complément
- **Transverse** 5622: Ajouter un pic et un filtre sur les listes de demandes “expiration proche”
- **Asile**: 6560: Migration de la page : Création/édition d'un site
- **Transverse** 6521: supprimer la surcharge de css sur pagination
- **Séjour** 6849: Fix - Demande bloquée si A Traiter + affectation manuelle
- **Séjour** 6855: Renommer le rôle "Central" en "Centrale"
- **Séjour** 6873: Correction affichage des pdfs dans la visionneuse du portail agent
- **Séjour** 6806: Compléter l'enum de valeurs du champ nature_titre (collection droit_document)
- **Dublin** 6562: Migration de la liste de procédure dublin
- **Transverse** 6688: Gestion de l'affichage des informations de l'agent connecté
- **Séjour** 6857: Documenter best practices Angular
- **Séjour** 5566: Permettre à l'usager de signaler des observations pour l'administration
- **Séjour** 6832: Afficher tous les messages d'erreur relatifs aux contrôles de recevabilité à l'ouverture de la demande
- **Séjour** 5243: Contrôles de recevabilité : Bloquer la demande à l'ouverture
- **Transverse** 6839: fix Pop-in "A propos"
- **Séjour** 6527: Appel CJN - le code erreur affiché ne correspond pas à celui remonté par AGDREF
- **Séjour** 6821: Calculer l'affichage biométrie après la mise à jour dossier à l'ouverture de la demande
- **Transverse** 5282: Pop-in "A propos"
- **Séjour** 6556: Retravailler l’affichage et l’activation du bouton libérer la demande
- **Transverse** 6786: Initier la demande d'attestation de prolongation avec une saisie de motif vide

## [v0.9.0] - 2020-07-22

- **Transverse** 6496: Réactualiser le nombre de demande dans la bannette
- **Séjour** 6794: Fix affichage du champ "Demande clôturée le"
- **Transverse** 5281: Menu du header et action de déconnexion
- **Asile** 6259: Suppression du breadcrumb et des marges du navigation layout
- **Séjour** 6784: Fix Impossibilité d'ouvrir une demande affectée à un agent
- **Transverse** 6427: Gestion des tris sur toutes les demandes
- **Asile** 5977: Migration de la page liste des sites
- **Séjour** 6712: Fix Impossibilité d'ouvrir une demande depuis la pioche quand elle est déjà affectée à un autre agent
- **Transverse** 6521: Pagination - Modifications de la numérotation des pages et nombre total de pages erroné
- **Séjour** 6515: Affichage du bloc Biométrie page instruction (BIOMETRIE V2) - état enrolement en cours ou invalide
- **Séjour** 6685-6600: Retravailler l'affichage des boutons "Réaffecter" et "Transférer"
- **Séjour** 6550: Ne pas effectuer le changement de statut automatique à l'ouverture d'une demande si je ne suis pas affecté dessus
- **Asile** 6299: Migration de la factory etalab et création d'un composant
- **Séjour** 6418: Afficher l'état de fabrication du titre
- **Transverse** 6700: Ajout du statut "Titre fabriqué" dans la bannette demande close
- **Séjour** 6534: Mettre en place un auth guard sur l'accès à la liste des demandes séjour
- **Séjour** 6659: Fix le montant de la majoration à appliquer qui ne s'enregistre pas au retour de la demande
- **Archis** 6733 : diverses améliorations sur le gitlab CI


## [v0.8.0] - 2020-07-01

- **Transverse** Fix - 6482: Gestion de l'affichage de la modale "Demande transférée".
- **Transverse** 6482: Gestion de l'affichage de la modale "Demande transférée".
- **Asile** 6163: Ajout de motifs de requalification PN vers PA depuis l'OFPRA
- **Séjour** 6618: Améliorer la gestion des référentiels referentiels.references_techniques et matrice_correspondance_titre
- **Séjour** Revert - 6534: Mettre en place un auth guard sur l'accès à la liste des demandes séjour
- **Séjour** 6534: Mettre en place un auth guard sur l'accès à la liste des demandes séjour
- **Séjour** 6635: Fix le non pré-calcul du montant des taxes
- **Séjour** 6621: Biométrie - Le radiobouton "Impossibilité de prise d'empreinte" ne doit pas être pré-coché à Non
- **Séjour** 6636: Fix Erreur "reference_reglementaire : champ invalide" au clic sur Retourner la demande
- **Séjour** 6620: "Enregistrer et quitter" ne doit pas modifier l'indicateur_biometrie_sbna
- **Séjour** 6624: Fix l'impossibilité de confirmer la décision d'une demande "Soumise à validation"
- **Séjour** 6554: Fix l'impossibilité de clôturer une demande "En attente de complément"
- **Séjour** 5444: Références réglementaires - Supprimer les référentiels et champs obsolètes
- **Transverse** 4857: Filtrer la liste des demandes via des critères
- **Séjour** 6583: Fix site de retrait écrasé au clic sur "enregistrer et quitter" si décision négative
- **Sejour** 6540: Delete useless code (6497-Mettre à jour l'indicateur biométrie sbna (BIOMETRIE V2)
- **Transverse** 6483: Gestion statut Transférée dans les bannettes
- **Séjour** 6576: Checkbox "demandeur contacté" grisée lorsque la demande passe en écriture
- **Séjour** 6583: Fix site de retrait écrasé au clic sur "enregistrer et quitter" si décision négative
- **Séjour** 6582: Le site de traitement affiché n'est pas le bon
- **Séjour** 6572: Afficher la date de la décision et la date de lecture de la notification de décision
- **Transverse** 6434: Refacto transmission SBNA (biométrie V2)
- **Séjour** 5650: Page décision : Calculer et enregistrer la référence technique et les attributs du titre délivré
_ **Séjour** 6570: Disparition de tous les boutons d'action de bas de page lorsque tous les justificatifs sont validés
- **Séjour** 6389: Séjour - Page décision : Etudiant - ajout de la catégorie juridique et des variables titre
- **Séjour** 6565: Lien d'upload du PDF de décision de rejet visible sur une décision positive

## [v0.7.0] - 2020-06-17

- **Transverse** 5656: Transférer une demande à un autre site
- **Séjour** 6498: Affichage du bloc Biométrie page instruction (BIOMETRIE V2)
- **Séjour** 6541: Fix enregistrement MOTIF_CLOTURE en cloturant la demande
- **Séjour** 6432: Mise a jour des valeurs de demande sejour formulaire
- **Séjour** 6512: Remplacer les commentaires de clôture par défaut par les vrais commentaires
- **Transverse** 6254: Migration de la recherche avancée
- **Transverse** 6398: Contenu de la banette 'Mes demandes'
- **Séjour** 6473: Bouton "Cloturer la demande" inactif au statut En attente de biometrie
- **Séjour** 6366: Séjour - Non-affichage des messages à la première ouverture de la demande
- **Séjour** 6454: Fix profil Instructeur voit le bouton "Confirmer décision" à tort et ne voit pas le bouton "Soumettre à validation" à tort
- **Séjour** 6177: Affichage d'une demande close
- **Séjour** 6474: Séjour - REGRESSION : Passage du statut Retour Valideur vers En cours ne se fait plus
- **Séjour** 6362: Séjour - Erreur 500 lors d’une erreur 302 AGDREF
- **Séjour** 5791: Afficher la "conclusion de l'instruction" et la "date de cloture"
- **Séjour** 5633: Afficher la date de la décision et la date de lecture de la notification de décision

## [v0.6.0] - 2020-06-03

- **Séjour** 6419: Suppression du site de délivrance + lien vers la demande_sejour
- **Séjour** 6326: Fix la possibilité pour un autre agent de modifier la date de prise de rendez-vous + le save de cette date
- **Séjour** 6316: Afficher les commentaires internes
- **Séjour** 6386: S17/032 : Transmisson decision negative - code erreur 200
- **Séjour** 6378: Fix le non-affichage du bouton "Retourner la demande" quand la demande est en lecture seule
- **Transverse** 6392: Affichage du nom/prénom de l'usager dans le tableau des demandes
- **Séjour** 6376: Supprimer le droit sejour.creer_compte
- **Séjour** 6274: Historiser les commentaires internes
- **Séjour** 6274: Historiser les commentaires internes
- **Séjour** 6176: Retravailler le workflow de la demande
- **Séjour** 6369: Amélioration l'apparence des modale réaffectation
- **Transverse** 6405: Supprimer le droit ADP si l'appel AGDREF est KO
- **Séjour** 6378: Fix le non-affichage du bouton "Retourner la demande" quand la demande est en lecture seule
- **Transverse** 6392: Affichage du nom/prénom de l'usager dans le tableau des demandes
- **Séjour** 6376: Supprimer le droit sejour.creer_compte
- **Séjour** 6338: Ajouter le wording relatif à la saisie des commentaires internes
- **Séjour** 6387: Permettre d'ouvrir la photo d'identité avec la visionneuse
- **Transverse** 6314: Correction du nombre d'affichage de nombre de demande et pagination
- **Transverse** 5704: Flux envoi prolongation instruction AGDREF
- **Séjour** 5245: Séjour Afficher le complément reçu
- **Séjour** 5917: Séjour Afficher la demande de complément
- **Séjour** 6357: Fix ouvrir une demande  et autoaffectation
- **Séjour** 6325: Fix les saisies obligatoires au clic sur "Mettre en attente biométrie"
- **Séjour** 6347: Fix le passage à "En cours" d'une demande au statut "Instruction en attente" et qui m'est affectée
- **Archi** 6388: Automatisation de la chaine DevOps CI avec GitlabCI
- **Séjour** 6349: Fix l'apparition du bouton "Mettre en attente biométrie" quand la biométrie est enregistrée
- **Séjour** 6234: Retirer le droit "Voir le bouton "Retourner la demande""
- **Asile** 6311: Ajouter des permissions et mise à jour des permissions utilisées dans séjour bannettes
- **Séjour** 6190: Notifier l'usager de la clôture de sa demande
- **Séjour** 6367: Fix le non-affichage du bouton d'actions (Fixer dépendance moment.js)
- **Transverse** 6310: Refacto session
- **Séjour** 6344: Corriger l'affichage de la page décision avec prolongation d'instruction
- **Séjour** 5879: Mettre à jour les rôles ("Instructeur", "Instructeur Décideur" et "Consultation")
- **Séjour** 6206: rectification affichage des radioboutons "Montant de la majoration à appliquer"
- **Séjour** 5174: Réaffecter une demande à un autre agent du site
- **Séjour** 6322: Fix l'affichage du bouton "Clôturer la demande"
- **Séjour** 6278: Fix l'oubli du save au clic sur "Suspendre l'instruction"
- **Séjour** 6250: Enregistrer l'état du casier judiciaire au clic sur "Enregistrer et quitter"
- **Séjour** 6276: Afficher correctement les boutons d'actions sur les demandes en lecture seule
- **Transverse** 5967: Gestion de la prolongation d'instruction
- **Séjour** 6319: Feature Flag "Simuler réponse CJN AGDREF"
- **Séjour** 6218: Retirer de la liste des rejets d'un document la valeur "Document manquant
- **Transverse** 5136: Afficher le nombre de demandes dans les bannettes
- **Séjour** 6209: Fix la mise à jour de indicateur_etat_cjn avant le contrôle à la validation de l'instruction
- **Séjour** 6155: Retravailler les regles daffectation et daffichage alouverture dune demande
- **Séjour** 6277: Fix bug de systeme de pioche à l'ouverture de la demande
- **Séjour** 5249: Clôturer une demande
- **Transverse** 5237: Ouvrir une demande via le système de pioche
- **Transverse** 6204: Gérer l'appel à agdref lors de l'ouverture d'une demande à traiter
- **Séjour** 5682: Enchainer les automatismes a l'ouverture de la demande
- **Transverse** 4669: Ouvrir une demande via le bouton d'action

## [v0.5.0] - 2020-04-22

- **Séjour** 6127: Enregistrer et afficher la date d'acquisition des empreintes d'AGDREF
- **Séjour** 6150: Reliquat 6046 - Contrôler l'accordéon des consultations sécuritaires "FPR/NSIS"
- **Séjour** 5620: Retourner la demande (ex retour valideur)
- **Séjour** 5248: Mettre une demande en attente
- **Séjour** 5790: Calculer le numéro métier de la demande
- **Transverse** 6138: Création du tableau des demandes séjour
- **Transverse** 4841: Consulter les bannettes de demandes
- **Séjour** 6139: Finaliser et corriger le développement de "Hébergé à titre gratuit"
- **Séjour** 5580: Communiquer la decision a l'usager
- **Séjour** 6161: Mise à jour inattendue de l'indicateur état cjn
- **Séjour** 6147: mettre a jour indicateur biometrie impossibilite prise empreinte non
- **Séjour** 6164: Sauvegarder la demande à la soumission à validation
- **Séjour** 5240: Demander un complément
- **Séjour** 5876: Corriger la date de début et de fin de validité de la décision
- **Transverse** 5854: Enregistrement des informations FPR/NSIS
- **Transverse** 5364: Actualisation des résultats FPR/NSIS à chaque modification de champs
- **Transverse** 5871: Affichage des résultats du FPR/NSIS
- **Transverse** 6005: Contrôle avant Appel création SBNA
- **Transverse** 6012: Mise en place de l'appel CJN
- **Séjour** 5618: Soumettre à validation
- **Séjour** 6141: Impossible d'enregistrer et quitter si la date de rdv de prise d'empreinte est non renseignée
- **Séjour** 6013: Permettre à l'agent de libérer la demande
- **Séjour** 5250: Mettre la demande en attente biometrie
- **Séjour** 5427: Conditionner l'affichage des boutons Valider l'instruction & Demander un complément
- **Séjour** 6046: Contrôles de surface à l'action "Valider l'instruction"
- **Séjour** 6094: Afficher correctement le message d'erreur à la création dans AGDREF

## [v0.4.0] - 2020-04-01

- **Séjour** 5292: Etape 3 - Modifications Déclaration des ressources
- **Séjour** 5692: Instruire les documents manquants
- **Séjour** 5438: Afficher la photographie et la signature (EPHOTO) sur la page Instruction
- **Séjour** 5714: Afficher l'état CJN sur la page d'instruction
- **Séjour** 6009: Message d'erreur generic en cas d'erreur service backend
- **Séjour** 6084: Ancrer en haut de page lorsque j'ouvre une demande
- **Séjour** 6086: Fix le message CJN mal orthographié
- **Séjour** 5563: Notifier la creation de la demande sur AGDREF
- **Séjour** 6076: Réafficher le footer
- **Séjour** 6034: Décision-Non correspondance entre le montant du timbre sur PSE et AGDREF
- **Séjour** 5841: Fix l'impossibilité de saisir un prénom avec espaces
- **Séjour** 6010: Dates enregistrées à J-1
- **Séjour** 4854: Instruire les justificatifs
- **Séjour** 5787: Consulter la date et le document de décision

## [v0.3.0] - 2020-03-04

- **Séjour** 6020: La demande ne s'ouvre pas à la première ouverture
- **Séjour** 6018: La demande s'ouvre toujours en lecture seule
- **Séjour** 5480: Mettre à jour le dossier à l'ouverture de la demande
- **Séjour** 5289: Transmettre les informations de l'usager à AGDREF à la validation formelle
- **Transverse** 5875: Gestion appel et affichage création identifiant AGDREF
- **Séjour** 5763: Masquer la liste des motifs rejet de l'étape de decision défavorable
- **Séjour** 5942: Mauvais affichage de la page décision lorsque je valide l'instruction
- **Séjour** 5961: Fix le portail agent ne s'affiche plus
- **Séjour** 5947: Performance des tests Angular
- **Séjour** 5932: Charger fixtures seulement en test
- **Séjour** 4846: Afficher les justificatifs à l'agent
- **Séjour** 5719: Instruction validée d'une demande est visible en lecture seule
- **Séjour** 5933: Mise à jour du readme installation du portail agent avec nginx

## [v0.2.0] - 2020-02-12

- **Séjour** 5404: Afficher en mode lecture seule l'instruction et la décision des demandes
- **Séjour** 5846: Afficher instructeur affecté sur la bannette de statut de demande (instruction, décision)
- **Séjour** 5285: Affecter instructeur à la demande au démarrage de l'instruction et restreindre en lecture seule les autres utilisateurs
- **Séjour** 5829: Correction pays non renseigné dans adresse usager a l'étape d'instruction de la demande
- **Séjour** 5593: Enregistrer la demande à la validation formelle

## [v0.1.0] - 2020-01-28

- **Séjour** 5279: Enregistrer et quitter l'examen formel
- **Séjour** 5466: Intégrer le référentiel des taxes et calculer le montant total de la taxe
- **Séjour** 5653: Implementer des controles de surfaces sur la page d'instruction
- **Séjour** 5830: Correction de bug sur la validation de l'instruction
- **Séjour** 5579: Ajout du composant d'upload de pieces jointes pour l'ajout de l'attestation de decision
- **Séjour** 5591: Confirmer avoir étudié l'année courante avant de remplir son motif
- **Séjour** 5662: Afficher bouton de confirmation de décision que lorsque l'examen formel est validé
- **Séjour** 5727: Retours démo (Pas de faux messages + site retrait en lecture seule + sélection nature avec
  durée maximum)
- **Séjour** 5594: Naviguer entre Instruction et Décision
- **Séjour** 5652: Rendre les champs modifiables/non-modifiables sur la page Instruction
- **Séjour** 5654: Sélection du site de retrait suite à une decision favorable
- **Séjour** 5581: Fix contrôle sur la saisie du nom d'usage
- **Séjour** 5403: Afficher le statut actuel du demandeur
- **Séjour** 5555: Renommer Examen formel en Instruction
- **Séjour** 5659: Page décision - Modifications ergonomiques
- **Séjour** 5239: Sauvegarder les "Eléments décisionnels" et finalisation de la décision
- **Séjour** 5455: Afficher le flag "Hors délai" sur la date de dépôt
- **Séjour** 5238: Afficher les "Eléments décisionnels" de la décision et intégrer le référentiel des refus
- **Séjour** 5588: Retirer l'étape de recherche d'identité approchante
- **Séjour** 4844: Compléter la page de l'examen formel avec tous les accordéons
- **Séjour** 5169: Créer la page de décision + bandeau + statut actuel du demandeur
- **Séjour** 5402: Créer la page de l'examen formel + bandeau
- **Séjour** 4850: Créer le layout du portail agent
- **Séjour** 5302: Envoi requête pour APIs de demande sejour avec données session agent
- **Séjour** 5283: Ajout des services front pour gérer la session agent et les features flags
- **Séjour** 5109: Integration de la lib-ui et modification de la liste des demandes a la charte
- **Séjour** 5258: Remettre le bouton `Editer l'attestation de prolongation d'instruction`
- **Séjour** 4939: Connecteur S06 - Mise en alias
- **Séjour** 5078: Workflow - Enregistrer le retour fait par le valideur
- **Séjour** 5147: Simuler la réaffectation et l'affichage de l'historique
- **Séjour** 5062: Workflow empecher instruction durant enquete
- **Séjour** 5110: Simuler les connecteurs à l'ouverture d'une demande
- **Séjour** 5149: Dessiner les blocs de la page d'instruction
- **Séjour** 5111: Créer la biométrie SBNA
- **Séjour** 4935: Workflow Faire une demande d'enregistrement des données biométriques, données enregistrées
- **Séjour** 4950: Editer l'attestation de prolongation d'instruction
- **Séjour** 4952: Workflow - Gérer l'irrecevabilité d'une demande
- **Séjour** 5010: Créer un service de gestion du titre des onglet
- **Séjour** 4930: Workflow cloturer une demande pour incomplétude renonciation action
- **Séjour** 4929: Workflow Cloturer une demande pour incompletude
- **Séjour** 4937: Workflow - Faire la revue d'identité
- **Séjour** 4926: Workflow - Faire et traiter retour valideur
- **Séjour** 4934: Mise en place du workflow de demande d'enregistrement de données biométriques
- **Séjour** 4928: Workflow - Réception de complément
- **Séjour** 4936: Workflow - Faire et traiter une demande enquete
- **Séjour** 4924: Reprendre une demande en cours
- **Séjour** 4925: Workflow - Enchainer la proposition d'une décision et l'enregistrement d'une décision pour un agent valideur
- **Séjour** 4927: Workflow - Faire une demande de complément
- **Séjour** 4983: Gestion des erreurs - cas générique
- **Séjour** 4912: Workflow - Enregistrer la décision
- **Séjour** 4911: Filtrer les demandes par bannettes
- **Séjour** 5002: Correction stratégie de routing
- **Séjour** 5001: Correction page blanche sur le portail agent en qualif
- **Séjour** 4893: Workflow - Valider formellement et proposer une décision
- **Séjour** 4668: Listage des demandes de séjour
- **Séjour** 4997: Downgrade du portail agent vers Angular 7
- **Séjour** 4988: Builds portail Agent vers Node 10
