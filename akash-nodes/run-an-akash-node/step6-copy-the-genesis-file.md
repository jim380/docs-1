# STEP6 - Copy the Genesis File

Akash nodes need the Genesis file for the blockchain.  In this step we will gather the genesis.json file and make sure it is valid.

### Copy the Genesis File

```
curl -s "$AKASH_NET/genesis.json" > $HOME/.akash/config/genesis.json
```

### Verify the Genesis File

```
akash validate-genesis
```

### Expected Output of Validate Genesis

```
root@ip-10-0-10-101:~# akash validate-genesis

File at /root/.akash/config/genesis.json is a valid genesis file
```