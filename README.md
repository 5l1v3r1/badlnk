# BADlnk v1.1
## Author: github.com/thelinuxchoice/badlnk
## Twitter: twitter.com/linux_choice
### Read the license before using any part from this code :)
### Reverse Shell in Shortcut File (.lnk)

![bd](https://user-images.githubusercontent.com/34893261/79396149-a6753880-7f51-11ea-9c34-a53ec6cd1388.jpg)

### How it works?

Shortcut file (Microsoft Windows 9.x)
LNK is a file extension for a shortcut file used by Microsoft Windows to point to an executable file. LNK stands for LiNK. Shortcut files are used as a direct link to an executable file, instead of having to navigate to the executable. LNK files contain some basic properties, such as the path to the executable file and the “Start-In” directory. LNK files use a curled arrow to indicate they are shortcuts, and the file extension is hidden (even after disabling “Hide Extensions for Known File Types” in Windows Explorer).
The script creates a .lnk file that points to the user's "cmd.exe" file (located in the default folder C:\Windows\System32\cmd.exe) to run a reverse shell through arguments.

## Legal disclaimer:

Usage of BADlnk for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

### Features:
#### Reverse TCP Port Forwarding using Ngrok.io

### Requirements:
#### Ngrok Authtoken (for TCP Tunneling): Sign up at: https://ngrok.com/signup
#### Your authtoken is available on your dashboard: https://dashboard.ngrok.com
#### Install your auhtoken: ./ngrok authtoken <YOUR_AUTHTOKEN>
#### Target must reboot/re-login after installing the .reg file

### Usage:
```
git clone https://github.com/thelinuxchoice/badlnk
cd badlnk
bash badlnk.sh
```

### Donate!
Support the authors, pay me a coffee:
### Paypal:
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CLKRT5QXXFJY4&source=url
