dotstrap-fish
=========
[![Build Status](https://travis-ci.org/mkwmms/ansible-dotstrap-fish.svg)](https://travis-ci.org/mkwmms/ansible-dotstrap-fish)

Install & configure the [fish] shell.

Requirements
------------

OS X: [homebrew] and the latest XCode tools.

Linux: None.

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
         - { role: mkwmms.dotstrap-fish }
```

License
-------

GPLv3

Author Information
------------------

[@mkwmms]


[@mkwmms]: https://github.com/mkwmms
[dotstrap]: https://github.com/mkwmms/dotstrap
[homebrew]: https://github.com/Homebrew/homebrew
[files]: files/
[default variables]: defaults/main.yml
[variables]: vars/main.yml
[zsh]: http://zsh.sourceforge.net
[fish]: http://fishshell.com/
