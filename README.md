# How to use Git
## Setup
```
1. Tạo 1 repositories trên GitHub
2. Tạo 1 folder dưới máy để chứa dự án với tên bất kỳ
3. Khởi tạo git đầu tiên cho project: git init
```
## Connect folder and GitHub
```
git remote add origin <link >
git remote -v: kiểm tra liên kết link đúng chưa
```
## Push file
```
1. Tạo file trong folder
2. Kiểm tra file mới thêm vào: <b>git status<\b>
3. Thêm tất cả các file project vào: git add . (git add --all)
4. Tạo commit: git commit -m "nd commit"
5. Kiểm tra commit thành công: git log (gitk: debug trước khi chạy)
6. Đẩy lên git: git push origin master
```
## Restore file
 ```
 git restore <Tên file>
```
## Quay lai phien ban truoc
```
git reset --hard <commit_id>
```
