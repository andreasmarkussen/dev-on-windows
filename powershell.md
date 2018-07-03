# How to make Powershell great again



## NPM Autocomplete

    Install-module -Name TabExpansionPlusPlus -AllowClobber
    Install-module -Name NPMTabCompletion
   

Then add this to your profile  

Open your profile 
    
    notepad $PROFILE

Insert these statements

    Import-Module TabExpansionPlusPlus
    Import-Module NPMTabCompletion


## Remove the sounds!!

While you are in your profile, turn off the sound

   Set-PSReadlineOption -BellStyle None

## Git 

[PowerShell GIT Client](https://github.com/dahlbyk/posh-git)

    choco install poshgit

