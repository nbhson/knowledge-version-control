# Resolve conflict (xử lí xung đột)

> git checkout "nhánh chính"
> git pull origin "nhánh chính"

> git checkout "nhánh phụ"
> git rebase "nhánh chính"
-> fix conflicts

> git add .
> git rebase --continue
> git push --force-with-lease "nhánh phụ"

> git checkout "nhánh chính"
> git merge "nhánh phụ"

