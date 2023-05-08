[Overview](#overview)\
[Device Access](#access)\
[AppManger Commands](#apmgr_cmds)\
[Additional Info](#add_info)\
[VPN Info](#vpn)\
[Support](#support)

<a name="top"></a>

# Overview <a name="overview"></a>

The Secure DDoS Edge Protection Sandbox provides a developer with an environment to test the Secure DDoS Edge Protection solution which is a Distributed software solution running as a docker-app in NCS Router to detect and mitigate DDOS attacks, by monitoring the Mobile/IOT/User-Equipment originated traffic(GTP-U), with the Controller running in the Cloud with connectivity to the app.

This Sandbox includes a NCS540 device and three Kali Linux instances. The NCS device contains the detector application pre-installed on it which can be verified using the appmgr CLI's. 

Check the below appmgr CLI's for more information on the application running. The user has the privileges to login into the Kali servers to initiate the legitimate/attack traffic. Once the legitimate traffic is started, the user will be able to view the same in the controller dashboard. Access details for the sandbox are given in subsequent tabs.

# Access Details: <a name="access"></a>

After your Sandbox reservation has begun, you must establish a VPN connection to your Sandbox. See the tab "VPN Access" for instructions on VPN. You will also receive software VPN access information and credentials via email once the sandbox environment is ready (~10 mins). Once connected via software VPN you can access the Container Platform UI's and API's via your local browser and console.

And you may access the devices in your lab as follows:
- Kali Servers
  - Kali-1 Legit user:10.10.20.55
  - Kali-2 Attack user:10.10.20.65
  - Kali-3 Protect application:10.10.20.75
  - Access protocol: SSH
  - credentials [demo/cisco123]
- NCS 540
  - NCS 540: 10.10.20.53
  - Access protocol: SSH
  - credentials [client/cisco123]
- Secure DDoS Edge Protection
  - IP Address: http://10.10.20.51.nip.io
  - credentials [admin@example.com/12345]

**OR Table format**
				
| Component | IP Address | Port | Method | Username | Password |
| --- | ----- |------ |------------- |----- |--- |
| vBond | 10.10.20.80 | 22| SSH. | admin | C1sco12345 |
| vBond | 10.10.20.80 | 22| SSH. | admin | C1sco12345 |
| vBond | 10.10.20.80 | 22| SSH. | admin | C1sco12345 |
| vBond | 10.10.20.80 | 22| SSH. | admin | C1sco12345 |
| vBond | 10.10.20.80 | 22| SSH. | admin | C1sco12345 |



# Additinal Information
  ## IOS XR Appmgr commands: <a name="apmgr_cmds"></a>
  show appmgr source-table\
  show appmgr application-table

  ## Additional Information: <a name="add_info"></a>
  [Cisco Secure DDoS Edge Protection Sandbox Learning Lab](1)\
  [Cisco Secure DDoS Edge Protection Documentation](2)\
  [IOS-XR Learning Labs - Cisco IOS XR on DevNET](3)\
  [Application hosting @ XRdocs.io](4)

[1]: https://developer.cisco.com/learning/lab/secure-ddos-edge-protection/step/
[2]: https://developer.cisco.com/docs/secure-ddos-edge-protection/
[3]: https://developer.cisco.com/learning/tracks/iosxr-programmability
[4]: https://xrdocs.io/application-hosting/ 

[top](#top)

# VPN Information: <a name="vpn"></a>
Software VPN Access to this Lab:
This tab will explain everything you need to know about how to establish a secure software VPN connection to this lab.  A VPN connection is required for you to interact with the systems and devices in this Lab.  You'll also need to have an active reservation for this Lab.

Stuff You Can (and Should) Do Prior to Your Reservation:
In order to establish a software VPN connection to this Lab, you must download and install Cisco's AnyConnect VPN Client software on any system you plan to use to connect to your Lab.  (And it's ok if you don't do  this until after your reservation has started.  It's all good!)  Here's how you download and install AnyConnect:
Download the Cisco AnyConnect VPN Client software.
Installation Guide for Cisco AnyConnect VPN Client software.

Emails You'll Receive:
When your Lab reservation begins, you will receive several emails communicating important information about the status of your Lab.
The first email is sent to you from the Lab provisioning automation engine, and indicates that resources in your Lab are in the process of being provisioned and tested.  Your Lab is NOT READY yet, but this email will give an estimate of when your Lab will be available.
The second email will be sent to you when your Lab is fully provisioned, tested and READY for you to connect.  In this email you'll find the  information required by AnyConnect to establish a VPN connection to your Lab (Network IP Address, VPN Username, VPN Password).
Connecting to Your Lab:
Once you receive the email that says your Lab is ready, you can begin the VPN connection process.  Here's how you establish a VPN connection to your Lab.
AnyConnect VPN Connection Guide.

[top](#top)


# Sandbox Support Forums <a name="support"></a>

Support:\
[Sandbox Support Forums](https://communities.cisco.com/community/developer/sandbox)\
Contact the sandbox support community if you have problems reserving or accessing the sandbox environment. For any questions on YDK, contact the YDK community on DevNET. For other questions related to the routing platform, you can contact the IOS XR Programmability support forum
