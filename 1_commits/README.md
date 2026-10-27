# Git Commit

## git init
> git init
Dùng để khởi tạo một repository trong máy, quản lí repo này cho một dự án mới.

## git status
> git status
Kiểm tra trạng thái repo (có file mới, những file trong state)
`Untracked`: Những file mới chưa được thêm vào local repo 
`Modifed`: Những file đã được thêm vào trước đó nhưng có sự thay đổi

## git add
> git add .
Dùng để add tất cả các file change vào state

> git add "tên file"
Dùng để add từng file mong muốn vào state

## git commit
> git commit -m "message commit"
Dùng để thêm những thay đổi vào repo trong máy
Mỗi commit sẽ có một commitId
> git commit -a -m "message commit"
Từ working dir và commit với mgs luôn

## Conventional Commits (Tiêu chuẩn 1.0.0)

```bash
git commit -m "feat: thêm tính năng đăng nhập"
git commit -m "fix: sửa lỗi validate email"
git commit -m "feat!: breaking change — đổi API response"
git commit -m "docs: cập nhật README"
```

Format: `type(scope): description`
- feat: tính năng mới
- fix: sửa bug
- docs: tài liệu
- style: format code
- refactor: tái cấu trúc
- test: thêm test
- chore: tooling, dependencies

Ref: https://www.conventionalcommits.org
