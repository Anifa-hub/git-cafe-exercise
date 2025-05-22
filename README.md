# git-cafe-exercise
User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (main)
$ git branch ft/new-feature

User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (main)
$ git checkout ft/new-feature 
Switched to branch 'ft/new-feature'

User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (ft/new-feature)
$ git add .

User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (ft/new-feature)
$ git commit -m ' changes on both menu pages'
[ft/new-feature e1e4253]  changes on both menu pages
 2 files changed, 2 insertions(+), 2 deletions(-)

User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (ft/new-feature)
$ git push
fatal: The current branch ft/new-feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/new-feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (ft/new-feature)
$ ^C

User@Anifa-hub MINGW64 /e/Code/git-cafe-exercise (ft/new-feature)
$ git push --set-upstream origin ft/new-feature
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 440 bytes | 146.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/new-feature' on GitHub by visiting:
remote:      https://github.com/Anifa-hub/git-cafe-exercise/pull/new/ft/new-feature
remote:
To https://github.com/Anifa-hub/git-cafe-exercise.git
 * [new branch]      ft/new-feature -> ft/new-feature
branch 'ft/new-feature' set up to track 'origin/ft/new-feature'.
