---
sidebar_position: 1
---


# How to set up a FiveM-Server With TXAdmin


1. Register on our client panel at [https://panel.serverstellar.com/](https://panel.serverstellar.com/)
2. Verify your Discord account at [https://panel.serverstellar.com/profile](https://panel.serverstellar.com/profile)
3. Go to "Servers" and create a server with software "GTA" -> "FiveM". Choose the node that is the closest to you. Also choose a name for your server.


5. Click on "Manage" on your server



6. You're going to be redirected to our panel. Use the same login details as on the client panel.
7. Wait for the installation process to complete. This takes about 2-3 minutes.

8. Go to the "Startup" tab


 

9. Get a key for your server at [https://keymaster.fivem.net/](https://keymaster.fivem.net/) if you don't have one. If your server is on US1, use 209.126.6.98 as the initial IP, if it's on DE2, use 185.215.166.122
10. Set your key in the field.


11. Scroll down and set the txadmin variable to 1
12. Go to the "Network" tab


13. Create a new allocation and copy the port of the new allocation

14. Go to the "Startup" tab and paste the port into the field "TxAdmin Port"


15. Go back to "Console" and start the server. Follow the instructions in the console.


16. Head over to the cfg editor on txadmin and make sure your endpoint is set to 0.0.0.0:[yourPrimaryPort]
If it's not then set it like that (you can find your primary port in the network tab on the panel
