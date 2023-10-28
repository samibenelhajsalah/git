------------------
##### Branches

| use |command |
|---|---|
| list all branches (local and remote) |git branch -a  |
|  update the local list of remote branches |  git remote update origin --prune |
|  update the local list of remote branches |  git remote update origin --prune |
|  delete local branch |  git checkout -b my_branch |

##### Change the name of a branch

| step |command |
|---|---|
| Rename your local branch |git branch --move branch_name branch_newname  |
| push to the remote server. This makes the renamed branch available |git push --set-upstream origin branch_newname |
| delete branch_name |git push origin --delete branch_name |

for more details see [git doc](https://git-scm.com/book/fr/v2/Les-branches-avec-Git-Gestion-des-branches), [vs code](https://code.visualstudio.com/docs/languages/markdown) and [framasoft](https://docs.framasoft.org/fr/grav/markdown.html)

##### Extension
- Graph: GitLens — Git supercha , Git Graph

##### Astuces
```
Utilisation de 'master' comme nom de la branche initiale. Le nom de la branche
astuce: par défaut peut changer. Pour configurer le nom de la branche initiale
astuce: pour tous les nouveaux dépôts, et supprimer cet avertissement, lancez :
astuce: 
astuce:         git config --global init.defaultBranch <nom>
astuce: 
astuce: Les noms les plus utilisés à la place de 'master' sont 'main', 'trunk' et
astuce: 'development'. La branche nouvellement créée peut être rénommée avec :
astuce: 
astuce:         git branch -m <nom>
```

