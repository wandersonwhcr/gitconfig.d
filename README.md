# gitconfig.d

My Git Configuration Directory

## Install

```
git clone git@github.com:wandersonwhcr/gitconfig.d ~/.gitconfig.d

cat <<'EOF' >> ~/.gitconfig
[include]
    path = ~/.gitconfig.d/main.gitconfig
EOF
```

## References

* [git-config: Configuration File](https://git-scm.com/docs/git-config#_configuration_file)
* [git-config: Includes](https://git-scm.com/docs/git-config#_includes)
