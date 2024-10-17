# AlphaShell-Terminal-bash
## Orginal files

AlphaShell-Host/Server-Terminal-bash

 <p align="center">
<img src="https://yt3.googleusercontent.com/6_gl3yD2a7kDSTrqua1O93qNxukmlfZm0fU7Lt3C5DmwF50bHD5V_u_1CfTsbjNn6Xdjqqjmc9c=w1060-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj" >
</p>

# Full Package

Depending on the scope of changes and feature enhancements that are added to an existing web shell’s source code, these updates can be tedious and time consuming for bad actors. For this reason, it’s common to see code for web shells reused among different, unaffiliated attackers.

 <p align="center">
<img src="https://github.com/4lph4shell/AlphaShell-Terminal-bash/blob/master/316.png" >
</p>

# Alfa-Shell-v7.4.7-GROM

 <p align="center">
<img src="https://github.com/4lph4shell/AlphaShell-Terminal-bash/blob/master/03.png" >
</p>


The ALFA-TEaM shell contains an enormous number of features, the latest version v7.4.7.
When comparing v7.47’s PHP code, we can see the following new features, which are not present in v3 of the web shell:
 <p align="center">
<img src="https://github.com/4lph4shell/AlphaShell-Terminal-bash/blob/master/Screenshot%202024-10-17%20194213.png" >
</p>

The first three are just variations of existing features (e.g coldumper) and relatively common among multi-featured PHP web shells.
Let’s focus on the behavior of the last three features: ** fakepage, config_grabber, and archive_manager. ** 

# Fake Page 
In my opinion, ** fakepage ** is of the most interesting new features added to v7.4.7. It allows the attacker to create an on-the-fly phishing page for the two most common hosting control panels: cPanel and DirectAdmin.
 <p align="center">
<img src="https://blog.sucuri.net/wp-content/uploads/2020/10/alfa_team_web_shell_phishing_page.gif" >
</p>
As demonstrated above, there are a few parameters that the attacker can input when setting up the fake control panel page from the web shell. I’ve explained them in more detail below to help you understand what is going on here.
# config_grabber
 <p align="center">
<img src="https://blog.sucuri.net/wp-content/uploads/2020/10/alfa_team_web_shell_config_grabber.png" >
</p>

This feature is used to recursively search for configuration files. It uses two functions; alfaconfig_grabber for the display in the web shell and Alfa_ConfigGrabber for performing the search.

While in theory this could be a potentially helpful feature, these searches return many files (as seen above), including those that don’t contain any MySQL database user login information whatsoever. This is due to greedy search terms contained in the $pattern function, causing it to return a lot of unneeded results.

# Archive Manager
 <p align="center">
<img src="[https://blog.sucuri.net/wp-content/uploads/2020/10/alfa_team_web_shell_config_grabber.png](https://blog.sucuri.net/wp-content/uploads/2020/10/alfa_team_web_shell_archive_manager.gif)" >
</p>
The Archive Manager feature allows the attacker to quickly unpack archive files (e.g .zip, .tar.gz, .gz, etc) into the server’s memory by generating a Phar PHP resource. The attacker can then manage the contents as if they had unpacked the archive in a file manager, but it is instead loaded into memory and doesn’t unpack to a directory.

# Conclusion
 <p align="center">
<img src="https://github.com/4lph4shell/AlphaShell-Terminal-bash/blob/master/312.png" >
</p>

** ALFA TEaM Shell ~ v7.4.7-GROM ** contains a lot of features useful to an attacker and is also polished in terms of its interface. What is especially interesting is to observe the evolution of the tool and see what features have been added with each new version. This also helps give someone insight into what is important to an attacker, not solely from a website owner’s perspective.



 
## ⚠️ WARNING: LEGAL DISCLAIMER

This tool is intended for **educational and ethical use only**. The author is not liable for any illegal use or misuse of this tool. Users are solely responsible for their actions and must ensure they have explicit permission to scan the target systems.
 <p align="center">
<img src="https://github.com/4lph4shell/AlphaShell-Terminal-bash/blob/master/319.png" >
</p>

## 🌐 Socials:
[![website](https://img.shields.io/badge/🐺-website-4EA94B.svg?&logo=web&logoColor=white)](https://www.4lph4.ir) <br/>
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/4lph4.co) <br/>
[![telegram](https://img.shields.io/badge/Telegram-2CA5E0.svg?&logo=telegram&logoColor=white)](https://t.me/ALPH4Co) 
[![telegram](https://img.shields.io/badge/Telegram-Topic-2CA5E0.svg?&logo=telegram&logoColor=white)](https://t.me/ALPH4ir) <br/>
[![youtube](https://img.shields.io/badge/You-tube-%23E4405F.svg?logo=youtube&logoColor=white)](https://www.youtube.com/@4lph4co) 

<img src="https://yt3.googleusercontent.com/6_gl3yD2a7kDSTrqua1O93qNxukmlfZm0fU7Lt3C5DmwF50bHD5V_u_1CfTsbjNn6Xdjqqjmc9c=w1060-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj" >
