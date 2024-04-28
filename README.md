Next command to view the current execution policy:
Get-ExecutionPolicy

If it is not set to RemoteSigned or Unrestricted:
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

Type the following command to run your script:
.\the_script.ps1

Set restricted :
Set-ExecutionPolicy Restricted -Scope CurrentUser
