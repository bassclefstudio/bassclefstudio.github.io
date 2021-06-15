---
title:  "AppModel"
excerpt: ".NET Standard view-models and services for cross-platform applications"
date: "2021-03-28T00:17:00-05:00"
header:
    overlay_color: "#3c3c64"
    actions:
      - label: "View GitHub"
        url: "https://github.com/bassclefstudio/AppModel"
tags:
  - development
---

Recently, I've been delving more into creating cross-platform apps using the .NET platform. While many cross-platform solutions exist (including [Xamarin](https://dotnet.microsoft.com/apps/xamarin)/[MAUI](https://github.com/dotnet/maui) and [Uno Platform](https://platform.uno/)), many had technical challenges as I went about trying to develop my app - either they were still in development, or were more a cross-platform UI than a cross-platform way to do... well... *anything else*. I created AppModel mostly for myself, as a library that dealt with making everything *but* UI cross-platform. Things like view-models in the MVVM platform, running code on the UI thread, navigation between views, dependency injection and filesystem access, settings storage, notifications... the list goes on. Simply put, my apps start as a .NET Standard project(s) with the models and view-models, which can do basically everything through services and interfaces defined in the core `AppModel` library. Then, I create my platform heads and reference my .NET Standard project and the relevant `AppModel.*` package. Currently, there are platform heads for UWP, WPF, the web (via [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)), and experimental .NET Core console support (although writing MVVM console apps is a bit... *strange*). I'm pretty pleased with the kinds of apps it's allowed me to create, and the ideas I'm currently working on. All the code is open-source (MIT license) on GitHub if you want to click the button on this article's header to delve right in!