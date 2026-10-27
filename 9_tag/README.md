# Đánh tag

> git checkout branch main
> git tag 'v1.0.0'
> git push --tags

## Annotated Tag (Tag có chú thích)

```bash
git tag -a v1.0.0 -m "Release version 1.0.0"   # tạo annotated tag
git tag -s v1.0.0 -m "Signed release v1.0.0"   # ký bằng GPG/SSH
git push origin v1.0.0                           # push 1 tag cụ thể (thay vì --tags)
```

Ref: https://git-scm.com/docs/git-tag
