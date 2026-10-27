# Git Stash, Reflog & Worktree

## Stash — Cất tạm thay đổi

```bash
git stash                           # cất thay đổi chưa commit
git stash list                      # xem danh sách stash
git stash pop                       # lấy lại + xóa stash gần nhất
git stash apply                     # lấy lại + giữ stash
git stash drop                      # xóa stash
git stash -u                        # cả untracked files
git stash -m "message"              # đặt tên stash
```

## Reflog — Lịch sử mọi thao tác

```bash
git reflog                          # xem mọi HEAD changes
git reflog show HEAD@{yesterday}    # xem trạng thái hôm qua
```
→ Dùng để cứu commit sau reset --hard, checkout nhầm, rebase sai.

## Worktree — Làm việc nhiều nhánh cùng lúc

```bash
git worktree add ../feature-xyz feature   # tạo worktree mới cho nhánh feature
git worktree list                              # xem danh sách worktree
git worktree remove ../feature-xyz             # xóa worktree
```

→ Hữu ích khi cần switch giữa nhiều nhánh mà không commit dở, hoặc dùng với AI coding tools (Claude/Copilot) cho từng task.

Ref:
- https://git-scm.com/docs/git-stash
- https://git-scm.com/docs/git-reflog
- https://git-scm.com/docs/git-worktree
