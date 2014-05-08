## Dots Template

This template provides a way to quickly get up and running using the `dots`
[dotfile management utility](https://github.com/EvanPurkhiser/dots).

### Method 1: Clone Me (Recomended)

If you would like to be able to pull in any changes made to this template, you
may use this as the base for your dotfiles repository.

Simply clone this repository `git clone https://github.com/EvanPurkhiser/dots-template`

### Method 2: Initalize empty

If you would prefer to start with a clean history and don't care or have the
need to pull in any updates to this template repository then you can instead
initalize a new repository with the contents of this repository.

```sh
$ git clone --depth 1 https://github.com/EvanPurkhiser/dots-template
$ rm -rf dots-template/.git
$ git init dots-template
```

### Setting Up Your Dotfiles

 1. Create configuration groups as you see fit. All directories aside from the
    `base` directory should contain a second directory in them representing a
    sub-configuration group.

    For example you could have a `machines/desktop` configuration group for
    your desktop and a `machines/laptop` configuration group for your laptop.
    You could also for example have a `common/develop` for configuration files
    specifically used for development tools.

 2. Organize your dotfiles into their respective configuration groups.

 3. Execute `source init-dots` to install the dots manager and initialize your
    dotfiles into ther directories.

 4. Execute `dots groups set [list of groups here]` then `dots install`.

 5. Enjoy your organized dotfiles!

While not required, it's recommended to read through the [dots
README](https://github.com/EvanPurkhiser/dots/blob/master/README.md).

---

Don't forget to edit this README to be specific to your dotfiles!
