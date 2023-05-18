# Terminal
1. >dir     
    Använde jag för att kolla vad som fanns i mitt current directrory. Det var tomt...
5. >dir     
    Nu har jag använt mig av >code för att skapa en ny fil. Efter det använde jag mig utav >move följt av filens namn, mellanslag och sen mappen den ska flyttas till. 
6.  > 
    C:\Users\Threefiddy\Desktop\terminal-git-tutorial\newFolder>
7. >echo 
    "Hello from the terminal!" >> newFile.txt 
9. >
    Git används för att spara ner filer lokalt och skapa checkpoints i ditt arbete och din kod. Man kan t.ex. skapa förgreningar i sitt arbete för att säkerställa att ens nya kod inte ställer till det för huvudkoden. Detta kallas för en 'branch'.
10. >
    1. Modified - Modifierade filer betyder att filerna harändrats men ännu inte commitats till databasen.
    2. Staged - Stageade filer är i stadiet mellan 1 och 3 där de vid nästa commit kommer att inkluderas.
    3. Commited - Commitade filer är filer som har sparats och som nu lagras lokalt på i databasen.
12. >git init
    C:\Users\Threefiddy\Desktop\terminal-git-tutorial>git init
    Initialized empty Git repository in C:/Users/Threefiddy/Desktop/terminal-git-tutorial/.git/
13. >newFolder/ >> .gitignore 
    Jag använder mig av CMD främst för att min powershell inte riktigt fungerar som den ska och min erfarenhet med powershell = 0
14. >git add README.md 
    >git add .gitignore
15. >git status
16. >git commit -m "README file for the repository"
17. >
    En git branch används för att skriva kod som vid ett senare tillfälle ska fogas samman med stammen, 'main'. Detta är särskilt bra när det är flera utvecklare som jobbar på samma projekt då de skapar en miljö (branch) som var och en kan jobba i utan att påverka varandras arbete eller stammen, main.
18. >git branch newBranch 
    >git switch newBranch
19. >echo newBranch.txt >> newBranch
    >git add .
    >git commit -m "New file to the newBranch"
20. >git switch master 
    Filen newbranch syns inte när jag kollar min directory.

21. # README
22. This is my first GitHub repository and I'm training the use of **Git** and *GitHub*.
24. I'm also learning:
- HTML
- CSS
- JavaScript

# GitHub
27. >git remote add origin git@https://github.com/focusjuice/terminal-git-tutorial.git´
    >git remote -v
    För att se att min repo accepterades och var korrekt.
28. >rename *old name* *new name*
    Jag var dock tvungen att stänga ner mitt VSC då det störde processen.
29.
30.
