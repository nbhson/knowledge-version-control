# Git Clone, Push, Pull

## git clone
> git clone
Lấy code từ trên máy chủ về (nhân bản) máy local

## git push
> git push
Đồng bộ những thay đổi giữa máy local lên máy chủ

## git pull 
> git pull
Đồng bộ giữa máy chủ về máy local

## git pull --rebase
> git pull --rebase
Kéo thay đổi từ remote về và replay các commit local lên trên (thay vì tạo merge commit). Lịch sử commit sạch hơn, tránh các merge commit không cần thiết.

> git config --global pull.rebase true
Đặt `--rebase` làm mặc định cho mọi lần `git pull`.

## push.autoSetupRemote
> git config --global push.autoSetupRemote true
Từ Git 2.37+, khi push nhánh mới lần đầu sẽ tự động set upstream (`git push -u` ngầm định), không cần gõ `git push --set-upstream origin <nhánh>` nữa.

