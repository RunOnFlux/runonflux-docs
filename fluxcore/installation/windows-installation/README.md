# Windows Installation

Hello everyone, welcome to the FluxCore installation guide for Windows. This guide will walk you through the process of installing FluxCore on your Windows-based machine. The officially recommended Windows versions are Windows 10, 11, and newer. While versions lower than Windows 10 may work, we haven’t officially tested them and issues may arise. If you encounter any problems, please use the following link to submit a bug report to our support team.

\
**We officially recommend installing the following graphic cards on your Windows OS:**

* **NVIDIA: Version 572**
* **AMD: Version 23**

**Choosing a different driver version should be done at your own discretion and may result in potential issues with certain FluxCore services, such as benchmarking or mining.**

Let’s get started!

1. **Download FluxCore**

* To install FluxCore on Windows, visit [this link.](https://leaderboard.fluxcore.ai/)

_Note: During the Beta phase, as FluxCore lacks an official license, the download may be flagged by Windows Defender. Follow the steps below to address this issue._

<figure><img src="https://cdn-images-1.medium.com/max/800/1*78eJLvfABvvf2jB0RrlMcQ.png" alt=""><figcaption></figcaption></figure>

**2. Addressing Download Issues:**

* Open Windows Defender.\


<figure><img src="https://cdn-images-1.medium.com/max/800/1*5WOwL5Ax-z-mtQunw0Oe5g.png" alt=""><figcaption></figcaption></figure>

* Select “Virus & Threat Protection” from the left-hand menu.\


<figure><img src="https://cdn-images-1.medium.com/max/800/1*TaLA3lN-TUtnwD2fqKATIQ.png" alt=""><figcaption></figcaption></figure>

* Select “Protection History.”\


<figure><img src="https://cdn-images-1.medium.com/max/800/1*W-sNPMmZF-pjRVWMS93AJw.png" alt=""><figcaption></figcaption></figure>

* Click on “Threat Blocked” and allow the app to make changes to your device.\


<figure><img src="https://cdn-images-1.medium.com/max/800/1*f3HNimwp6_pQYLXMUVeLFg.png" alt=""><figcaption></figcaption></figure>

* Click on “Actions,” then select “Allow” to authorize the app to make changes.
* Re-download the FluxCore client if necessary.

**3. Initiate FluxCore Installation**

* Begin the installation of the application.
* If a “Windows protected your PC” pop-up appears, click “More info” and then select “Run anyway” to authorize the app.

<figure><img src="https://cdn-images-1.medium.com/max/800/1*F1woFIs6mmJt8wCL4quiig.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*vYCZ3NHudlFXT6S0oNt6Kg.png" alt=""><figcaption></figcaption></figure>

**4. Open FluxCore**

* The FluxCore client should automatically open a browser window with the URL. If not, right-click on the FluxCore Icon in the Windows taskbar and select “Open FluxCore.”

**5. Download the Machine ID and Password during the initial installation**

* During Step Two of the installation process, titled “Register Machine,” you will be prompted to download a file that includes your Machine ID and Password. Kindly proceed with the download, as you may require these values later to establish a connection with another FluxCore GUI for remote control purposes.

<figure><img src="https://help.runonflux.io/wp-content/uploads/2023/12/Screenshot-2023-12-14-002030-1024x493.png" alt="" height="493" width="1024"><figcaption></figcaption></figure>

**6. Dependency Installation**

* A small box at the bottom right of the client will indicate the installation of dependencies. This may take some time as FluxCore installs dependencies like TensorFlow, CUDA, and WSL for proper functionality.

### Essential Tips <a href="#essential-tips" id="essential-tips"></a>

If you encounter issues with your FluxCore client, consider the following:

If you experience issues with your FluxCore client running on FluxCore or can not get it running to begin with, we hope this section will be of help for you. There could be two main reasons why you are having Issues with FluxCore on your machine. If both of them do not solve the issue please open a ticket via our support desk

1. Virtualization Not Enabled

* Check if virtualization is enabled on your BIOS.
* Press Ctrl + ALT + ESC to open Task Manager, go to the Performance tab, and check if Virtualization is enabled.

<figure><img src="https://cdn-images-1.medium.com/max/800/0*MlhQGHlbKCEGKsRO.jpg" alt=""><figcaption></figcaption></figure>

* If disabled, follow the provided steps to enable it.\


_Note that the steps below are based on a Windows 11 machine; your system may have different steps. If needed, refer to online resources on how to access the BIOS on your specific system and enable Virtualization._

* Go to Settings.

<figure><img src="https://cdn-images-1.medium.com/max/800/0*ivIOryuJUXndh_xS.png" alt=""><figcaption></figcaption></figure>

* Access “Windows Update”.\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*RfHGJ64L1l_RU204" alt=""><figcaption></figcaption></figure>

* Click on “Advanced Options,” then navigate to “Recovery.”\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*MXbo-0eoY3C0fnxQ" alt=""><figcaption></figcaption></figure>

* Choose “Advanced Startup.” This will initiate a restart of your computer, allowing you to access the BIOS settings.\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*byROeHvl11-wZYSD" alt=""><figcaption></figcaption></figure>

_Note that the following instructions assume that the screens are in German. Please choose the English terms or adjust according to your language settings._

* Access “Troubleshooting”.

<figure><img src="https://cdn-images-1.medium.com/max/800/1*s6i6qqDpBB9zl8Mq-pZCtA.png" alt=""><figcaption></figcaption></figure>

* Click on “Advanced Options”.\


<figure><img src="https://cdn-images-1.medium.com/max/800/1*SkraSWhdpndoA0sl6bYkTw.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*uMn7s6rz4vuFKZr0redTHQ.png" alt=""><figcaption></figcaption></figure>

* Select “UEFI Firmware Settings.” This action will initiate another restart of your machine. Once restarted, you will encounter a new screen similar to this:\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*YsevCm59E1o6i3_w" alt=""><figcaption></figcaption></figure>

* Click on “Advanced” and then navigate to “CPU and Chipset Configuration.”\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*JkfZHXNZMHv7nWhx" alt=""><figcaption></figcaption></figure>

* Ensure that both Intel VT-x and Intel VT-d are enabled.\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*u2Osh0KfqXPkBJD_" alt=""><figcaption></figcaption></figure>

* Click or initiate an exit, ensuring that configurations are saved. This will shut down your machine.\


<figure><img src="https://cdn-images-1.medium.com/max/800/0*rnBTy5IG8IBvnFng" alt=""><figcaption></figcaption></figure>

* Start your machine manually, and it will start normally with the new BIOS settings saved.\


**2. Troubleshooting WSL for FluxCore:**

* For FluxCore to function, WSL needs to run on your machine.
* Windows Subsystem for Linux (WSL) is a feature of Windows that allows you to run a Linux environment on your Windows machine, without the need for a separate virtual machine or dual booting.
* Verify if WSL is activated on your machine. This is typically done automatically during the FluxCore installation.
* To check, enter “Windows Feature” in your search bar and click on the search result.

<figure><img src="https://cdn-images-1.medium.com/max/800/1*hpSeh-FMsjT-Ff1i5l9LXg.png" alt=""><figcaption></figcaption></figure>

* Scroll down the list and ensure that the box next to “Windows Subsystem for Linux” is checked. If not, please check it and click “OK.”
* If you are still experiencing issues, proceed to install WSL manually on your machine.
* Open your Windows PowerShell.

<figure><img src="https://cdn-images-1.medium.com/max/800/1*YLwNKiu-SVMQZYNv9D_Hsg.png" alt=""><figcaption></figcaption></figure>

* Enter the command: \`wsl — install\`

<figure><img src="https://cdn-images-1.medium.com/max/800/1*p34-cfY_g4GTkKMf24ubxw.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*NZxag-JT-fuSYq1cDhRaFg.png" alt=""><figcaption></figcaption></figure>

* This process will install the latest Ubuntu version on your local machine.
* Please enter a username and password.

<figure><img src="https://cdn-images-1.medium.com/max/800/1*ymqPvDvlN6bvdVNYTMGfGA.png" alt=""><figcaption></figcaption></figure>
