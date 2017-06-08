Changes in this repository.

Merged:
- https://github.com/aksonov/react-native-router-flux/pull/1497


To merge changes from other forks:

```
git remote add <fork author> git://github.com/<fork author>/react-native-router-flux.git
git fetch <fork author>
git rebase merge master <fork author>/<pull request branch>
git branch <local branch> HEAD
git checkout master
git merge <local branch>
git branch -d <local branch>
git push
```

Example:

```
git remote add psychoo118 git://github.com/psychoo118/react-native-router-flux.git
git fetch psychoo118
git rebase master psychoo118/master
git branch pull_request_1497 HEAD
git checkout master
git merge pull_request_1497
git branch -d pull_request_1497
git push
```

