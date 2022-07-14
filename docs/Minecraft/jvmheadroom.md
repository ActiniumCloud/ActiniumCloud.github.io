# How to use the JVM RAM Headroom Variable?

|  Tutorial details |           |
|:-----------------:|:---------:|
| Est. reading time | 5 minutes |
| Difficulty level  | Intermediate       |

**If you're using a 1GB server, make sure to change your JVM Headroom to 512MB or lower!**

## What is JVM RAM Headroom?

In order to understand what it is, we would need to understand the reasoning. Java (JVM) has a way of stashing RAM to access it easily, the only issue with this is that it tends to take 100% of the RAM to do so, leaving none left for the Operating System.
JVM RAM Headroom completely counters this by subtracting the RAM that JVM can use, leaving some headroom for the system. This solution eliminates RAM over heaping therefore making your server run much more faster.


## How would I set it up?

Usually you wouldn't even need to do a thing! The default 1024MB (1GB) should already be enough for the basic Java Server with few plugins and players, but if you are experiencing RAM over heaping (which is common on high player/mods servers) then adjusting the headroom would be ideal.

1024MB (1GB) Not enough? Change it to 1536MB (1.5GB) and see how things run, keep on adding 512MB or 1024MB until you're at the sweet spot.

## Recommended Headroom Settings.


|  Server RAM (GB) |    Headroom Amount (MB)       |
|:-----------------:|:---------:|
| 1GB | 512MB or 256MB |
| 2GB  | 512MB      |
| 4GB  | 1024MB      |
| 6GB  | 1536MB      |
| 8GB  | 2048MB      |
| 10GB  | 2048MB      |
| 12GB  | 2560MB      |

*These may not be right for you depending on your use cases, you may need to adjust.*
