# Prepare development environment
>Last update: 8/30/2017
>
>Author: [Dariusz Porowski](http://DariuszPorowski.MS/about/)

## Table of Contents
1. [(Option 1) Deploy developer environment](#option-1-deploy-developer-environment)
2. [(Option 2) Setup developer machine](#option-2-setup-developer-machine)

## (Option 1) Deploy developer environment
1. Click on **Deploy to Azure** button below.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fdaporolibstg.blob.core.windows.net%2Fshare%2Ftemplates%2Fdevtestlab.json" target="_blank">![Deploy to Azure](https://azuredeploy.net/deploybutton.png)</a>

2. Fill the parameters - for **Resource Group** select **Create new** and input name using a pattern like **\<your initials\>\<today's date in YYYYMMDD format\>**, e.g., **jd20170821**, set **Location** to **West Europe**, input name for **Lab Name** using the same pattern like for Resource Group, e.g., **jd20170821**. For **User Name** and **User Password** you can provide your values or use default: **AzureDev** and **Passw0rd1!**
![Developer environment deployment form](./_img/devtestdeploy.png)

3. Deployment process takes about 1 hour. After successful deployment go to **DevTest Labs** -> **\<your Lab Name\>dtl** (e.g. **jd20170821dtl**) -> **My virtual machines** -> **DevVM**
![DevTest Labs - My virtual machines](./_img/devtestmyvms.png)

4. Click **Connect**, save and open RDP file, and login using default credentials: **DevVM\AzureDev** for username, and **Passw0rd1!** for password.
![DevTest Labs - RDP Connection](./_img/rdpconnectvm.png)

5. Verify that you can run Visual Studio. 

[Scroll to Top](#prepare-development-environment)

## (Option 2) Setup developer machine

[Scroll to Top](#prepare-development-environment)