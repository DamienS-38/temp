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
        git push -u origin main





Modif sur un fichier

    git add README.md

    git commit -m "Modif readMe"

    git push -u origin main
