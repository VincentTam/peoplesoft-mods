---
id: 80
title: PeopleSoft Campus Solutions Native OS DPK Install
date: 2016-05-25T18:30:55+00:00
guid: http://www.peoplesoftmods.com/?p=80
permalink: /psadmin/campus-solutions-9-2-nativeos-dpk-install/
categories:
  - PeopleSoft Administration
---
This is the step-by-step process that I took to install the Campus Solutions 9.2 application to a Windows  operating system using the Native OS deployment package (DPK).  Using the DPK to deploy the environment took several failed attempts before I was able to get it working properly. This tutorial was done using CS PUM image 1 and it is likely that the deployment steps will change in future PUM images.

<!--more-->

Create two folders in the base of your C drive.  Name the first one _CS92_DPK_ (path: _C:\CS92_DPK_) and the second one _psft_ (path: _C:\psft_).  Note: Subsequent steps in this tutorial assume that you are using the same naming conventions that are specified in this step.

Go to the PeopleSoft Update Manager (PUM) homepage and navigate to the _Campus Solutions Update Image Homepage_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture31.png" rel="attachment wp-att-125"><img class="alignnone size-full wp-image-125" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture31.png" alt="Capture31" width="738" height="483" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture31.png 738w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture31-300x196.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture31-581x380.png 581w" sizes="(max-width: 738px) 100vw, 738px" /></a>

Click the _Native OS_ link and select _PeopleSoft Update Image CS 9.2.001 Native OS_ for the _Windows_ platform

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture32.png" rel="attachment wp-att-126"><img class="alignnone size-full wp-image-126" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture32.png" alt="Capture32" width="951" height="437" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture32.png 951w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture32-300x138.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture32-768x353.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture32-827x380.png 827w" sizes="(max-width: 951px) 100vw, 951px" /></a>

Click the _Download_ button and agree to the terms and conditions

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture33.png" rel="attachment wp-att-127"><img class="alignnone size-full wp-image-127" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture33.png" alt="Capture33" width="1021" height="265" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture33.png 1021w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture33-300x78.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture33-768x199.png 768w" sizes="(max-width: 1021px) 100vw, 1021px" /></a>

Click the _Download All_ button to download all 10 of the zip files

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture34.png" rel="attachment wp-att-128"><img class="alignnone size-full wp-image-128" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture34.png" alt="Capture34" width="835" height="540" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture34.png 835w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture34-300x194.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture34-768x497.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture34-588x380.png 588w" sizes="(max-width: 835px) 100vw, 835px" /></a>

Save the zip files to the newly created _C:\CS92_DPK\_ directory

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture1.png" rel="attachment wp-att-81"><img class="alignnone size-full wp-image-81" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture1.png" alt="Capture1" width="792" height="314" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture1.png 792w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture1-300x119.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture1-768x304.png 768w" sizes="(max-width: 792px) 100vw, 792px" /></a>

Extract the contents of the _CS-920-UPD-001-WIN_1of10.zip_ file into _C:\__CS92_DPK_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture2.png" rel="attachment wp-att-82"><img class="alignnone size-full wp-image-82" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture2.png" alt="Capture2" width="617" height="424" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture2.png 617w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture2-300x206.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture2-553x380.png 553w" sizes="(max-width: 617px) 100vw, 617px" /></a>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture3.png" rel="attachment wp-att-83"><img class="alignnone size-full wp-image-83" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture3.png" alt="Capture3" width="790" height="396" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture3.png 790w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture3-300x150.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture3-768x385.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture3-758x380.png 758w" sizes="(max-width: 790px) 100vw, 790px" /></a>

Search for the Windows PowerShell program, right click it, and run it as administrator

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture1.png" rel="attachment wp-att-84"><img class="alignnone size-full wp-image-84" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture1.png" alt="Picture1" width="400" height="556" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture1.png 400w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture1-216x300.png 216w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture1-273x380.png 273w" sizes="(max-width: 400px) 100vw, 400px" /></a>

