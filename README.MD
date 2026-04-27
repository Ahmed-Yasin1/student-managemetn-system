Simple Web Project

This is a simple web project with HTML,CSS,JAVASCRIPT

Git Commands Used

git init
git add.
git commit -m"description"
git status
git log
git push
$ git log
commit c7faaf2ac56d91cd0c5ffb2a2aa0bc13ef532f9f (HEAD -> master)
Merge: 6b14a95 7c5c883
Author: AhmedYasin <xasancumar063@gmail.com>
Date:   Mon Apr 27 04:30:42 2026 -0700

    Merge branch 'feature-login'

commit 7c5c8830a608c35191e0b7ce56b123557879c6fc (feature-login)
Author: AhmedYasin <xasancumar063@gmail.com>
Date:   Mon Apr 27 04:27:10 2026 -0700

    Added pull command

commit 6b14a9542d01bea9712d219310f744333aa08e17
Author: AhmedYasin <xasancumar063@gmail.com>
Date:   Mon Apr 27 04:25:42 2026 -0700

    added pull command

commit b93bb1f316c63be8177816aa59dec1d91d420cdf
Author: AhmedYasin <xasancumar063@gmail.com>
Date:   Mon Apr 27 04:21:41 2026 -0700

    added login feature

commit 544a378be8c7df05af6187c2d6d07f37b97192c2
Author: AhmedYasin <xasancumar063@gmail.com>
Date:   Mon Apr 27 04:17:10 2026 -0700
:
$ git log --oneline
c7faaf2 (HEAD -> master) Merge branch 'feature-login'
7c5c883 (feature-login) Added pull command
6b14a95 added pull command
b93bb1f added login feature
544a378 added gitignore
4119d17 Restore Student file
469acc8 deleted student file
ecdeb4b added 3 students
2fb8bbe added Readme file git commands used
8da1b26 Updated Readme with project description
fff76bf Initial project setup with basic files
10f0e75 deleted all becouse of type err
b4aa8ad Initial project with basic files
 git diff
diff --git a/README.MD b/README.MD
index 34137ae..d6a0b63 100644
--- a/README.MD
+++ b/README.MD
@@ -9,4 +9,48 @@ git add.
 git commit -m"description"
 git status
 git log
-git push
\ No newline at end of file
+git push
+$ git log
+commit c7faaf2ac56d91cd0c5ffb2a2aa0bc13ef532f9f (HEAD -> master)
+Merge: 6b14a95 7c5c883
+Author: AhmedYasin <xasancumar063@gmail.com>
+Date:   Mon Apr 27 04:30:42 2026 -0700
+
+    Merge branch 'feature-login'
+
+commit 7c5c8830a608c35191e0b7ce56b123557879c6fc (feature-login)
+Author: AhmedYasin <xasancumar063@gmail.com>
+Date:   Mon Apr 27 04:27:10 2026 -0700
+
+    Added pull command
+
+commit 6b14a9542d01bea9712d219310f744333aa08e17
+Author: AhmedYasin <xasancumar063@gmail.com>
+Date:   Mon Apr 27 04:25:42 2026 -0700
:
diff --git a/README.MD b/README.MD
index 34137ae..d6a0b63 100644
--- a/README.MD
+++ b/README.MD
@@ -9,4 +9,48 @@ git add.
 git commit -m"description"
 git status
 git log
-git push
\ No newline at end of file
+git push
+$ git log
+commit c7faaf2ac56d91cd0c5ffb2a2aa0bc13ef532f9f (HEAD -> master)
+Merge: 6b14a95 7c5c883
+Author: AhmedYasin <xasancumar063@gmail.com>
+Date:   Mon Apr 27 04:30:42 2026 -0700
+
+    Merge branch 'feature-login'
+
+commit 7c5c8830a608c35191e0b7ce56b123557879c6fc (feature-login)
+Author: AhmedYasin <xasancumar063@gmail.com>
+Date:   Mon Apr 27 04:27:10 2026 -0700
+
+    Added pull command
+
+commit 6b14a9542d01bea9712d219310f744333aa08e17
+Author: AhmedYasin <xasancumar063@gmail.com>
+Date:   Mon Apr 27 04:25:42 2026 -0700
:
git log --oneline
7c5c883 (HEAD -> feature-login) Added pull command
b93bb1f added login feature
544a378 added gitignore
4119d17 Restore Student file
469acc8 deleted student file
ecdeb4b added 3 students
2fb8bbe added Readme file git commands used
8da1b26 Updated Readme with project description
fff76bf Initial project setup with basic files
10f0e75 deleted all becouse of type err
b4aa8ad Initial project with basic files
