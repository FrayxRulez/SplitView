# SplitView for 8.1

Introduction
============
This repository contains a porting of SplitView control (Available in Windows 10) for Runtime 8.1.

Properties are the same, so if in future you want to port your app to 10 you have just to remove the Universal.UI.Xaml.Controls namespace.

The code is released under the MIT/X11, so feel free to modify and share your changes with the world.

How to
======
This control support both Windows and Windows Phone 8.1 but base-sizes are thinked for Phone.
If you want to use this control in a Windows app you have just to edit `SplitViewOpenPaneThemeLength` and `SplitViewCompactPaneThemeLength` in **Themes\Generic.xaml** or override them in your **App.xaml** (Or where you want)

Documentation available [here].

Install
=======
To use this control you have just to add the project to your solution.
A [NuGet] package is not available at this time.

[NuGet]:http://nuget.org/
[here]:https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.splitview.aspx
