# ssh_with_pipe

Starts ssh with an additional session for piping commands.

## Installation

```bash
git clone https://github.com/okkays/ssh_with_pipe ~/.ssh_with_pipe
cd ~/.ssh_with_pipe
./install
```

## Features

`open` on the remote host will run `open` on the client, instead. This allows
for things like:

```bash
client$ ssh_with_open connect me@some_host
server$ open https://www.google.com # Opens in the client's browser.
```

See `ssh_with_pipe help` for more.
