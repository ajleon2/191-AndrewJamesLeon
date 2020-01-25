This is a practice repository for a 3-way merge.


Answers to questions:

8. What is the output of `git log --oneline --graph --all`?
86b3df2 (HEAD -> master) Added a README.md file
c8610f4 (greeting) Editted greeting.txt to contain favorite greeting
40ccd48 Add content to greeting.txt
f452737 Add file greeting.txt

9. Diff the branches
diff --git a/README.md b/README.md
deleted file mode 100644
index 1af3803..0000000
--- a/README.md
+++ /dev/null
@@ -1 +0,0 @@
-This is a practice repository for a 3-way merge.
\ No newline at end of file
diff --git a/greeting.txt b/greeting.txt
index ce01362..f942050 100644
--- a/greeting.txt
+++ b/greeting.txt
@@ -1 +1 @@
-hello
+I'm a new greeting :)
\ No newline at end of file
