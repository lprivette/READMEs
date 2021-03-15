# README-nawqa
###NAWQA build


----------

##Developer Instructions

After cloning, navigate to nawqa-sw-trends folder, and run `npm install` AND ` bower install` to get dependencies.

run `bower update bootstrap` and enter `3` as your answer for version.

run `bower list` and all dependencies should be installed.

> Does `gulp` or `gulp build` need to be run?

run `gulp watch` to run in browser

For Windows machines it is recommended that Windows Subsystem for Linux (WSL) is used. At the time of writing this WSL version 1 must be used due to a bug in version 2.
    To install WSL:

 1. Go to https://docs.microsoft.com/en-us/windows/wsl/install-win10
 2. Scroll to the section titled "Manual Installation Steps"
 3. Complete steps 1-4
 4. In powershell run the command `wsl --set-default-version 1`
 5. Go to https://docs.microsoft.com/en-us/windows/wsl/install-manual
 6. Select and download a distribution of Linux
 7. Open up a powershell prompt inside the folder that contains the downloaded linux distro
 8. run `Add-AppxPackage .\app_name.appx`, substituting 'app_name' with the name of the file
