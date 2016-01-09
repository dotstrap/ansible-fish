ansible-fish
============
[![Build Status](https://travis-ci.org/mkwmms/ansible-fish.svg)](https://travis-ci.org/mkwmms/ansible-fish)

Install & configure the [fish] shell.

Installation
------------

```
ansible-galaxy install mkwmms.fish
```

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

Using all the [default variables]:

```
    - hosts: all
      roles:
         - role: mkwmms.fish
```

Notes
-----

__Warning__: This role will change your default shell to [fish].

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
