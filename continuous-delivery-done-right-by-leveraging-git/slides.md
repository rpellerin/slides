% Continuous Delivery done right by leveraging Git 
% Romain Pellerin
% HumanTalks Compiègne 2016-05-10

-------------------------------------------

# I'm ONLINE

## @romainpellerin 

## [romainpellerin.eu](http://romainpellerin.eu)

### UTC, GI04 SRI

<style>
h1.title {
    font-size: 2.5em;    
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
test
</div>

-------------------------------------------

# Continuous

## Integration
## Delivery
## Deployment

![](assets/continuous.gif)

-------------------------------------------

<img src="assets/gite_fr.png" alt="Gite de France" class="w70"/>

-------------------------------------------

<br />

<span style="font-size: 3em; font-weight: bold; color: red;">
GIT != Github
</span>


-------------------------------------------

![](assets/calm.png)

-------------------------------------------

<img src="assets/xkcd.png" alt="XKCD" class="w50"/>

-------------------------------------------

# GIT =

## Directed

## Acyclic

## Graph

-------------------------------------------

# Reminder

<img src="assets/commits.png" alt="Commits" class="w90"/>

-------------------------------------------

# ID =

- Content +
- Author +
- Date +
- Log message +
- Previous commit

-------------------------------------------

# Branches and references 

<video autoplay loop src="assets/branches.webm" ></video>

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

-------------------------------------------

# Branches

## Create locally and remotely

```bash
git checkout -b <new-branch>

git push origin <branch>:<branch>
```

-------------------------------------------

# Branches

## Delete locally and remotely

```bash
git branch -d <branch>

git push origin --delete <branch>
```

-------------------------------------------

# Online platforms

## Github

## Gitlab

## Travis-ci

-------------------------------------------

# Pull requests

- Rebase
    - `git rebase origin/develop`
- Merge
    - `git merge origin/feature-x`
        - `--no-ff`
        - `--ff-only`
- Reset
    - `git reset --hard origin/xyz`

-------------------------------------------

# Commands

- bisect
- revert
- cherry-pick

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
