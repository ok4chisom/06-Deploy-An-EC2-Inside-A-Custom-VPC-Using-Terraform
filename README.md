<h1>Deploy An EC2 Inside A Custom VPC Using Terraform</h1>
<!--
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)
<h2>Description</h2>
A new startup business in North America has recruited you to help with the launch of a quick-access, low-cost static website. You've decided to complete this contract by hosting and deploying their website utilizing AWS S3
<br />
-->

<h2>Solution Overview</h2>

- <b>Configure AWS provider
- Create VPC
- Create Subnet
- Create Internet Gateway
- Create Route Tables
- Create EC2 instance
- Create Security Group
- Deploy EC2 in public subnet
- Launch your website

<h2>Detailed Steps:</h2>

<p align="center">

Configure AWS provider <br/> 
<img src="https://i.imgur.com/SOBKW5E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create VPC  <br/>
<img src="https://i.imgur.com/P6ExVmw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Subnet<br/>
<img src="https://i.imgur.com/zm6Ijka.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Internet Gateway<br/>
<img src="https://i.imgur.com/WTfe5gj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Route Tables and assoiciate subnet to route table<br/>
<img src="https://i.imgur.com/s3eHtFG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Security Group<br/>
<img src="https://i.imgur.com/Su2GEOm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create EC2 instance<br/>
<img src="https://i.imgur.com/HHTmT8j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run terraform init -> terraform plan -> terraform apply

Launch your website
- Copy paste your public ip and paste in your browser. You should see your website
<img src="https://i.imgur.com/o8ur737.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>