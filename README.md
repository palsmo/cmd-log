## About

Command for printing nice logging messages in the terminal. \
Lightweight, simple and effective.

## Install
* requires UNIX system & Bash

```bash
git clone github.com/palsmo/cmd-log
cd ./cmd-log/
mv ./log /usr/bin/ # any dir in `PATH`
```

## Info

```shell
Usage: log <LOG_TYPE> <MESSAGE> <OPTIONS>
Print a nice logging message.

Arguments:
  LOG_TYPE - Type of log (DEBUG, INFO, SHOW, TASK, WARN, FAIL)
  MESSAGE  - Text message

Options:
  -n       - Do not output trailing newline
  -e       - Exit after logging the message

Example:
  log INFO 'This is a generic message.'
```

## Screenshots

<div>
    <img src="screenshots/001.webp" alt="screenshot" width="auto" height="350">
</div>
