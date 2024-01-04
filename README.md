# SSH-to-EC2-instance-with-Termius
# AWS SSH
<p align="center">
<img src="https://i.imgur.com/sspxmci.png"/>
</p>

<h1>SSH into a EC2 instance in AWS with Termius</h1>
In this tutorial, we will ssh are ec2 linux instance with termius by using punblic Ip address and pairing a .pem file key. <br />




<h2>Environments and Technologies Used</h2>

- AWS (EC2 / Linux / Termius)


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>Actions and Observations</h2>

<p>
<img src="https://imgur.com/lK6a3Qj"/>
</p>
<p>
First we need to log into AWS to access are home console then we can launch are virtual machine with EC2.
</p>
<br />

<p>
<img src="https://imgur.com/a/MZPsMwu"/>
</p>
<p>
Once we are in EC2 dashboard we can click "Launch instance" and will we be prompted to and given the options to select the OS image we need. Select Amazon linux for this project.
</p>
<br />

<p>
<img src="https://imgur.com/a/C675SRJ"/>
</p>
<p>
Next scroll down till you see "Key pair (login)", we will need this to securely connect to are instance. Give it a name then click "Create new key pair" and it will download to your files automatically. 
<br />

<p>
<img src="https://imgur.com/a/wx0XulS"/>
</p>
<p>
Now that we got are desired stated, we can launch are instance. Click the orange button that saids "Launch instance" in the far right bottom corner.
</p>
<br />

<p>
<img src="https://imgur.com/HNJEptQ"/>
</p>
<p>
Click connect to launch the the instance.
</p>
<br />

<p>
<img src="https://imgur.com/a/7r3zPfi"/>
</p>
<p>
Next we will make sure to copy the IP address use (ctrl + C) to copy, and from there we can click connect to launch are application.
</p>
<br />

<p>
<img src="https://imgur.com/a/nDpozFP"/>
</p>
<p>
Now at this point we should be able to see Amazon's linux cli.
</p>
<br />

<p>
<img src="https://imgur.com/a/WaSvAK6"/>
</p>
<p>
Next we will download and install Termius.
</p>
<br />

<p>
<img src="https://imgur.com/a/d0su1x6"/>
</p>
<p>
Once installed we will paste are IP address to are new host, "ctrl + V" to paste. Next we will click create host. 
</p>
<br />

<p>
<img src="https://imgur.com/a/yXMpINr"/>
</p>
<p>
Next page we drag and drop are private key file.
</p>
<br />

<p>
<img src="https://imgur.com/a/LsPlf7o"/>
</p>
<p>
From there we can now see the linux terminal that we SSH in Termius.
</p>
<br />

<p>
<img src="https://imgur.com/a/lumZUyY"/>
</p>
<p>
We will now verify that it worked by creating a directory, using command "mkdir Hello world!".Then we will see in Amazon linux if the files did indeed stored. 
</p>
<br />

<p>
<img src="https://imgur.com/a/UUDOqko"/>
</p>
<p>
Now we will go back to are browser then go into Amazon linux and we will  type the command "LS", to list are directory. We should see "Hello world!". 
</p>
<br />
