# Step One
Read [this](https://gist.github.com/roy-t/2f089414078bf7218350e8c847951255)

# Step Two
Put this instead.
```
<Installation InstalledByMsi="false">
    <InstallationTarget Version="[12.0,17.0)" Id="Microsoft.VisualStudio.VSWinDesktopExpress" />
    <InstallationTarget Version="[12.0,17.0)" Id="Microsoft.VisualStudio.Pro" />
    <InstallationTarget Version="[12.0,17.0)" Id="Microsoft.VisualStudio.Premium" />
    <InstallationTarget Version="[12.0,17.0)" Id="Microsoft.VisualStudio.Ultimate" />
    <InstallationTarget Version="[14.0,17.0)" Id="Microsoft.VisualStudio.Community" />
    <InstallationTarget Version="[14.0,17.0)" Id="Microsoft.VisualStudio.Enterprise" />
  </Installation>
  
  Version 17 is for VS19 (Helpful I know)