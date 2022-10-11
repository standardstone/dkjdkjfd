# git-1
## version control
It's essential to use a version control system for software development and other documentation

##  how to store information
storing data as snapshots and use Distributed methods
Modified working Directory ->Staged staging Area -> commit in git directory(Repository)

#Git cinfig: First-time setup
Git configurations are stored in three levels:

```
1. System level: --system option. Affects all uses and repositories on the system
   ex) git config -- sytem user.name "jungsuk"
2. Global(user) level: -- global option. Affects all repositories of a current user
ex) git config -- global user.name "jungsuk"
3. Local level: --local option. Specific to the current repository
ex) git config -- local user.name "jungsuk"
```
*Each level overrides values inthe prvious level:system->global->local

git config -- global user.name "jungsuk"
git config -- global user.email dsfnj12@gachon.ac.kr
git config --list
git config --list --show-origin
git config  user.name
show jungsuk





