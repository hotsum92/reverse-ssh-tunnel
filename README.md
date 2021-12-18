# reverse-ssh-tunnel

Reverse SSH tunnel sample.

A reverse SSH tunnel allow an SSH connection to an SSH server behind a firewall.
The SSH server behind a firewall(remote.py) start to make a SSH connection to your PC(local.py).

[2.7 Paramikoを用いたSSH通信プログラムの作成 (BOOK: サイバーセキュリティプログラミング Pythonで学ぶハッカーの思考)]()

## install

Open a command prompt(Local command prompt).

```
pip install paramiko
```

## example

```
python local.py 127.0.0.1 22
```

Open another command prompt(Remote command prompt).

```
python remote.py
```

With local command prompt.


```
ls -al

```

You can get the result of remote command execution.
Do whatever you want.

