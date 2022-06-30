# Failed to Login: Invalid Session

## A non-premium (cracked) player is connecting to a online server

There are two solutions:

1) Disable Minecraft's account verification checks on the server:

!!! danger "Heads up!"
  `Doing this breaks Minecrafts EULA and also makes it significantly easier for people with malicious intentions (such as hackers) to join your server and rejoin after being banned. It's not recommended that you add support for cracked accounts unless you trust your playerbase.`

Find the `server.properties` file on your server, then open it and locate the `online-mode=true` line, and change it to `online-mode=false`. Restart your server and voila! Cracked accounts can now join your server.

2) Tell the players to buy Minecraft and connect to the server with a non-cracked account.
