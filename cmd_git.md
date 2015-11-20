#Test
#git config --global user.name "Prenom Nom"
#					user.email "email"
#					color.ui auto
#git status 
#git diff
#git diff --word-diff
#git add fichiers...
#git diff --cached
#git commit


Variantes:

#git commit -m "Message"
#git commit fichiers
#git commit -a (all)
#=>le "add" est fait tout seul pour les fichiers suivis par git

revoir les commits:
#git show
#git log
#git log -p
#git log --stat --summary
#git log --oneline
#git log --oneline --graph --branches --tags --remotes --decorate

Communiquer avec le serveur distant:

envoyer les commits locaux -> distant:
#git push
#git status

recevoir les commits distants -> local
#git fetch
#git pull (fetch+merge)

exemple de commit typique:
https:://git.kernel.org
->projet git.git
	->log
		"daemon: plug memory leak"

#git add fichiers/ rm fichiers -> git commit

#git stash -> modif enregistrée dans le stash et retour à ancienne version
#git stash pop ->réapplique modif du stash dans espace de travail ->pile
#git stash show
#git stash drop
#git stash list

Branches:

#git branch nom ->* devant branche courante
#git checkout nom
#git merge nom -> commit de branche secondaire dans branche principale -> conflits possibles
#git branch -d nom -> supprime étiquette de la branche nom (doit êter reliée à branche principale)





