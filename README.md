# A prototype shareable hooks. Should work now

## What it does

This is a simple repo that checks global hooks concept of git.

It implements `pre-commit` hook that writes a string `some data` to [text.txt](./text.txt) every time you commit changes.

## Usage

Call [init-hooks.sh](./init-hooks.sh) and try to commit something. After committing changes mind checking
[text.txt](./text.txt)

