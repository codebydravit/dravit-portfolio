Microsoft Windows [Version 10.0.19045.5854]
(c) Microsoft Corporation. All rights reserved.

C:\Users\dravit\Desktop\portifio>dir
 Volume in drive C has no label.
 Volume Serial Number is 6846-B2F4

 Directory of C:\Users\dravit\Desktop\portifio

12-06-2025  11:31    <DIR>          .
12-06-2025  11:31    <DIR>          ..
12-06-2025  12:41    <DIR>          dravit-portfolio
12-06-2025  11:28             5,413 dravit-portfolio.html
12-06-2025  11:21                 0 New Text Document.txt
               2 File(s)          5,413 bytes
               3 Dir(s)  277,692,801,024 bytes free

C:\Users\dravit\Desktop\portifio>cd  dravit-portfolio

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git init           
Initialized empty Git repository in C:/Users/dravit/Desktop/portifio/dravit-portfolio/.git/

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "first commit"
[main (root-commit) 9ef159c] first commit
 8 files changed, 293 insertions(+)
 create mode 100644 README.md
 create mode 100644 about.html
 create mode 100644 articles.html
 create mode 100644 assets/Dravit_Resume.pdf
 create mode 100644 assets/profile.jpg
 create mode 100644 contact.html
 create mode 100644 index.html
 create mode 100644 projects.html

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git branch -M main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git remote add origin https://github.com/codebydravit/dravit-portfolio.git

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (9/9), 3.47 KiB | 1.16 MiB/s, done.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/codebydravit/dravit-portfolio.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/codebydravit/dravit-portfolio.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
To https://github.com/codebydravit/dravit-portfolio.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
branch 'main' set up to track 'origin/main'.

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "second 404 page commit" 
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html
        modified:   articles.html
        modified:   contact.html
        modified:   index.html
        modified:   projects.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        thispagedoesnotexist.html

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "second 404 page commit"
[main 2ae2478] second 404 page commit
 6 files changed, 54 insertions(+), 5 deletions(-)
 create mode 100644 thispagedoesnotexist.html

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git branch -M main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git remote add origin https://github.com/codebydravit/dravit-portfolio.git
error: remote origin already exists.

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push -u origin main
To https://github.com/codebydravit/dravit-portfolio.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/codebydravit/dravit-portfolio.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push --help

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git branch
* main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
To https://github.com/codebydravit/dravit-portfolio.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/codebydravit/dravit-portfolio.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git pull origin main --rebase
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (5/5), 1.57 KiB | 100.00 KiB/s, done.
From https://github.com/codebydravit/dravit-portfolio
 * branch            main       -> FETCH_HEAD
   9ef159c..d77ff0e  main       -> origin/main
Successfully rebased and updated refs/heads/main.

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.27 KiB | 1.27 MiB/s, done.
Total 8 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), completed with 5 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   d77ff0e..704fcec  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git mv thispagedoesnotexist.html 404.html
fatal: bad source, source=thispagedoesnotexist.html, destination=404.html

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "Add custom 404 page"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    thispagedoesnotexist.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        404.html

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Everything up-to-date

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Everything up-to-date

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "Add custom 404 page"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    thispagedoesnotexist.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        404.html

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git rm thispagedoesnotexist.html                                    
rm 'thispagedoesnotexist.html'

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add 404.html

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "Renamed custom 404 page"
[main a2e1329] Renamed custom 404 page
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename thispagedoesnotexist.html => 404.html (100%)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 263 bytes | 263.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/codebydravit/dravit-portfolio.git
   704fcec..a2e1329  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "Moved pages to folders for clean URLs"
[main 8cd0cd9] Moved pages to folders for clean URLs
 5 files changed, 20 insertions(+), 20 deletions(-)
 rename 404.html => 404/index.html (82%)
 rename about.html => about/index.html (84%)
 rename articles.html => articles/index.html (88%)
 rename contact.html => contact/index.html (88%)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (11/11), 3.19 KiB | 155.00 KiB/s, done.
