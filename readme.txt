Pour installer le hook :

1. Copier le fichier pre-commit dans le dossier .git/hooks/
   cp hooks/pre-commit .git/hooks/pre-commit

2. Rendre le fichier exécutable :
   chmod +x .git/hooks/pre-commit

Le hook demandera à chaque commit si vous voulez créer le fichier suivi/commitInfo.txt.
