<h1>AWS Inspector Lab</h1>



<h2>Description</h2>
<br> Late-night AWS Inspector lab, just getting familiar with how AWS Inspector operates, by Performing a vulnerability scan on EC2 instances.

Started off with setting up EC2 instances, then modifying EC2 instances to make these ports “21, 22, 80, 445, 3389” open for inbound traffic. Then I created an assessment target and installed an agent on the EC2 instances. After I created and ran my assessment template, I located and analyzed my findings once it was done running. Inspector produces a detailed list of security findings prioritized by the severity levels. Finally applied the recommended fix to my assessment target.
<br />


<h2>Environments Used </h2>

- <b>Amazon Web Services</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/lLeqo9R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

