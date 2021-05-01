# launchd-plists
A collection of launchd plist files on macOS.

## Setup
```shell
ln -s /path/to/launchd-plists/User/Library/LaunchAgents/* ~/Library/LaunchAgents

# These plist files do not exist on this repository so far
# (sudo?) ln -s /path/to/launchd-plists/System/Library/LaunchAgents/*  /Library/LaunchAgents
# (sudo?) ln -s /path/to/launchd-plists/System/Library/LaunchDaemons/* /Library/LaunchDaemons
```

## Other information
[LaunchControl](https://www.soma-zone.com/LaunchControl/) is useful to launch application via GUI.

```shell
brew install --cask launchcontrol
```

## See also
* https://qiita.com/rsahara/items/7d37a4cb6c73329d4683
* https://blog.freedom-man.com/launchd-daemon-task
* https://dev.classmethod.jp/articles/mac-launch-agents/
