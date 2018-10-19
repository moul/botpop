# botpop

[![GuardRails badge](https://badges.production.guardrails.io/moul/botpop.svg)](https://www.guardrails.io)

## Usage

Simply change in the code the channels / server (2 examples provided with the executable)

It has been tested with ruby 2.2.

``bundle install`` to install the gems.


## Arguments

- -c : list of channels (default equilibre)
- -s : server ip (default to freenode)
- -p : port (default 7000 or 6667 if no ssl)
- --no-ssl : disable ssl (enabled by default)
- -n : nickname
- -u : username
- --config : change the configuration file (default to ``modules_config.yml``)
