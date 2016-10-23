Setup Guide
===========

1. install latest Python 3 from Homebrew (Python 3.5 with pip3)

```bash
brew update
brew install python3
```

2. install nameko using pip3

```bash
pip install nameko
```

3. install RabbitMQ (message broker required by nameko [link](https://nameko.readthedocs.io/en/stable/installation.html#install-with-pip))

```bash
brew install rabbitmq
nano ~/.bash-profile
* add "PATH=$PATH:/usr/local/sbin" to file then save (no "")
```

4. run RabbitMQ server

```bash
rabbitmq-server
```

5. [start using nameko](https://nameko.readthedocs.io/en/stable/index.html)
 