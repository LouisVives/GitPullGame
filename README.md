Dit is de Git PullRequest Game

1. Commando om Git versiecontrol te initialiseren in een directory:git init
2. Commando om alle changes toe te voegen aan de commit:git add -A
3. Commando om alles toegevoegde changes te committen met als boodschap 'initial commit':git commit -m "initial commit"
4. Commando om https://github.com/MilanVives/testRepo.git als remote origing van onze repository toe te voegen:git remote add origin https://github.com/MilanVives/testRepo.git
5. Commando om al onze commits te pushen naar de remote origin master: git push -u origin https://github.com/MilanVives/testRepo.git
6. Commando om de status te controleren:git status
7. Commando om een nieuwe branch aan te maken met als naam 'feature-branch':git checkout -b feature-branch
8. Commando om te zien in welke branch men bezig is:git branch
9. Commando om te veranderen naar branch 'feature-branch':git checkout feature-branch
10. Je zit in de feature-branch. Met welke commando kan je alle wijzigingen toevoegen aan de master branch?:git merge new-branch
11. Je zit op branch feature-branch. Na het branchen is er op de master een nieuwe file aangemaakt nieuwefile.txt. Met welke commando kan je je branch updaten met de laatste nieuwe file?:git checkout master
