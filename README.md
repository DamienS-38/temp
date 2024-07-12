# Mémo Git et GitHub
différence entre >Git et GithUB
    Git --> OpenSource: Versionning de code
    GitHub --> Plateforme hébergement

Ici et là

1er Enregistrement:

    echo "# temp" >> README.md
        git init
    git status
        git add README.md
    git status
   
    Si mess Erreur:
    git config --global user.name ”Damien”
    git config --global user.email ”damien.schaeffer@le-campus-numerique.fr”
        
        git commit -m "first commit"
        git branch -M main
        git remote add origin git@github.com:DamienS-38/temp.git
            git remote show origin
                * remote origin
                Fetch URL: git@github.com:DamienS-38/temp.git
                Push  URL: git@github.com:DamienS-38/temp.git
                HEAD branch: (unknown)	
        git push -u origin main (-u que la 1ere fois)


Modif ici


Modif sur un fichier

    -Faire une modif en local
    -git add . (Le '.' est pour add tout le répertoire - Ex: git add README.md)
    -git commit -m "message du commit" (Message de ce que tu as fait)
    -git push origin main (-u setupstream/ renseignement, pousser les modifs locales vers GitHub)
