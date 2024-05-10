# Disertation Project

# Applications:

Composer:
    [Composer Exe installer](https://getcomposer.org/Composer-Setup.exe)
    
NodeJs: 
    [NodeJs msi installer](https://nodejs.org/dist/v20.13.1/node-v20.13.1-x64.msi)
    
XAMPP:
    [XAMPP Exe Installer](https://altushost-swe.dl.sourceforge.net/project/xampp/XAMPP%20Windows/8.2.12/xampp-windows-x64-8.2.12-0-VS16-installer.exe?viasf=1)
    
sau
    [XAMPP download page](https://www.apachefriends.org/download.html)
    
Git:
    [Git Downloads Page](https://git-scm.com/downloads)
    

# Installation Process:

## Git clone the project using cmd or powershell on Desktop or any folder.
    git clone https://github.com/mariananghel05/Disertation2

## Run following commands in order to setup the project!
Composer 

    composer install
NodeJs
    
    npm install 
    npm run prod

Larave # IMPORTANT!! (first run XAMPP control and create a named "laravel" database before running!)

    php artisan migrate
    php artisan storage:link
