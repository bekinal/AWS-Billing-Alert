<h1>AWS Instance Setup</h1>

<h2>Description</h2>
Project consists of using a billing alert to notify when 80% of the free services are used.
<br />


<h2>Utilities Used</h2>

- <b>Amazon Web Services</b>

<h2>Creating a new EC2 instance:</h2>
The search bar is used to navigate to the Billing dashboard:<br/>
<img src="https://imagizer.imageshack.com/img924/7404/QHHNiJ.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Budgets is selected from the menu to the left:<br/>
<img src="https://imagizer.imageshack.com/img922/1345/JBbbR3.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A new budget is created:<br/>
<img src="https://imagizer.imageshack.com/img922/3848/rp50Zi.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The budget type is defined as a "Cost budget":<br/>
<img src="https://imagizer.imageshack.com/img922/1443/O3jF95.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The budget name is defined:<br/>
<img src="https://imagizer.imageshack.com/img924/9607/4rL440.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The period is set to recur monthly, and the fixed budget amount is set to $1.00:<br/>
<img src="https://imagizer.imageshack.com/img923/2108/OHEhhG.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
An alert threshold of 80% is defined. This feature sends an email if the alert threshold is triggered:<br/>
<img src="https://imagizer.imageshack.com/img922/7420/i8daPT.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next is selected:<br/>
<img src="https://imagizer.imageshack.com/img924/3199/yaJ7kk.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The budget details are reviewed and created. The budget can be managed through the dashboard:<br/>
<img src="https://imagizer.imageshack.com/img923/2852/DQ3wPP.png" width="80%" alt="Disk Sanitization Steps"/>
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
