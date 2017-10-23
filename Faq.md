# Faq

**What is WPF?**

WPF, which stands for Windows Presentation Foundation, is a Microsoft approach to a GUI framework, used with the .NET framework. 

**Why a WPF Backend in Xamarin.Forms?**

There is a high volume of Windows computers that do not support UWP applications. We talk about computers with Windows 7 and even Windows XP. In addition, there is a very high  community of WPF developers.

**What platforms are supported?**

Windows XP, Windows 7, Windows 8 and Windows 10.

**Can I extend functionallity to new platforms by creating new controls?**

Absolutely!. You can create effects or custom renders in the same way as iOS or Android.

**And what happens with new functionality added in Xamarin.Forms as Forms Embedding?**

WPF Backend supports Forms Embedding!

    var frameworkElement = new ContentPage().ToFrameworkElement();

**What has been used with the Map control?**

Internally the Map control makes use the Bing Maps Windows Presentation Foundation (WPF) Control.

**How can I use all this today?**

Is recommended reading the [How can I try](README.md) section. 

To test this project you must add this two Nuget sources in Visual Studio:

- Xamarin.Forms WPF CI: [https://ci.appveyor.com/nuget/xamarin-forms-wpf-ci](https://ci.appveyor.com/nuget/xamarin-forms-wpf-ci)
- WpfLightToolkit CI: [https://ci.appveyor.com/nuget/wpflighttoolkit-ci](https://ci.appveyor.com/nuget/wpflighttoolkit-ci)
