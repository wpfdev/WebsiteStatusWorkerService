# WebsiteStatusWorkerService

The new way to create worker service in ASP.NET Core 3.0

Tutorial:
https://www.youtube.com/watch?v=PzrTiz_NRKA

Install worker as Windows service:
sc.exe create WebsiteStatus binpath= c:\temp\workerservice\WebsiteStatus.exe start= auto

Uninstall worker from Window services:
sc.exe delete WebsiteStatus
