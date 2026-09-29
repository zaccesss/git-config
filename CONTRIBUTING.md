# Contributing

Thanks for taking an interest. Contributions are welcome: setting corrections and
guide improvements.

## What belongs here

- A setting Git no longer accepts or that behaves differently on a platform
- A credential helper that is wrong for a platform
- Improvements to the guides
- Improvements to the guides

## What does not belong here

- A setting that only reflects one person's taste rather than something broadly
  useful, keep that in your own copy

## How to contribute

1. Fork the repository and create a branch named `fix/<short-description>` or
   `feat/<short-description>`.
2. Make your change and check it with `git config --file <platform>/gitconfig --list`. Keep the
   three platform files identical except for the credential helper.
3. Open a pull request with a clear title and a one-paragraph description of what changed and
   why. CI validates that every file parses.

## Style rules

> [!IMPORTANT]
> - **Comments**: explain the why, not the what.
> - **UK English** in prose and documentation.

## Reporting bugs

Open an issue with your Git version and platform, what you expected versus what happened.

More about me and my work: [isaacadjei.me](https://isaacadjei.me).
