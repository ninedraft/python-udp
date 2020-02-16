# python-udp
Python udp broadcast client-server example ([previously](https://gist.github.com/ninedraft/7c47282f8b53ac015c1e326fffb664b5))

---

Works for python 3.7 and 2.7 for **Mac OS** and **Linux(kernel>=3.9)** hosts. If you're using **linux(kernel<3.9)**, then use `socket.O_REUSEADDR` instead of `socket.SO_REUSEPORT` to share `(host, port)` between multiple clients and servers.

Tricks and traps:

+ Socket portability issues: [How do SO_REUSEADDR and SO_REUSEPORT differ?](https://stackoverflow.com/questions/14388706/how-do-so-reuseaddr-and-so-reuseport-differ);
+ [Awesome "Socket Programming HOWTO"](https://docs.python.org/3/howto/sockets.html);

Have a question? [Make an issue :3](https://github.com/ninedraft/python-udp/issues/new)