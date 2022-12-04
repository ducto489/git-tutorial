# git-tutorial

Repo này là một guide hướng dẫn sử dụng github
## Bắt đầu

1. Tải git
1. Tạo 1 repo trên github (có readme.md)
1. Clone repo từ bên trung gian về máy tính qua `git clone https://URL.git`

## Tương tác với github

### Branch (Nhánh nhỏ)

* Tạo một branch `git branch branch_name`
* Tạo nhánh chính `git branch -M tên_branch` (nhánh gốc mà tất cả users sẽ thấy) 

### Pull, Add

* Pull (kéo) code từ trung gian `git pull origin main`, từ nhánh khác `git pull origin branch_name`
* Add file sau khi đã tạo file `git add .`

### Đẩy lên trung gian

* Commit code lên github `git commit -am "YOUR COMMENT ABOUT THIS UPDATE"` 
Lưu ý: Luôn commit trước khi push và comment cần chi tiết
* Push (đẩy) code lên trung gian `git push https://URL.git` hoặc `git push origin main`

## Khi gặp conflict

1. Pull code từ main xuống
1. Merge code
1. Đẩy lên trung gian