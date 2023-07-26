
walte@Walter MINGW64 ~
$ source .bash_profile

walte@Walter MINGW64 ~
$ cd d:

walte@Walter MINGW64 /d
$ cd Fi
Final-Git-Practice/    Fix_My_Code_Challenge/

walte@Walter MINGW64 /d
$ cd Final-Git-Practice/

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ vi services.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ add
warning: in the working copy of 'services.html', LF will be replaced by CRLF the next time Git touches it
[ft/bundle-2 db2bbce] Latest Update
 1 file changed, 12 insertions(+)
 create mode 100644 services.html
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 544 bytes | 544.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/bundle-2
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$

