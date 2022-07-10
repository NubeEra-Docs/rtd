**Lab -1**

**Creating and Login to Windows Instance (by using EC2) – for
Beginners**

Click “Launch instance”.

|image1|\ |image2|

Select “Microsoft Windows Server 2016 Base”.

|image3|\ |image4|

Select “General Purpose”- t2.micro (which is free tier eligible).

|image5|\ |image6|

Click “Next”.

Leave the settings default and click “Next”.

|image7|\ |image8|

Click “Next”.

Leave the default settings and Click “Next”.

|image9|\ |image10|

In Key type as “Name” and value as “Windows 2016 instance”.

|image11|\ |image12|

Click “Next”

In Security group, create a new security group “Testing_Sec_Group”. By
default AWS allows RDP (3389) for management purpose of the server.

|image13|\ |image14|

Click “Review and launch”.

|image15|\ |image16|

Click “Launch”.

|image17|\ |image18|

Create a new key pair and type the name of the key pair then Click
“Downlod key pair”.

|image19|\ |image20|

Click “Launch Instance”.

Now you have created the instance successfully.

|image21|\ |image22|

Click “View Instances”.

You need to wait up to status checks is 2/2.

|image23|\ |image24|

Now you can able to view the public ip address as above (13.127.133.231)
and LAN IP address as (172.31.19.40). Then we need to connect the
instance by using RDP.

Try to connect the server by using mstsc in run command. Then type the
public IP

|image25|\ |image26|

It required password,

|image27|\ |image28|

Now, click connect button,

|image29|\ |image30|

Click “Get Password”button.

|image31|\ |image32|

Then click “”close”.

Click “choose file” and locate the “Eveningaws.pem” file.

.. image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image21.png
   :width: 4.672in
   :height: 2.97241in

Then click “Decrypt password

|image33|\ |image34|

password is highlighted as below.

|image35|\ |image36|

Login to server by using above login credentials.

|image37|\ |image38|

While try to login, security certificate prompts click “Yes”.

|image39|\ |image40|

Now you have successfully login to the Windows 2016 Instance.

|image41|\ |image42|

In start menu, right click then click command prompt (Admin).

|image43|\ |image44|

In command prompt, type ipconfig to view the LAN ip address of the
Windows 2016 server.

|image45|\ |image46|

If you need to shut down the instance for later use click Instance state
Stop. (Public IP address will not change if you restart the instance. If
you stop the instance public ip will change.

|image47|\ |image48|

Otherwise, click Instance state Terminate to shut down the server and
then delete it.

|image49|\ |image50|

.. |image1| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image1.png
   :width: 0.28694in
   :height: 0.18502in
.. |image2| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image2.png
   :width: 6.008in
   :height: 4.63181in
.. |image3| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image1.png
   :width: 0.28681in
   :height: 0.18472in
.. |image4| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image3.png
   :width: 6.5in
   :height: 5.00556in
.. |image5| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image6| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image5.png
   :width: 6.5in
   :height: 5.00556in
.. |image7| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image8| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image6.png
   :width: 6.5in
   :height: 5.01111in
.. |image9| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image10| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image7.png
   :width: 6.5in
   :height: 5.00556in
.. |image11| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image12| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image8.png
   :width: 6.5in
   :height: 5.00556in
.. |image13| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image14| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image9.png
   :width: 6.5in
   :height: 5.00069in
.. |image15| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image16| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image10.png
   :width: 6.5in
   :height: 5.00069in
.. |image17| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image11.png
   :width: 0.38192in
   :height: 0.24627in
.. |image18| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image12.png
   :width: 4.256in
   :height: 3.11788in
.. |image19| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image11.png
   :width: 0.38192in
   :height: 0.24627in
.. |image20| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image13.png
   :width: 5.376in
   :height: 3.92115in
.. |image21| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image22| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image14.png
   :width: 6.5in
   :height: 5.00556in
.. |image23| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image24| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image15.png
   :width: 6.5in
   :height: 5.00556in
.. |image25| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image26| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image16.png
   :width: 3.432in
   :height: 2.15632in
.. |image27| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31528in
   :height: 0.20347in
.. |image28| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image17.png
   :width: 4.58333in
   :height: 2.67708in
.. |image29| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image30| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image18.png
   :width: 6.5in
   :height: 5.01597in
.. |image31| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image19.png
   :width: 0.3472in
   :height: 0.22388in
.. |image32| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image20.png
   :width: 4.456in
   :height: 2.73311in
.. |image33| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image22.png
   :width: 0.41963in
   :height: 0.27082in
.. |image34| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image23.png
   :width: 4.304in
   :height: 2.72679in
.. |image35| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image11.png
   :width: 0.38192in
   :height: 0.24627in
.. |image36| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image24.png
   :width: 4.512in
   :height: 2.72022in
.. |image37| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image19.png
   :width: 0.3472in
   :height: 0.22388in
.. |image38| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image25.png
   :width: 4.60417in
   :height: 2.71875in
.. |image39| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image40| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image26.png
   :width: 4.21875in
   :height: 4.22917in
.. |image41| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image11.png
   :width: 0.38192in
   :height: 0.24627in
.. |image42| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image27.png
   :width: 6.5in
   :height: 5.01111in
.. |image43| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image19.png
   :width: 0.3472in
   :height: 0.22388in
.. |image44| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image28.png
   :width: 6.5in
   :height: 5.00556in
.. |image45| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image19.png
   :width: 0.3472in
   :height: 0.22388in
.. |image46| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image29.png
   :width: 6.5in
   :height: 5.00556in
.. |image47| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image48| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image30.png
   :width: 6.5in
   :height: 4.99722in
.. |image49| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image4.png
   :width: 0.31563in
   :height: 0.20353in
.. |image50| image:: vertopal_9232b711ecb74792b7d474c86b1d6683/media/image31.png
   :width: 6.5in
   :height: 4.99722in
