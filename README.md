# Git & GitHub - The FULL Course

A fast-paced course for getting up to speed with Git and Github

I'm also working on a feature
Just working on a feature

## sefull aliases
<details>
<summary>add all and commit</summary>

``` git ac <commit-name> ```  
to implement add the following line in to .gitconfig  
```ac = "commit -am"```
</details>
<details>
<summary>add all, commit and push</summary>

``` git acp <commit-name> ```  
to implement add the following line to .gitconfig  
``` acp = "!f() { git add -A && git commit -m \"$1\" && git push; }; f" ```
</details>