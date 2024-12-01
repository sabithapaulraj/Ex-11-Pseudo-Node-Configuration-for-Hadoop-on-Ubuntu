# Ex-11-Pseudo-Node-Configuration-for-Hadoop-on-Ubuntu

## AIM

To implement Pseudo Node configuration for Hadoop on ubuntu.

## Hadoop Installation Overview

## Pre-requisites

a) jdk

Single-Node Configuration

1.	Create a dedicated user account for hadoop

![1](https://github.com/user-attachments/assets/92c1e563-c5f1-47fb-b37b-7d5e12b31164)

2.	Install java1.8 in folder /usr/local

![2](https://github.com/user-attachments/assets/5ea2d3ed-90dc-445a-bf33-c11e3cfc34a3)

3.	Install Hadoop

![3](https://github.com/user-attachments/assets/ffda2502-c6a3-4fd3-8295-9f3dfc1ba252)

4.	Set the hadoop environment variables: Include the following lines in the
$HOME/.bashrc file

![4](https://github.com/user-attachments/assets/d1c52226-f8dd-4d3f-b745-6c1691b8d064)

5.	Set hadoop environment variables: Include the following lines /etc/profile file

![5](https://github.com/user-attachments/assets/696d8da4-a010-4538-8b2e-4bc1ab00960a)

6.	Run the.bashrc & profile files from the $ prompt for updating the changes


![6](https://github.com/user-attachments/assets/77f349a6-4631-449e-bb03-b77c0f3ce87a)
<br>![7](https://github.com/user-attachments/assets/99438a71-e073-46b2-ba1e-3188d2956b80)

$ bin/hadoop version	


7.	Configuration of the hadoop files: hadoop-env.sh, core-site.xml, mapred-site.xml, hdfs- site.xml and yarn-site.xml


path ::	/usr/local/hadoop-2.5.1/etc/hadoop

a)	hadoop-env.sh

Include the following lines in hadoop-env.sh file

![8](https://github.com/user-attachments/assets/c1b537c1-19ba-49fa-b30a-6ad3560fa72a)

b)	core-site.xml

Configure the directory for Hadoop to store its data files, the network ports it listens to, etc. Setup will use Hadoop’s Distributed File System (HDFS-single local machine)

![9](https://github.com/user-attachments/assets/b54388b5-4e27-4ca9-b226-4ea8b993f5a0)
 
Include the following lines in core-site.xml file between <configuration> and

</configuration> tags

![10](https://github.com/user-attachments/assets/ac0c1344-a0ed-4ab3-83f1-3ca31d59205a)<br>

c)	mapred-site.xml

<img src="https://github.com/user-attachments/assets/4e182fa8-e530-4eec-9b40-53a0a14777a0" width="35%" /><br>


Include the following lines in mapred-site.xml file
 
<img src="https://github.com/user-attachments/assets/d7412a43-c500-440a-8367-ebb97f11a15a" width="35%" /><br>


d)	hdfs-site.xml

Include the following lines in hdfs-site.xml file

<img src="https://github.com/user-attachments/assets/47b39cbc-7e8e-4a4b-9707-02422070ecda" width="30%" />
<br>
e)	yarn-site.xml

Include the following lines in yarn-site.xml file

<img src="https://github.com/user-attachments/assets/35243557-25be-4468-b1d1-4686a61a9397" width="40%" />

8.	Format the Hadoop File system implemented on top of the local file system using

<img src="https://github.com/user-attachments/assets/710df2f1-12ef-42cc-982b-ad37e4cb01fb" width="40%" />


9.	Start Hadoop using

<img src="https://github.com/user-attachments/assets/ff41bcda-3e9a-450e-bca8-bf8858207b39" width="26%" />
<br>
<img src="https://github.com/user-attachments/assets/6012351c-93b9-4c43-b720-92e5d18728be" width="40%" />

Explore Hadoop using http://localhost:50070/ from the browser	
 
10.	The commonly used HDFS Commands are as follows:

<img src="https://github.com/user-attachments/assets/df6d34e4-5229-4464-906c-66475a8f3989" width="40%" />

<br>11.	Create a directory ‘/input’ in HDFS

<img src="https://github.com/user-attachments/assets/079d266e-6302-478c-8108-7123f6305ddc" width="25%" />


<br>12.	Copy the input files into the distributed file system

<img src="https://github.com/user-attachments/assets/1070e89c-92c6-4085-ad95-c25cb42db862" width="35%" />


<br>13.	Run some of the examples provided

<img src="https://github.com/user-attachments/assets/9652e89c-c5aa-46cb-bcdc-c2781c80f339" width="40%" />

<br>14.	Examine the output files

<img src="https://github.com/user-attachments/assets/accab9ce-79e8-4533-a16e-c0e1108b5f47" width="40%" />


Copy the output files from the distributed file system to the local file system and examine them:

<img src="https://github.com/user-attachments/assets/674e4f4b-0690-4fbb-839f-482c618f738c" width="25%" />


or
View the output files on the distributed file system<br>
<img src="https://github.com/user-attachments/assets/4d69b5ba-c7d6-458d-a004-cb4296eaa228" width="25%" />



## Result:
Thus, the implementation of Pseudo Node configuration for Hadoop on ubuntu is successfully executed.