Total 11 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
To https://github.com/codebydravit/dravit-portfolio.git
   a2e1329..8cd0cd9  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Everything up-to-date

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "removed doulbe dot in href link"       
[main e2ec40d] removed doulbe dot in href link
 5 files changed, 16 insertions(+), 16 deletions(-)
 rename projects.html => projects/index.html (88%)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (11/11), 1.43 KiB | 731.00 KiB/s, done.
Total 11 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 4 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   8cd0cd9..e2ec40d  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Everything up-to-date

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated pages to folders for clean URLs" 
[main 9e4b352] updated pages to folders for clean URLs
 5 files changed, 9 insertions(+), 9 deletions(-)
 rename about/{index.html => about.html} (100%)
 rename articles/{index.html => articles.html} (98%)
 rename contact/{index.html => contact.html} (90%)
 rename projects/{index.html => projects.html} (98%)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (11/11), 2.30 KiB | 1.15 MiB/s, done.
Total 11 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   e2ec40d..9e4b352  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "update path issues  href link"       
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   404/index.html
        deleted:    about/about.html
        deleted:    articles/articles.html
        deleted:    contact/contact.html
        modified:   index.html
        deleted:    projects/projects.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about/index.html
        articles/index.html
        contact/index.html
        projects/index.html

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "update path issues  href link"
[main b56a8b0] update path issues  href link
 6 files changed, 24 insertions(+), 24 deletions(-)
 rename about/{about.html => index.html} (82%)
 rename articles/{articles.html => index.html} (86%)
 rename contact/{contact.html => index.html} (86%)
 rename projects/{projects.html => index.html} (86%)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (13/13), 3.58 KiB | 915.00 KiB/s, done.
Total 13 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   9e4b352..b56a8b0  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Everything up-to-date

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated pages to folders for clean URLs"
[main ff4d30d] updated pages to folders for clean URLs
 1 file changed, 4 insertions(+), 4 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 390 bytes | 390.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   b56a8b0..ff4d30d  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Everything up-to-date

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated pages to folders for clean URLs"
[main 798d9e4] updated pages to folders for clean URLs
 1 file changed, 5 insertions(+), 5 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   ff4d30d..798d9e4  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated pages to folders for clean URLs"
[main 65bbd16] updated pages to folders for clean URLs
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   798d9e4..65bbd16  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated pages remove .html in the  URLs" 
[main 14117e1] updated pages remove .html in the  URLs
 5 files changed, 25 insertions(+), 25 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (12/12), 1.45 KiB | 743.00 KiB/s, done.
Total 12 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), completed with 5 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   65bbd16..14117e1  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated home pages to folders for clean URLs" 
[main 494b805] updated home pages to folders for clean URLs
 6 files changed, 6 insertions(+), 6 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (13/13), 1.55 KiB | 528.00 KiB/s, done.
Total 13 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), completed with 5 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   14117e1..494b805  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "issue with404 .html page"                
[main c26d5c9] issue with404 .html page
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename 404/index.html => 404.html (100%)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.21 KiB | 1.21 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/codebydravit/dravit-portfolio.git
   494b805..c26d5c9  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .                                                    

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated footer copyright"                
[main 64d1061] updated footer copyright
 6 files changed, 52 insertions(+), 10 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.  
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done. 
Writing objects: 100% (12/12), 2.64 KiB | 676.00 KiB/s, done. 
Total 12 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 5 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   c26d5c9..64d1061  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add contact

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated space mb in contact page" 
[main de1f9fe] updated space mb in contact page
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 357 bytes | 357.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   64d1061..de1f9fe  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add assets

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated assets resume download in home page" 
[main d4e690f] updated assets resume download in home page
 1 file changed, 0 insertions(+), 0 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 193.94 KiB | 21.55 MiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/codebydravit/dravit-portfolio.git
   de1f9fe..d4e690f  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add contact

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add index  
fatal: pathspec 'index' did not match any files

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .            

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated  resume download in home  page"       
[main 4a91808] updated  resume download in home  page
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   d4e690f..4a91808  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .            
warning: in the working copy of 'assets/favicon.svg', LF will be replaced by CRLF the next time Git touches it

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated main index page "               
[main 409e414] updated main index page
 4 files changed, 233 insertions(+), 7 deletions(-)
 create mode 100644 assets/favicon.svg
 create mode 100644 assets/profile.jfif
 create mode 100644 uses/index.html

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 35.13 KiB | 7.03 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 35.13 KiB | 7.03 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 35.13 KiB | 7.03 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 35.13 KiB | 7.03 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 35.13 KiB | 7.03 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   4a91808..409e414  main -> main
To https://github.com/codebydravit/dravit-portfolio.git
   4a91808..409e414  main -> main
   4a91808..409e414  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "final template for  home  page is done like color and hover effect are done "
