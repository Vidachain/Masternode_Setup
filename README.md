# VIDA Masternode Setup Guide

## Step 1

Enter in your server command prompt:
```sh
wget -q https://raw.githubusercontent.com/Vidachain/Masternode_Setup/master/masternodeinstall.sh
```

```sh
sudo chmod +x masternodeinstall.sh
```

```sh
./masternodeinstall.sh
```

## Step 2

When prompted to Enter your Vida Masternode GEN Key.

Paste your Masternode GEN Key and press enter

# Verify node status

Wait until your masternode is fully Synced with blockchain. You can check this with the command below

```sh
vida-cli getinfo
```

When your masternode is fully synced enter the command below to verify your masternode status.

```sh
vida-cli getmasternodestatus
```

