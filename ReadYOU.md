Some initial text - b4 any git action

Some more text after making containing dir a repo (git init)

git commit -m "first commit; no add was invoked yet"
On branch master

Initial commit

Untracked files:
        ReadYOU.md

nothing added to commit but untracked files present

git add ReadYOU.md

git commit -m "second commit - after staging"
[master (root-commit) bf1fa33] second commit - after staging
 1 file changed, 14 insertions(+)
 create mode 100644 ReadYOU.md

git remote add origin https://github.com/chiefchiefon/git_ex_01.git
git branch -M main
git push -u origin main
<authentication>
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com': shaul.chamoula@gmail.com
Password for 'https://shaul.chamoula@gmail.com@github.com':
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 404 bytes | 404.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/chiefchiefon/git_ex_01.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

git push -u origin main
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com': shaul.chamoula@gmail.com
Password for 'https://shaul.chamoula@gmail.com@github.com':
Everything up-to-date
Branch 'main' set up to track remote branch 'main' from 'origin'.

