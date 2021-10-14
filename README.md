<h1 align="center">
  Pterodactyl-Eggs
</h1>

# What is it?

This repository is made for modified pterodactyl panel eggs.<br>
The modifications are intended to improve some aspect of the specific egg, either for a faster installation, or settings that are not configured by default.

## CS-GO

The CS-GO egg has been improved in many ways.<br>
Here is the list.

**1 -** Rewritten installation script.
Now you no longer need steamcmd to download the full server from the valve servers. Now the script downloads the server already configured with updated and stable `Sourcemod + Metamod` via my URL.<br>
**2 -** More useful variables, such as tickrate, passwords, etc.<br>
**3 -** The `server.cfg` file is already included in the server files, this file is updated on each server restart, you can see this on the main egg page, under `Configuration Files`.<br>

### Advantages of using this egg

**1 -** The server is downloaded and configured in no more than 10 minutes.<br>
**2 -** Fully configured for standard use.

### Disadvantages

**1 -** If the download speed of your node is less than `100 MBPS`, it can take on average 15 to 20 minutes for the server to be ready. If this is your case, you decide whether to use the original egg, or mine. At speeds starting at `200 MBPS` the server downloads in less than 1 minute.<br>

### Why did I create this?

Firstly, to improve egg both in more basic options and in download speed from a server.
The standard egg in my region takes around 30-40 minutes to download.
With my egg, this is down to 10 minutes.

### Attention!

If you are going to use this, please allocate at least `70 GB` of server space in your panel, this is in case someone uses the option to reinstall the server via the client front-end.<br>
If the value is below 70 GB, the reinstall may fail.
This is just to avoid this problem, since pterodactyl does not delete the old server in this process, which ends up adding 30 GB of server with another 30 GB of the new server.