Change the directory to the directory that contains the setup folder

<pre>cd C:\CS92_DPK\setup\</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture4.png" rel="attachment wp-att-85"><img class="alignnone size-full wp-image-85" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture4.png" alt="Capture4" width="533" height="111" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture4.png 533w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture4-300x62.png 300w" sizes="(max-width: 533px) 100vw, 533px" /></a>

Run the following command (prevents security access errors) and then press _y_

<pre>Set-ExecutionPolicy unrestricted</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture5.png" rel="attachment wp-att-86"><img class="alignnone size-full wp-image-86" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture5.png" alt="Capture5" width="954" height="188" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture5.png 954w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture5-300x59.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture5-768x151.png 768w" sizes="(max-width: 954px) 100vw, 954px" /></a>

Now run the setup script

<pre>./psft-dpk-setup.ps1</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture6.png" rel="attachment wp-att-87"><img class="alignnone size-full wp-image-87" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture6.png" alt="Capture6" width="956" height="203" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture6.png 956w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture6-300x64.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture6-768x163.png 768w" sizes="(max-width: 956px) 100vw, 956px" /></a>

Press _y_ to install Puppet on the host

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture7.png" rel="attachment wp-att-88"><img class="alignnone size-full wp-image-88" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture7.png" alt="Capture7" width="954" height="467" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture7.png 954w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture7-300x147.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture7-768x376.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture7-776x380.png 776w" sizes="(max-width: 954px) 100vw, 954px" /></a>

Enter the following path for the PeopleSoft base folder and then press _y_

<pre>C:\psft</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture8.png" rel="attachment wp-att-89"><img class="alignnone size-full wp-image-89" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture8.png" alt="Capture8" width="566" height="156" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture8.png 566w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture8-300x83.png 300w" sizes="(max-width: 566px) 100vw, 566px" /></a>

Enter the following values for the environment variables and then press _y_:

Database Name = _CS92_

Connect ID = _people_

Connect ID Password = _peop1e_

App Server Domain Password (_Do not set, just press enter_)

Weblogic Server Admin Password = _Weblog1c_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture9a.png" rel="attachment wp-att-90"><img class="alignnone size-full wp-image-90" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture9a.png" alt="Capture9a" width="765" height="440" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture9a.png 765w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture9a-300x173.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture9a-661x380.png 661w" sizes="(max-width: 765px) 100vw, 765px" /></a>

Press _n_ at the “Do you want to continue with the default initialization process” prompt.  Then exit PowerShell and restart your machine.

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture10.png" rel="attachment wp-att-91"><img class="alignnone size-full wp-image-91" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture10.png" alt="Capture10" width="611" height="269" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture10.png 611w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture10-300x132.png 300w" sizes="(max-width: 611px) 100vw, 611px" /></a>

Go to _C:\ProgramData\PuppetLabs\puppet\etc\data_ directory and create a file named _psft_customizations.yaml_.  Open this file in a text editor, paste in the 3 lines of text below, and then save.  Or you can just download the file from <a href="http://www.peoplesoftmods.com/Development/psft_customizations.yaml" target="_blank">here</a> and then upload it to the _C:\ProgramData\PuppetLabs\puppet\etc\data_ directory.

<pre>---

db_port:               1521</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture2.png" rel="attachment wp-att-92"><img class="alignnone size-full wp-image-92" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture2.png" alt="Picture2" width="872" height="281" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture2.png 872w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture2-300x97.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture2-768x247.png 768w" sizes="(max-width: 872px) 100vw, 872px" /></a>

Run PowerShell as administrator.  Change the directory and press _enter._

<pre>cd C:\ProgramData\PuppetLabs\puppet\etc\manifests</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture12.png" rel="attachment wp-att-93"><img class="alignnone size-full wp-image-93" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture12.png" alt="Capture12" width="618" height="106" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture12.png 618w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture12-300x51.png 300w" sizes="(max-width: 618px) 100vw, 618px" /></a>

