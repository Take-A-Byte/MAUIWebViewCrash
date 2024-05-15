# WebView Crash on latest iOS

This project reproduces the MAUI application crash on iOS 17.4.
MAUI project can be standard MAUI or MAUI Hybrid project.

## How to reproduce crash?

- Run application with Target as iOS Simulator 17.4
- It will open up https://learn.microsoft.com/en-us/dotnet/maui/user-interface/controls/blazorwebview?view=net-maui-8.0 
- Click on `Search` button

Expected behavior - search box opens
Actual behavior - application crashes

> NOTE
> The application suns fine on older iOS version.
>
> If you want you can replace the website with any other website with search functionality and still the app crashes.