[main ab5b2c3] final template for  home  page is done like color and hover effect are done
 3 files changed, 301 insertions(+), 54 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
[main ab5b2c3] final template for  home  page is done like color and hover effect are done
 3 files changed, 301 insertions(+), 54 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
 3 files changed, 301 insertions(+), 54 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Counting objects: 100% (13/13), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 5.87 KiB | 1.96 MiB/s, done.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 5.87 KiB | 1.96 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Writing objects: 100% (7/7), 5.87 KiB | 1.96 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/codebydravit/dravit-portfolio.git
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/codebydravit/dravit-portfolio.git
   409e414..ab5b2c3  main -> main
To https://github.com/codebydravit/dravit-portfolio.git
   409e414..ab5b2c3  main -> main
   409e414..ab5b2c3  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .










C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .







C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .





C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .



C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .



C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated  color   all  page"             
[main ebdff95] updated  color   all  page
[main ebdff95] updated  color   all  page
 10 files changed, 414 insertions(+), 131 deletions(-)
 create mode 100644 assets/email.svg
 create mode 100644 assets/location.svg
 create mode 100644 assets/shaking-hands.svg

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
 create mode 100644 assets/email.svg
 create mode 100644 assets/location.svg
 create mode 100644 assets/shaking-hands.svg

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
 create mode 100644 assets/location.svg
 create mode 100644 assets/shaking-hands.svg

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
 create mode 100644 assets/shaking-hands.svg

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
Compressing objects: 100% (13/13), done.
Enumerating objects: 31, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (18/18), 18.30 KiB | 3.05 MiB/s, done.
Counting objects: 100% (31/31), done.
Delta compression using up to 8 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (18/18), 18.30 KiB | 3.05 MiB/s, done.
Total 18 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
Compressing objects: 100% (13/13), done.
Writing objects: 100% (18/18), 18.30 KiB | 3.05 MiB/s, done.
Total 18 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
Writing objects: 100% (18/18), 18.30 KiB | 3.05 MiB/s, done.
Total 18 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (7/7), completed with 2 local objects.
Total 18 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (7/7), completed with 2 local objects.
remote: Resolving deltas: 100% (7/7), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   ab5b2c3..ebdff95  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated contact page "    
[main 7b832f3] updated contact page
 1 file changed, 26 insertions(+), 29 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 649 bytes | 649.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   ebdff95..7b832f3  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git add .

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git commit -m "updated  about page"        
[main 11f4e3a] updated  about page
 3 files changed, 125 insertions(+), 49 deletions(-)

C:\Users\dravit\Desktop\portifio\dravit-portfolio>git push origin main
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.  
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done. 
Writing objects: 100% (8/8), 1.70 KiB | 870.00 KiB/s, done.
Total 8 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 4 local objects.
To https://github.com/codebydravit/dravit-portfolio.git
   7b832f3..11f4e3a  main -> main

C:\Users\dravit\Desktop\portifio\dravit-portfolio>         
