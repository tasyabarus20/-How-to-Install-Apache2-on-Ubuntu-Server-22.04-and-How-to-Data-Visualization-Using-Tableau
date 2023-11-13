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

# How to Data Visualization Using Tableau
## 1. Install Tableau
## 2. Create Data Visualization in Tableau
1. Connect the data by selecting the file type you have, for example, select Text File. My data is Warmindo Sales
2. Select the file to upload and click open
3. If successful, the data display will look like this
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/2cecc978-67f8-490b-a827-beafbe344084)

4. Click Sheet 1 and rename it to sales trend to perform the first visualization. 
5. Then drag the transaction date to the columns, then drag the sales value data to the rows and display it in the form of bars and lines.
6. Then dual axis and then synchronize so that the summary is the same.
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/99b1bab9-a2c4-4774-a7a9-7d102d7dabae)
7. Next, create a Top Product, to see what products sell best
8. Move to the next sheet and rename it to Top Product
9. Then drag the product name to the rows, next drag the quantity to the coloumns
10. Then we sort them from largest to smallest
11. Then we filter them to show only the Top 5
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/4411ef28-7532-4f53-abec-d7e0beb11c94)
12. Then we will create a visualization for the purchase method using a pie
13. Move to the next sheet and rename it to Purchase Method
14. Then click order type and sales value
15. Then click the pie chart on the top right side
16. Then drag the sales value to the label and change it to percent of total
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/ddac6801-d37c-4747-a70d-ff657815858e)

## 3. Create Dashboard
1. Click new dashboard at the bottom
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/b6589774-d037-4a5e-8698-2ef0147e14e4)

2. Then adjust the size by selecting custom
3. Then select floating to be free to place each sheet on the dashboard as desired
4. Then select text to create a title
5. Then edit as desired starting from blank frames, colors etc.
6. Then drag each sheet to the dashboard and start editing by placing as you wish (freedom because you have chosen floating)
7. Then filter the sales trend section, so that when clicking on one of the data in the sales trend, it will filter all of them

## 4. Dashboard Result
![image](https://github.com/tasyabarus20/Apache2-and-Tableau/assets/150136650/68bd478e-89e0-48a8-b002-1d0a9b725459)

## 5. Link Dashboard
https://public.tableau.com/app/profile/tasya.barus/viz/DashboardPenjualanWarmindo _16985389406590/Dashboard1?publish=yes 
