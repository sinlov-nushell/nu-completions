# this Custom completions for https://www.nushell.sh/

- [https://www.nushell.sh/book/custom_completions.html](https://www.nushell.sh/book/custom_completions.html)

## notics

- please install [https://www.nushell.sh](https://www.nushell.sh) then use
- all usage use context at `nu`

## usage

- install pluings [https://github.com/sinlov-nushell/nu-completions](https://github.com/sinlov-nushell/nu-completions)

```bash
mkdir ~/.config/nushell/custom-completions ; cd ~/.config/nushell/custom-completions
git clone https://github.com/sinlov-nushell/nu-completions.git
```

- update pluings

```bash
cd ~/.config/nushell/custom-completions/nu-completions ; git pull
```

### git-completions

```nu
echo "\n# git-completions\nsource ~/.config/nushell/custom-completions/nu-completions/git/git-completions.nu" | save -a $nu.config-path
```

### make-completions

```nu
echo "\n# make-completions\nsource ~/.config/nushell/custom-completions/nu-completions/make/make-completions.nu" | save -a $nu.config-path
```

### docker-completions

```nu
echo "\n# docker-completions\nsource ~/.config/nushell/custom-completions/nu-completions/docker/docker-completions.nu" | save -a $nu.config-path
```

### npm-completions

```nu
echo "\n# npm-completions\nsource ~/.config/nushell/custom-completions/nu-completions/npm/npm-completions.nu" | save -a $nu.config-path
```

### cargo-completions

```nu
echo "\n# cargo-completions\nsource ~/.config/nushell/custom-completions/nu-completions/cargo/cargo-completions.nu" | save -a $nu.config-path
```