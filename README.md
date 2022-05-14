# Troubleshooting-Logs
This is a repo of all the errors that I have faced and have successfully fixed in my Data Science career. This will be a active log and shall help others to refer this 

1. Annaconda doesn't open after uninstalling or reinstalling Anaconda. 
   FIx: Run the following command on powershell in admin mode: C:\Windows\System32\reg.exe DELETE "HKCU\Software\Microsoft\Command Processor" /v AutoRun /f
