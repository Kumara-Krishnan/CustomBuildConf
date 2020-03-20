Reproduces an issue with Microsoft.UI.Xaml nuget package in UWP App.

When a custom build configuration is used, TypeLoadException is thrown and crashes the app during OnLaunched.

It works fine for default configs Debug and Release.

This is a sample to reproduce the mentioned issue.