# Commit Conventions

Starting from September 15th, 2023, I would use this commit convention unless working on repositories or organizations with a specified commit convention.

## Commit Approach

It is highly recommended to commit "atomically" instead of making bulk commits.

## Commit Messages

The commit messages specification are based on the [Gitmoji Official Specification](https://gitmoji.dev/specification).

* Commit messages must be written in only Latin alphabets, spaces, brackets, parantheses, numbers, and graves.

* A commit message consists of two or three elements:
  * emoji
    * Emojis should well represent the main purpose of the commit.
    * References can be taken from [Gitmoji](https://gitmoji.dev).
    * It is recommended to use [GitHub emoji shortcodes](https://github.com/ikatyang/emoji-cheat-sheet).
  * scope (optional)
    * Scopes could be added to the commit message to help other contributors to know where the changes have been made.
    * They must be wrapped in parentheses and written in all lowercases. 
  * message
    * Messages should explain what changes have been made.
    * They must start with a verb and it should be in its capitalized dictionary form.
    * Messages should not exceed 40 characters.

> ### This is an example of a commit message following this convention:
> :sparkles:(user backend) Add new `GET` endpoint `/settings`