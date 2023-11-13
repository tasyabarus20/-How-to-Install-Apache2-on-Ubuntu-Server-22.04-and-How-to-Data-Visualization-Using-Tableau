# How to Install Apache2 on Ubuntu Server 22.04 and How to Data Visualization Using Tableau

# How to Install Apache2
## 1. Login to Ubuntu Server
## 2. Update and upgrade packages
    sudo apt update && sudo apt upgrade
## 3. Install Apache2
    sudo apt install apache2
## 4. Check the applications that have been installed
     sudo ufw app list
## 5. To view the status of Apache2 use the command
    sudo systemctl status apache2
## 6. Display Apache2 in the Browser
check the ip address using the `ip a` command, copy *ip a* in the browser and it will appear like this
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/be33d893-5651-4b28-b8bf-27fe78aa6372)
## 7. Creating a Web <br>
### 7.1 Move to the /var/www/html directory to create the web
    cd /var/www/html
### 7.2 Create a Directory
    mkdir <directory name>
### 7.3 Move to root
    sudo su
### 7.4 Move to the directory that was created
    cd <directory name>
### 7.5 Edit the directory
    nano index.html
### 7.6 Example program
```sh
<h1> HIMASISKO UNSRI 2023 </h1>
```
### 7.7 Output 
`ip a`

![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/545764d0-8a28-48b7-88e9-cf369fa4c30e)

## How to Remote
### 1. CMD
    ssh<server name>@ip a
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/a49d6285-7795-44f2-9206-4b70198504e7)

### 2. PuTTY
1. Enter the ip address on puTTY <br>
2. click open <br>
3. connect once <br>
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/9ea00349-70ef-4be2-85b7-62c95fbcb699)

![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/f3170e71-3d41-43ea-b2f9-40c60fbc2444)

### 3. Linux Mint
```sh
ssh<nama server>@ip a
```
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/91e171e9-79ab-40ca-ba2e-6465c05ff4e7)


