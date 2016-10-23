Setup Guide
===========

install latest Python 3 from Homebrew (Python 3.5 with pip3)
```bash
brew update
brew install python3
```

install nameko using pip3
```bash
pip3 install nameko
```

install RabbitMQ (message broker required by nameko [link](https://nameko.readthedocs.io/en/stable/installation.html#install-with-pip))
```bash
brew install rabbitmq
nano ~/.bash-profile
* add "PATH=$PATH:/usr/local/sbin" to file then save (no "")
```

run RabbitMQ server
```bash
rabbitmq-server
```

[start using nameko](https://nameko.readthedocs.io/en/stable/index.html)
