ansible-fish
============
[![Build Status](https://travis-ci.org/mkwmms/ansible-fish.svg)](https://travis-ci.org/mkwmms/ansible-fish)

Install & configure the [fish] shell.

Requirements
------------

A system package manager.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.fish }
```

Notes
-----

This role will backup your `~/.config/fish/config.fish` and then add a new one 
using the [template].

License
-------

GPLv3

Author Information
------------------

[@mkwmms]


[@mkwmms]: https://github.com/mkwmms
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[template]: templates/config.j2
[variables]: vars/main.yml
[zsh]: http://zsh.sourceforge.net