Set the execution policy and press _y_

<pre>Set-ExecutionPolicy unrestricted</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture13.png" rel="attachment wp-att-94"><img class="alignnone size-full wp-image-94" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture13.png" alt="Capture13" width="947" height="188" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture13.png 947w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture13-300x60.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture13-768x152.png 768w" sizes="(max-width: 947px) 100vw, 947px" /></a>

Run the following command to deploy the environment

<pre>puppet apply site.pp</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture14.png" rel="attachment wp-att-95"><img class="alignnone size-full wp-image-95" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture14.png" alt="Capture14" width="941" height="206" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture14.png 941w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture14-300x66.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture14-768x168.png 768w" sizes="(max-width: 941px) 100vw, 941px" /></a>

Once the script is done running, close out of PowerShell and run the Command Prompt as administrator.  Change the directory and press _enter._

<pre>cd C:\psft\pt\ps_home8.55.03\appserv</pre>

Run the psadmin program

<pre><i>p</i><i>sadmin.exe</i></pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture3.png" rel="attachment wp-att-96"><img class="alignnone size-full wp-image-96" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture3.png" alt="Picture3" width="651" height="407" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture3.png 651w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture3-300x188.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture3-608x380.png 608w" sizes="(max-width: 651px) 100vw, 651px" /></a>

Press _6_ for the Service Startup Menu

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture4.png" rel="attachment wp-att-97"><img class="alignnone size-full wp-image-97" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture4.png" alt="Picture4" width="658" height="433" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture4.png 658w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture4-300x197.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture4-577x380.png 577w" sizes="(max-width: 658px) 100vw, 658px" /></a>

Press _1_ to Configure Windows Service and then press _y_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture5.png" rel="attachment wp-att-98"><img class="alignnone size-full wp-image-98" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture5.png" alt="Picture5" width="658" height="236" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture5.png 658w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture5-300x108.png 300w" sizes="(max-width: 658px) 100vw, 658px" /></a>

Press _y_ (again) to change values and set the variables to the following values:

Service Start Delay = _10_

Application Server Domains = _APPDOM_

Process Scheduler Domains = _PRCSDOM_

Search Server Domains (_Do not set, just press enter_)

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture6.png" rel="attachment wp-att-99"><img class="alignnone size-full wp-image-99" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture6.png" alt="Picture6" width="477" height="146" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture6.png 477w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture6-300x92.png 300w" sizes="(max-width: 477px) 100vw, 477px" /></a>

Press _n_ to not make anymore changes and then press _2_ to Install Windows Service

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture7.png" rel="attachment wp-att-100"><img class="alignnone size-full wp-image-100" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture7.png" alt="Picture7" width="606" height="206" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture7.png 606w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture7-300x102.png 300w" sizes="(max-width: 606px) 100vw, 606px" /></a>

Search for the Windows Services program, right click it, and run it as administrator

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture8.png" rel="attachment wp-att-101"><img class="alignnone size-full wp-image-101" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture8.png" alt="Picture8" width="401" height="557" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture8.png 401w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture8-216x300.png 216w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture8-274x380.png 274w" sizes="(max-width: 401px) 100vw, 401px" /></a>

Scroll down and double click on the service named _OracleOraDB12cHomeTNSListener_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture9.png" rel="attachment wp-att-102"><img class="alignnone size-full wp-image-102" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture9.png" alt="Picture9" width="811" height="463" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture9.png 811w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture9-300x171.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture9-768x438.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture9-666x380.png 666w" sizes="(max-width: 811px) 100vw, 811px" /></a>

Change the _Startup type_ to _Automatic_ and click apply

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture10.png" rel="attachment wp-att-103"><img class="alignnone size-full wp-image-103" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture10.png" alt="Picture10" width="813" height="592" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture10.png 813w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture10-300x218.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture10-768x559.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture10-522x380.png 522w" sizes="(max-width: 813px) 100vw, 813px" /></a>

