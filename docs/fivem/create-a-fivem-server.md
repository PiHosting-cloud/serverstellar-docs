---
sidebar_position: 1
---


# How to set up a FiveM-Server With TXAdmin


1. Register on our client panel at [https://client.pihosting.cloud/](https://client.pihosting.cloud/)
2. Verify your Discord account at [https://client.pihosting.cloud/profile](https://client.pihosting.cloud/profile)
3. Go to "Servers" and create a server with software "GTA" -> "FiveM". Choose the node that is the closest to you. Also choose a name for your server.

<img src="https://screenshot.gq/yFBp" alt="Server creation page" width="400"/>

5. Click on "Manage" on your server

<img src="https://docs.pihosting.cloud/uploads/images/gallery/2023-01/scaled-1680-/manage.png" alt="Manage button" width="200"/>

6. You're going to be redirected to our panel. Use the same login details as on the client panel.
7. Wait for the installation process to complete. This takes about 2-3 minutes.

8. Go to the "Startup" tab

<img src="https://docs.pihosting.cloud/uploads/images/gallery/2023-01/scaled-1680-/screenshot-2023-01-18-195307.png" alt="Startup tab" width="100"/>

 

9. Get a key for your server at [https://keymaster.fivem.net/](https://keymaster.fivem.net/) if you don't have one. If your server is on US1, use 209.126.6.98 as the initial IP, if it's on DE2, use 185.215.166.122
10. Set your key in the field.

<img src="https://screenshot.gq/OjGj" alt="FiveM License field" width="500"/>

11. Scroll down and set the txadmin variable to 1
12. Go to the "Network" tab

<img src="https://docs.pihosting.cloud/uploads/images/gallery/2023-01/scaled-1680-/network.png" alt ="Network tab" width="100"/>

13. Create a new allocation and copy the port of the new allocation
<img src="https://screenshot.gq/qwne" alt="Create Allocation" width="500"/>
 
 
<img src="https://docs.pihosting.cloud/uploads/images/gallery/2023-01/scaled-1680-/port.png" alt="Copy new port" width="500"/>

14. Go to the "Startup" tab and paste the port into the field "TxAdmin Port"

<img src="https://docs.pihosting.cloud/uploads/images/gallery/2023-01/scaled-1680-/screenshot-2023-01-18-195307.png" alt="Startup tab" width="100"/>
 
 
<img src="https://screenshot.gq/vdG8" alt="Txadmin Port field" width="500"/>

15. Go back to "Console" and start the server. Follow the instructions in the console.

<img src="https://docs.pihosting.cloud/uploads/images/gallery/2023-01/scaled-1680-/console.png" alt="Console tab" width="100"/>

16. Head over to the cfg editor on txadmin and make sure your endpoint is set to 0.0.0.0:[yourPrimaryPort]
If it's not then set it like that (you can find your primary port in the network tab on the panel
