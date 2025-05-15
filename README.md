## BTC Private Key Checker

This python tools is used to get private keys of BTC address.

sudo python3 -m pip install --upgrade pip && pip3 install bit bip32utils

Then Download latest BTC address files. 
```
run python3 check.py 
```

Example: python3 -r btc.txt -o found_key.txt -t 2

-r : Input file containing btc addresses
-o : Out files to save valid keys
-t : threads to use of server.
