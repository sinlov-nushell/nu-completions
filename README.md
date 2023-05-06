# this Custom completions for https://www.nushell.sh/

- [https://www.nushell.sh/book/custom_completions.html](https://www.nushell.sh/book/custom_completions.html)

## notics

please install [https://www.nushell.sh](https://www.nushell.sh) then use

## usage

- install

```bash
mkdir ~/.config/nushell/custom-completions && cd ~/.config/nushell/custom-completions
git clone https://github.com/sinlov-nushell/nu-completions.git
```

- update

```bash
cd ~/.config/nushell/custom-completions/nu-completions ; git pull
```

### git-completions

```nu
echo "\n\n# git-completions\nsource ~/.config/nushell/custom-completions/nu-completions/git/git-completions.nu" | save -a $nu.config-path
```