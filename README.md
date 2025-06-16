I started this one by spinning up a new linux server, and then beginning the process of installing fleet server on the machine. 

![alt text](https://i.imgur.com/d5PHPVk.png)

I then had to install the elastic agent onto the host server.

![alt text](https://i.imgur.com/JxnaIgq.jpeg)

After that I installed elastic agent to the windows server for our lab. Things got messy here during setup but after some tinkering I realized a port that was included in a URL inside the fleet server settings.

![alt text](https://i.imgur.com/LCCGo73.png)

And now we have some captured logs from the elastic agent!

![alt text](https://i.imgur.com/hKSmaGJ.png)
