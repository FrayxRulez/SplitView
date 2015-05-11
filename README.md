# SplitView for 8.1

Introduction
============
This repository contains a porting of SplitView control available in Windows 10 for Runtime 8.1 and Silverlight 8.X

Properties are the same, so if in future you want to port your app to 10 you have just to remove the Universal.UI.Xaml.Controls namespace.

The code is released under the MIT/X11, so feel free to modify and share your changes with the world.

How to
======
### Runtime
This control support both Windows and Windows Phone 8.1 but base-sizes are thinked for Phone.
If you want to use this control in a Windows app you have just to edit `SplitViewOpenPaneThemeLength` and `SplitViewCompactPaneThemeLength` in **Themes\Generic.xaml** or override them in your **App.xaml** (Or where you want)

### Silverlight
In Silverlight the control uses PhoneChromeBrush as PaneBackground.

Default values are 480px for `SplitViewOpenPaneThemeLength`, 72px for `SplitViewCompactPaneThemeLength`.


### Documentation
Documentation available [here].

Install
=======
To use this control you have just to add the project to your solution.
A [NuGet] package is not available at this time.

[NuGet]:http://nuget.org/
[here]:https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.splitview.aspx
