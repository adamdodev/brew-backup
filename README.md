# brew-backup

Generate a Brewfile and back it up to git.

## Install

Clone and add the `brew-backup` file to your `$PATH` (e.g. symlink).

## Configure

Create a `.brew-backup` file in your home directory with the following options:
```
git_repo=git@example.com:example/example.git    # Git repo to back up your Brewfile to
```

## Usage

Simply run `brew-backup` to generate a fresh Brewfile and push it to the git repo.

Probably most useful run on a cron or launchd schedule.

```
Usage: brew-backup [options...]

    -h, --help           Show this help info

Configuration: Create a .brew-backup file in your home directory with the following options:

    git_repo=git@example.com:example/example.git    # Git repo to back up your Brewfile to

```

## Info

Originally developed by [Adam Westbrook](https://github.com/adamdodev)

[Licence](https://github.com/adamdodev/brew-backup/blob/master/LICENSE)

Source, issues and questions available on [Github](https://github.com/adamdodev/brew-backup)

Please feel free to contribute, comments, fixes and improvements using the issue tracker linked above.
