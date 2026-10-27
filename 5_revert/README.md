# Git Revert

## Git revert
> git revert "commitId"
Tạo một **commit mới** với nội dung ngược lại của commit được chọn — lịch sử commit được giữ nguyên (an toàn hơn `reset --hard`, dùng được trên nhánh đã push).

So sánh nhanh:

| Lệnh | Tác dụng với lịch sử |
|------|---------------------|
| `git revert <commitId>` | Thêm commit mới "đảo ngược" commit cũ — **an toàn cho remote** |
| `git reset --hard <commitId>` | Xóa commit khỏi lịch sử — chỉ dùng khi chưa push |

For Vi or Vim
1. Press "i" (for insert mode)
2. Write your message
3. Press esc (escape insert mode)
4. Press ":wq" (write & quit)
5. Press enter

Ref: https://git-scm.com/docs/git-revert

