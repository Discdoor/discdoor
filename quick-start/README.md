# DiscDoor Quick Start Folder

This folder is the data directory for a Quick Start setup of DiscDoor.

Please review the values in the `.env` files located in `config/`. There is a high chance that something needs to be changed.

## Known Issues

Here are a list of known issues.

### MongoDB is not connecting

For each module utilizing MongoDB, please change the host name in the accompanying `.env` file. You are recommended to use a direct IP address.

Obviously I cannot guess your local IP, so you will have to find it yourself using `ipconfig` (on Windows) or `ip a` (on Linux).