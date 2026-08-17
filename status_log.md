On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	part1/

nothing added to commit but untracked files present (use "git add" to track)
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   part1/notes.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        part1/draft.md
        status_log.md
@@ -1,3 +1,3 @@
 ggg
-Lol
+lol
 dsa
\ No newline at end of file
@@ -1,3 +1,3 @@
 ggg
-Lol
+lol
 dsa
\ No newline at end of file
Phân biệt git fetch và git pull:
- git fetch: Tải thông tin, commit và nhánh mới nhất từ remote repository về máy local nhưng chưa hợp nhất (merge) vào thư mục làm việc hiện tại.
- git pull: Tải dữ liệu mới về đồng thời tự động hợp nhất (merge) vào nhánh làm việc hiện tại trên máy local (tương đương git fetch + git merge).