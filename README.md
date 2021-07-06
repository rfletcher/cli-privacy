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

1. Download the `cli-privacy` script to any directory you like.
2. `source /path/to/cli-privacy` from your shell's initialization file. (For
   example `.bash_profile` or `.zprofile`

## Contributing

Can you add to the list of tools supported by `cli-privacy`? Please submit a
pull request!
