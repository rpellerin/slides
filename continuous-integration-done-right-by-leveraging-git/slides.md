% Continuous Integration done right by leveraging Git 
% Romain Pellerin
% HumanTalks Compiègne 2016-05-10

-------------------------------------------

# I'm ONLINE

## @romainpellerin 

## [romainpellerin.eu](http://romainpellerin.eu)

### UTC, GI04 SRI

<style>
h1.title {
    font-size: 2.3em;    
}
.title footer span {
    font-size: .8em;    
}
</style>

-------------------------------------------

<br />

<span style="font-size: 6em; font-weight: bold; color: white;">
GIT
</span>

![](assets/mind.gif)

<div class="notes">
On va plutot parler principalement de Git au lieu de continuous delivery.
</div>

-------------------------------------------

# Continuous

## Integration
## Delivery
## Deployment

![](assets/continuous.gif)

<div class="notes">
FAIRE DESSIN
</div>

-------------------------------------------

# Online platforms

## Github

## Gitlab

## Travis-ci

<div class="notes">
FAIRE DESSIN
</div>

-------------------------------------------

<img src="assets/gite_fr.png" alt="Gite de France" class="w70"/>

<div class="notes">
Prononciation
</div>

-------------------------------------------

<br />

<span style="font-size: 3em; font-weight: bold; color: red;">
GIT != Github
</span>

<div class="notes">
- Git système de versionning (logiciel)
- Github/Gitlab : plateforme web de services, en fait des server qui host des repo git distant + features autour
- On peut utiliser Git sans github. un peu installer un repo git sur son pc et donner l'accès à d'autres gens
</div>

-------------------------------------------

![](assets/calm.png)

<div class="notes">
Utilisez la ligne de commande (donc Linux) et pas d'outils graphiques (celui proposé par Github par ex)
</div>

-------------------------------------------

<img src="assets/xkcd.png" alt="XKCD" class="w50"/>

<div class="notes">
- C'est quoi Git ? Inventé par Linus Torvalds, le créateur de Linux, il y a dix ans.
- Version control system
- Remplace SVN
- Largement adopté
</div>

-------------------------------------------

# GIT =

## Directed

## Acyclic

## Graph

<div class="notes">
Fonctionne sur le principe d'un graphe orienté acyclique
</div>

-------------------------------------------

# Reminder

<img src="assets/commits.png" alt="Commits" class="w90"/>

<div class="notes">
- Commits = snapshot
- Add : crée un hash de tous les fichiers
- Commit : crée l'identifiant qui correspond au snapshot et à l'ensemble de ces hash
</div>

-------------------------------------------

# ID =

- Content +
- Author +
- Date +
- Log message +
- Previous commit

<div class="notes">
ID unique
</div>

-------------------------------------------

# Branches

<video autoplay loop src="assets/branches.webm" ></video>

<div class="notes">
- Branches = très simple avec Git, unlike SVN
- Branches = étiquettes vers un commit
- HEAD, tags = pareil
- Tracking branches are read only
- On peut revenir à n'importe quel commit ou en annuler comme on veut
</div>

-------------------------------------------

<img src="assets/workflow.png" alt="Workflow" class="w55"/>

<style>
div.sourceCode {
    /*background-color: rgba(238,238,238,0.5);*/
}
section > p:first-child {
    margin: 10px; 
}
.w55 {
    width: 55%;    
}
</style>

<div class="notes">
Workflow que j'ai adopté. Il en existe d'autre. Celui-ci est répandu. A vous de choisir.
</div>

-------------------------------------------

# Pull requests

- `merge`
    - `git merge origin/feature-x`
        - `--no-ff`
        - `--ff-only`
- `rebase`
    - `git rebase origin/develop`
- `reset`
    - `git reset --hard origin/xyz`

<div class="notes">

</div>

-------------------------------------------

# Commands

- `pull` (`fetch` + `merge`)
- `bisect`
- `revert`
- `cherry-pick`

<div class="notes">

</div>

-------------------------------------------

# Thanks

<img src="assets/uni.gif" alt="Workflow" class="w20"/>

<div style="color: gray">

### Further reading:
### [blog.romainpellerin.eu/continuous-integration.html](http://blog.romainpellerin.eu/continuous-integration.html)
### [blog.romainpellerin.eu/git-upgrade-yourself.html](http://blog.romainpellerin.eu/git-upgrade-yourself.html)

</div>
<br /><br /><br /><br /><br /><br />

<!--<span style="font-size: .7em; color: gray">Image credit : <a style="color: inherit" target="_blank" href="http://nvie.com/posts/a-successful-git-branching-model/">Vincent Driessen</a> & <a style="color: inherit" target="_blank" href="http://blog.osteele.com/posts/2008/05/my-git-workflow/">Oliver Steele</a></span>-->

-------------------------------------------

# Image/Video Credits

<div style="font-size: .6em">

- [http://imgur.com/DWrI2JY](http://imgur.com/DWrI2JY)
- [http://devopsreactions.tumblr.com/post/110800328581/continuous-delivery](http://devopsreactions.tumblr.com/post/110800328581/continuous-delivery)
- Logo "Gîte de France"
- [http://xkcd.com/1597/](http://xkcd.com/1597/)
- [http://codingdomain.com/git/partial-commits/](http://codingdomain.com/git/partial-commits/
)
- [http://www.gifbin.com/983296](http://www.gifbin.com/983296)
- [http://nvie.com/posts/a-successful-git-branching-model/](http://nvie.com/posts/a-successful-git-branching-model/)

</div>
