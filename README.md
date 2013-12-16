### Dots Template

This template provides a way to quickly get up and running using the dots
dotfile management utility.

#### Instructions

 1. Clone this repository onto your machine somewhere.

 2. Create configuration groups as you see fit. All directories aside from the
    `base` directory should contain a second directory in them representing a
    sub-configuration group.

    For example you could have a `machines/desktop` configuration group for
    your desktop and a `machines/laptop` configuration group for your laptop.
    You could also for example have a `common/develop` for configuration files
    specifically used for development tools.

 3. Organize your dotfiles into their respective configuration groups.

 4. Execute `source init` to install the dots manager and initialize your
    dotfiles into ther directories.

 5. Execute `dots groups set [list of groups here]` then `dots install`.

 5. Enjoy your organized dotfiles!

While not required, it's recommended to read through the [dots
README](https://github.com/EvanPurkhiser/dots).

---

Don't forget to edit this README to be specific to your dotfiles!
