# .net-sample-projects
Different sample projects using .NET

## Windows Test Service (.NET framework)
1. Build app
2. Open VS Developer cmd / powershell with administrative rights

### Install Service
Run `installutil WindowsTestService.exe`

### Uninstall Service
Run `installutil /u WindowsTestService.exe`

## Windows Test Service (.NET 6)
This is a more modern approach.

1. Build app
2. Open VS Developer cmd / powershell with administrative rights

### Install Service
Run `sc.exe create ".NET Test Service" binpath="C:\Path\To\App\net6.0-windows\WindowsTestServiceNET6.exe"`

### Uninstall Service
Run `sc.exe delete ".NET Test Service`
