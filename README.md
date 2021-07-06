# cli-privacy

CLI Privacy: Opt-out of third-party tracking in your terminal.

It's becoming more common for software makers to track how people use their
software in private, often without their knowledge. Some provide a way to
opt-out, but there's no universal standard for doing so. To opt-out across
every tool requires digging through documentation, and modifying your shell
configuration.

`cli-privacy` aims to aggregate that app-specific opt-out knowledge in one
place. Install and configure `cli-privacy` once, and it will automatically opt
you out of behavioral tracking across a growing list of third party tools.

## Installation

### With Homebrew

1. Run `brew install rfletcher/cask/cli-privacy`.
2. Add `source /usr/local/bin/cli-privacy` to your shell's init file. (For
   example `.bash_profile` or `.zprofile`.)

### Manually

1. [Download](https://github.com/rfletcher/cli-privacy/releases) the latest
   release.
2. Extract the `cli-privacy` script to any directory you like.
3. Add `source /path/to/cli-privacy` to your shell's init file. (For
   example `.bash_profile` or `.zprofile`.)

## Helping

Can you add to the list of tools supported by `cli-privacy`? Please submit a
pull request!
