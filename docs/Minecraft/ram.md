# Why is the RAM full?

Currently ActiniumCloud shows the memory allocated by the JVM in the dashboard, not the actual memory occupied by the server, so all you see is the 100% usage. To see the actual memory used by the server, you can do the following.

## Spigot, Paper (and forks), Mohist and CatServer

After installing the Essentials plugin, use commands such as `/memory` `/gc` to display memory usage information.

## Spongeforge

Use the `/sponge heap` command to display JVM information.

## Nukkit

Use the `/status` command to display server information, including memory.

## Bedrock Dedicated Server

BDS is developed in C++ and the memory shown in the dashboard is the real memory occupied by the Minecraft server.