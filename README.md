# Unity Version Selector

<center><img src="https://github.com/GeneralD/Unity-Version-Selector/blob/master/Unity%20Version%20Selector.app/Contents/Resources/Icon.icns?raw=true" width="180px"></center>

## Usage

* Touch the directory ~/Developer/Unity_Versions and move /Application/Unity to ~/Developer/Unity_Versions/[0-9].[0-9].[0-9]\(p|f\)[0-9] \(<- version name\).
 
* Rename Unity project's root directory to *.unityproj.

* Now, you can open the *.unityproj with double click!
 

<center><img src="https://github.com/GeneralD/Unity-Version-Selector/blob/master/Unity%20Version%20Selector.app/Contents/Resources/DocumentIcon.icns?raw=true" width="55px"></center>


```
mkdir -p ~/Developer/Unity_Versions
# if installed version is 5.6.0p2...
mv /Application/Unity ~/Developer/Unity_Versions/5.6.0p2
# if you've have a unity project directory...
mv AnyUnityProject Any\ Unity\ Project.unityproj # space ok!
# Now, you can open .unityproj with suited version of Unity
open Any\ Unity\ Project.unityproj # or double-click!
```

## Unity Version Selector 2017?

Unity Version Selector 2017.app requires '/usr/local/bin/gsort' command but it can also support unity version of 2017.

On the other hand, Unity Version Selector.app only supports Unity 5.x.x or 4.x.x. 