# CleanNugetPackages
TOOLS - How to clean cache nuget packages


First, download the NuGet command line tool from here.

https://www.nuget.org/downloads

Next, open a command prompt and cd to the directory to which nuget.exe was downloaded.

You can list the local caches with this command:
```
nuget locals all -list
```
You can clear all caches with this command:
```
nuget locals all -clear
```
