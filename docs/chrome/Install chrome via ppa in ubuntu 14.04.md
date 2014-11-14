# **Install Chrome**

##### **Step 1: Add Google Chrome PPA File**

> First add the google chrome repository in your system using following commands.
> While using PPA in our system we also receives the latest updates whenever you check for latest updates.

```sh
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
```

##### **Step 2: Install/Upgrade Google Chrome**

> After adding Google chrome repository in our system use following commands to install latest Google chrome stable release. 
> If you already have installed older version, It will upgrade current installed version with recent stable version.

```sh
sudo apt-get update
sudo apt-get install google-chrome-stable
```

##### **Step 3: Start Google Chrome**
> Let's start the chrome using following commands.

```sh
 google-chrome
 	[or]
google-chrome-stable
```