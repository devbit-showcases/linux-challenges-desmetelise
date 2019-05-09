## Challenge 1: RPi Setup Script

**Create a bash script that takes care of the full SSH setup of your Raspberry Pi. Fetch your public keys from Github using curl or a similar tool.**

```sh
#!/usr/bin/env bash
cd ~/.ssh
if [ ! -e authorized_keys ]; then
curl https://github.com/desmetelise.keys >> authorized_keys
else
echo "Authorized_key is already present."
fi
```

## Challenge 2: RPi Detector

**Create a bash script that determines the IP addresses and MAC addresses of all the Raspberry Pi's currently on the network.**

```sh

```
