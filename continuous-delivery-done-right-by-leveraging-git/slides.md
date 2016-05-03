% Continuous Delivery done right by leveraging Git 
% Romain Pellerin
% HumanTalks Compiègne 2016-05-10

-------------------------------------------

# Hello, world!

## GI04 SRI, UTC

## _ 

## [romainpellerin.eu](http://romainpellerin.eu)


<style>
h1.title {
    font-size: 2.5em;    
}
.title footer span {
    font-size: .8em;    
}
</style>

-------------------------------------------

<img src="assets/gite_fr.png" alt="Gite de France" class="w70"/>

-------------------------------------------

# Continuous Delivery

![](assets/continuous.gif)

-------------------------------------------

<img src="assets/workflow.png" alt="Workflow" class="w55"/>

<style>
div.sourceCode {
    background-color: rgba(238,238,238,0.5);    
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

<video autoplay loop src="assets/create_b.mp4" ></video>

## Create locally and remotely

```bash
git checkout -b <new-branch>

git push origin <branch>:<branch>
```

-------------------------------------------

# Branches

<video autoplay loop src="assets/branches.webm" ></video>

## Delete locally and remotely

```bash
git branch -d <branch>

git push origin --delete <branch>
```

-------------------------------------------
# Thanks

<br />

<div style="color: gray">

### Further reading:
### [blog.romainpellerin.eu/continuous-integration.html](http://blog.romainpellerin.eu/continuous-integration.html)

</div>
<br /><br /><br /><br /><br /><br />

<!--<span style="font-size: .7em; color: gray">Image credit : <a style="color: inherit" target="_blank" href="http://nvie.com/posts/a-successful-git-branching-model/">Vincent Driessen</a> & <a style="color: inherit" target="_blank" href="http://blog.osteele.com/posts/2008/05/my-git-workflow/">Oliver Steele</a></span>-->

-------------------------------------------

# Credits

<div style="font-size: .6em">

- Gîte de France
- [http://devopsreactions.tumblr.com/post/110800328581/continuous-delivery](http://devopsreactions.tumblr.com/post/110800328581/continuous-delivery)
- [http://www.gifbin.com/983296](http://www.gifbin.com/983296)

</div>
