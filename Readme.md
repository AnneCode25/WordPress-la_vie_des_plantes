Readme

# Migration de Site WordPress avec All-in-One WP Migration

Ce guide vous explique comment utiliser le plugin All-in-One WP Migration pour exporter un site WordPress depuis un environnement local et l'importer dans un nouvel environnement.

## Pré-requis

- Accès à l'interface d'administration de WordPress sur le site source et le site de destination.
- Le plugin All-in-One WP Migration installé sur les deux sites.

## Étapes pour Exporter le Site

1. **Installer All-in-One WP Migration sur le Site Source**
    - Connectez-vous à votre tableau de bord WordPress.
    - Allez dans **Extensions > Ajouter**.
    - Recherchez "All-in-One WP Migration".
    - Cliquez sur **Installer** puis **Activer**.

2. **Exporter le Site**
    - Allez dans **All-in-One WP Migration > Exporter**.
    - Cliquez sur **Exporter vers** et sélectionnez **Fichier**.
    - Attendez que le plugin prépare le fichier d'exportation.
    - Une fois terminé, cliquez sur le bouton de téléchargement pour télécharger le fichier `.wpress` sur votre ordinateur.

3. **Fournir le Fichier**
    - Transférez le fichier `.wpress` à la personne qui doit recevoir le site. Utilisez des services de partage de fichiers comme Google Drive, Dropbox, WeTransfer, etc.

## Étapes pour Importer le Site

1. **Installer WordPress sur le Site de Destination**
    - Assurez-vous que WordPress est installé et configuré sur le serveur ou l'environnement local de destination.

2. **Installer All-in-One WP Migration sur le Site de Destination**
    - Connectez-vous à votre tableau de bord WordPress.
    - Allez dans **Extensions > Ajouter**.
    - Recherchez "All-in-One WP Migration".
    - Cliquez sur **Installer** puis **Activer**.

3. **Importer le Fichier**
    - Allez dans **All-in-One WP Migration > Importer**.
    - Cliquez sur **Importer depuis** et sélectionnez **Fichier**.
    - Téléchargez le fichier `.wpress` fourni.
    - Le plugin importera le site. Cela peut prendre un certain temps selon la taille du fichier.
    - Une fois l'importation terminée, le plugin vous demandera de sauvegarder les permaliens.

4. **Régénérer les Permaliens**
    - Allez dans **Réglages > Permaliens**.
    - Cliquez sur **Enregistrer les modifications** pour régénérer les permaliens et assurer le bon fonctionnement des liens sur le site.

## Notes

- Assurez-vous d'avoir suffisamment d'espace de stockage et de ressources sur le serveur de destination pour gérer l'importation du site.
- Si l'importation échoue en raison de la taille du fichier, vous pouvez essayer de diviser le fichier ou augmenter les limites de téléchargement et de mémoire PHP sur le serveur de destination.

---

Ce guide devrait vous aider à exporter et importer facilement votre site WordPress en utilisant le plugin All-in-One WP Migration. Si vous rencontrez des problèmes, veuillez consulter la documentation officielle du plugin ou contacter leur support technique.
