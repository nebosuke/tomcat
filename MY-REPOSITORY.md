# fix trivial problem branch for Tomcat 7.0.x

## How to merge changes on apache/tomcat repository

```
git remote add upstream https://github.com/apache/tomcat.git
git fetch upstream
```

```
$ git branch -a
* 7.0.x
  master
  remotes/origin/7.0.x
  remotes/origin/8.5.x
  remotes/origin/HEAD -> origin/master
  remotes/origin/fix_finalizer_close_recycled_response
  remotes/origin/master
  remotes/upstream/7.0.x
  remotes/upstream/8.5.x
  remotes/upstream/master
```

```
git merge upstream/7.0.x
```
