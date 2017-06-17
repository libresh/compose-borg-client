# borg-client
A client to backup to borg server

## Getting started

```
git clone https://github.com/indiehosters/borg-client
cd borg-client
ssh-keygen -f ./ssh/id_rsa -N '' -t rsa
# copy the ssh public key to the remote borg-server
cp env.sample env
vi env
libre start
libre enable
```
