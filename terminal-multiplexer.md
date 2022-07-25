# Terminal Multiplexer

## Screen

- [screen command GeeksforGeeks](https://www.geeksforgeeks.org/screen-command-in-linux-with-examples/)
- [screen使用](https://blog.csdn.net/qq_28832135/article/details/79831700)

| Common Operations             | Code                       |
| ----------------------------- | -------------------------- |
| Check running screen sessions | `screen -ls`               |
| Create a session              | `screen -S <name>`         |
| Detach a session              | `screen -d <name>`         |
| Go back to a session          | `screen -r <name>`         |
| Kill a session                | `screen -S -X <name> quit` |