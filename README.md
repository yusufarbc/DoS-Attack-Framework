# DoS Attack Framework 
DoS Attack Framework is a whiptail project that facilitate to perform DOS attack with hping3 tool. Whiptail is a TUI(Text User Interface) environment running in linux terminal.

## Getting Started
--------------------------------------
First of all, you must be root privileges to run this script. When the script runs, you will see the welcome message screen. To pass the next screen hit enter. You will see an alert in that screen. 

DO NOT USE FOR MALICIOUS ACTIVITY.

![image](https://github.com/yusufarbc/DOS-ATTACK-FRAMEWORK/assets/77548038/5fbb7563-85cf-469a-b30a-815d3620696f)

When you pass the alert message, you must enter target IP and port address. If you select cancel with tab button, you exit from the script interface.

![image](https://github.com/yusufarbc/DOS-ATTACK-FRAMEWORK/assets/77548038/ac6c8d0a-7d76-44f1-b626-b6e5cad2d292)

![image](https://github.com/yusufarbc/DOS-ATTACK-FRAMEWORK/assets/77548038/882b02ec-54e8-4600-a9a3-f67cedc2b7e8)

After target information, you can select the attack type from that menu.

![image](https://github.com/yusufarbc/DOS-ATTACK-FRAMEWORK/assets/77548038/581244cc-d4c3-4c86-a3a7-7d0f06df1998)

After that you will see a confirmation message. If you select yes, the attack will start. If you select no, you come back the menu.

![image](https://github.com/yusufarbc/DOS-ATTACK-FRAMEWORK/assets/77548038/e9db8058-0a9d-41bf-b39a-35e00e2f3579)

## Prerequisites
--------------------------------------
DoS Attack Framework uses hping3 and Whiptail. So you have to make sure them already installed. The script is only runs on a linux machine.

## Installation
--------------------------------------
After ensuring the perform prerequisites, you can download dos-console.sh file from this repository. First of all, ensure the hping variable in the script is true directory of the hping3 tool. Then, you can position the script file in the directory you want and grant execution permission. If you move the script in the /bin directory you can easily run the script with 'dos-console' command. Remember you must be root priveleges to run this script.

```sh
sudo su

chmod +x dos-console.sh

./dos-console.sh
```

## Issues
--------------------------------------
If you find a bug you can report from github. The project is open any contribution.
