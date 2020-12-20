Learned from https://stackoverflow.com/a/24577293

```sh
git checkout upstream-master && git pull && git subtree split --prefix=deconz --onto upstream-deconz && git checkout master
git rebase upstream-deconz

````
