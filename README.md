# gitconfig.d

My Git Configuration Directory

## Install

```
git clone git@github.com:wandersonwhcr/gitconfig.d ~/.gitconfig.d

cat <<'EOF' >> ~/.gitconfig
[include]
    path = ~/.gitconfig.d/main.gitconfig
EOF

cat <<'EOF' >> ~/.gitconfig/main.local.gitconfig
[user]
    name       = John Doe
    email      = john@doe.tld
    signingkey = 0123456789ABCDEF0123456789ABCDEF01234567
EOF
```

## References

* [git-config: Configuration File](https://git-scm.com/docs/git-config#_configuration_file)
* [git-config: Includes](https://git-scm.com/docs/git-config#_includes)
* [Nice, useful global Git configuration](https://gist.github.com/tdd/470582)
