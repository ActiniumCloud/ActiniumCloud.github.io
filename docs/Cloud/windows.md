# Installing Windows Server 2016 on a VPS instance

## Step 1 - Mount Windows Server 2016 iso

Log into the control panel and click "ISO Images"

<kbd>
    <img src="https://media.discordapp.net/attachments/943993455481339925/996802375195041883/unknown.png">
</kbd>

Mount any Windows Server 2016 iso image

<kbd>
    <img src="https://media.discordapp.net/attachments/943993455481339925/996808404116967454/unknown.png">
</kbd>

## Step 2 - Install Windows Server 2016

Restart your VPS instance

<kbd>
    <img src="https://media.discordapp.net/attachments/943993455481339925/996802799889285140/unknown.png">
</kbd>

<kbd>
    <img src="https://media.discordapp.net/attachments/943993455481339925/996803741359542302/unknown.png">
</kbd>

Open the KVM console

<kbd>
    <img src="https://media.discordapp.net/attachments/943993455481339925/996810219977969674/unknown.png">
</kbd>

Start the installation process

![1](https://media.discordapp.net/attachments/943993455481339925/996811615649402900/unknown.png)

![1](https://media.discordapp.net/attachments/943993455481339925/996811883753508864/unknown.png)

![1](https://media.discordapp.net/attachments/943993455481339925/996812121536991242/unknown.png)

Go back to the ISO image section and mount the virtio-win drivers

![1](https://media.discordapp.net/attachments/943993455481339925/996803483565047888/unknown.png)

Load the drivers

![1](https://media.discordapp.net/attachments/943993455481339925/996812258019639396/unknown.png)

D:\vioscsi\2k16\amd64\vioscsi.inf

![1](https://media.discordapp.net/attachments/943993455481339925/996813353852878918/chrome_yqs17QhpU2.gif)

![1](https://media.discordapp.net/attachments/943993455481339925/996814695451328552/unknown.png)

Go back to the ISO image section and mount the Windows ISO back

![1](https://media.discordapp.net/attachments/943993455481339925/996808404116967454/unknown.png)

Delete all existing partitions and click "New"

![1](https://media.discordapp.net/attachments/943993455481339925/996816291581145148/chrome_cml82RHr5P.gif)

Finally, you can continue your installation as normal.