Scroll down and double click on the service named _PeopleSoft\_C\_\_Users\_PS\_psft\_pt_8.55_ 

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture11.png" rel="attachment wp-att-104"><img class="alignnone size-full wp-image-104" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture11.png" alt="Picture11" width="811" height="482" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture11.png 811w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture11-300x178.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture11-768x456.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture11-639x380.png 639w" sizes="(max-width: 811px) 100vw, 811px" /></a>

Change the _Startup type_ to _Automatic_ and click apply

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture12.png" rel="attachment wp-att-105"><img class="alignnone size-full wp-image-105" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture12.png" alt="Picture12" width="813" height="592" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture12.png 813w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture12-300x218.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture12-768x559.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture12-522x380.png 522w" sizes="(max-width: 813px) 100vw, 813px" /></a>

Ensure that all of the following services have the _Startup type_ set to _Automatic_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture13.png" rel="attachment wp-att-106"><img class="alignnone size-full wp-image-106" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture13.png" alt="Picture13" width="811" height="480" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture13.png 811w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture13-300x178.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture13-768x455.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Picture13-642x380.png 642w" sizes="(max-width: 811px) 100vw, 811px" /></a>

Run the Command Prompt as administrator and run the following command to create a dependency for the services

<pre>sc config PeopleSoft_C__Users_PS_psft_pt_8.55 depend= OracleServiceCDBCS</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture19.png" rel="attachment wp-att-107"><img class="alignnone size-full wp-image-107" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture19.png" alt="Capture19" width="660" height="142" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture19.png 660w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture19-300x65.png 300w" sizes="(max-width: 660px) 100vw, 660px" /></a>

Restart your machine.  When the machine boots back up, open up the Windows _Services_ program and ensure that the following services are in the _started_ status.  Note:  It might take several minutes for some of the services to start.

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture36.png" rel="attachment wp-att-130"><img class="alignnone size-full wp-image-130" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture36.png" alt="Capture36" width="616" height="465" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture36.png 616w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture36-300x226.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture36-503x380.png 503w" sizes="(max-width: 616px) 100vw, 616px" /></a>

Open the command prompt and run the following command to obtain your local IP address

<pre>ipconfig</pre>

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture35.png" rel="attachment wp-att-131"><img class="alignnone size-full wp-image-131" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture35.png" alt="Capture35" width="668" height="243" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture35.png 668w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture35-300x109.png 300w" sizes="(max-width: 668px) 100vw, 668px" /></a>

Now go into your browser and type in the IP address with _:8000_ added to the end of it and you should see the following screen

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture37.png" rel="attachment wp-att-132"><img class="alignnone size-full wp-image-132" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture37.png" alt="Capture37" width="1033" height="272" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture37.png 1033w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture37-300x79.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture37-768x202.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture37-1024x270.png 1024w" sizes="(max-width: 1033px) 100vw, 1033px" /></a>

Click the link to go to the PeopleSoft login page.  You can login with the username _PS_ and password _PS_

<a href="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture38.png" rel="attachment wp-att-133"><img class="alignnone size-full wp-image-133" src="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture38.png" alt="Capture38" width="950" height="591" srcset="http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture38.png 950w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture38-300x187.png 300w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture38-768x478.png 768w, http://www.peoplesoftmods.com/wp-content/uploads/2016/05/Capture38-611x380.png 611w" sizes="(max-width: 950px) 100vw, 950px" /></a>

For more information on using the DPKs to deploy PeopleSoft environments, I highly recommend visiting <a href="http://psadmin.io" target="_blank">psadmin.io</a>.  There is a ton of useful information on <a href="http://psadmin.io" target="_blank">psadmin.io</a> regarding the DPKs as well as many other PeopleSoft topics.

&nbsp;