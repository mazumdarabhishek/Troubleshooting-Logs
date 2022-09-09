# Troubleshooting-Logs
This is a repo of all the errors that I have faced and have successfully fixed in my Data Science career. This will be a active log and shall help others to refer this 

1. Annaconda doesn't open after uninstalling or reinstalling Anaconda. 
   FIx: Run the following command on powershell in admin mode: C:\Windows\System32\reg.exe DELETE "HKCU\Software\Microsoft\Command Processor" /v AutoRun /f

2. In RNNs there are instances where the loss goes to "nan". This can be mostly due to exploding gradients arising from the choice of activation functions. for example relu activation function are notorious for the same reasons. Whever facing such issue, try using centered activation functions like 'tanh'
