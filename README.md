# Supl Client
This is a supl client bundled with a server to run it using Vagrant. 

## Getting started
- Install [vagrant](https://www.vagrantup.com/docs/installation/)

```sh
# clone the repo
git clone https://github.com/coleHafner/supl-client.git
cd supl-client

# install the submodules
git submodule init
git submodule update

# build and provision the server, compile the supl client
vagrant up
```

## Testing the SUPL client
```sh
vagrant ssh
supl-client -t 3 -d supltest.gpstream.net
```
