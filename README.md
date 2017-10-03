# Xamarin.Forms WPF Backend

The purpose of this repository is to show the status of the **WPF backend of Xamarin.Forms**. 

<p align="center">
<img src="https://www.artonik.com/GetImage.ashx?idImage=Images/Main_1040.png" Width="300"/>
</p>

Windows Presentation Foundation (WPF) is the presentation (user-interfaces) sub system of .NET framework. It is used to create user interfaces for Windows operating system. The user interfaces are also known as Windows client applications or Windows applications. 

Xamarin.Forms WPF Backend | 
------ | 
[Xamarin.Forms.Platform.WPF](https://github.com/mohachouch/Xamarin.Forms/tree/wpf-newimpl) |

Xamarin.Forms WPF Backend Samples | 
------ | 
[Movies](https://github.com/mohachouch/xamarin-forms-gtk-movies-sample/tree/wpf) |
[Weather](https://github.com/jsuarezruiz/xamarin-forms-wpf-weather-sample) |
[Hanselman.Forms](https://github.com/mohachouch/Hanselman.Forms/tree/wpf) |
[WeatherApp](https://github.com/mohachouch/MyWeather.Forms/tree/wpf) |

## Xamarin.Forms

Xamarin.Forms provides a way to quickly build native apps for iOS, Android, Windows, macOS and Linux, completely in C#.

Read more about the platform at [https://www.xamarin.com/forms](https://www.xamarin.com/forms).

<p align="center">
<img src="images/movies_screen.png" Width="600"/>
</p>

## Status

Curently, the WPF Backend allows to develop applications, but it is still in development. If you want to know in detail the **status**, navigate to the [Status section](Status.md).

## How can I try?

This is really simple. You can test the latest Xamarin Forms WPF on Nightly build. <br>

This project requires two libraries:
- Xamarin.Forms.Platform.WPF: Xamarin Forms WPF Backend
- WpfLightToolkit: It's a collection of helper functions and custom controls for Xamarin.Forms WPF Backend.

To test this project you must add this two Nuget sources in Visual Studio:

- Xamarin.Forms WPF CI: [https://ci.appveyor.com/nuget/xamarin-forms-wpf-ci](https://ci.appveyor.com/nuget/xamarin-forms-wpf-ci)
- WpfLightToolkit CI: [https://ci.appveyor.com/nuget/wpflighttoolkit-ci](https://ci.appveyor.com/nuget/wpflighttoolkit-ci)

## Performance

Quality is top of the list of priorities. This means stability and performance first and foremost. Constant testing on a huge volume of samples to achieve this goal.

<p align="center">
<img src="images/layout_performance.png" Width="600"/>
</p>

### Fast Renderer

All renderer are fast ! The controls are not embedded into a panel.

Bellow the difference between WPF and UWP.

<table style="width:100%">
  <tr>
    <th>UWP</th>
    <th>WPF</th>
  </tr>
  <tr>
    <td><img src="images/uwp_weather_tree.png" /></td>
    <td><img src="images/wpf_weather_tree.png" /></td>
  </tr>
</table>

## Gallery

Looks good?. In the **[gallery](Gallery.md)** section you have a huge variety of screenshots.

## Feedback

Please use **[GitHub issues](https://github.com/mohachouch/forms-wpf-progress/issues)** for questions, comments, feature requests, or if would like to vote on what others are recommending.

## Faq

Still with doubts or questions?. Do not worry, we have prepared a complete **[Faq](Faq.md)** answering the most common doubts.

## How to Contribute

Are you interesting?. You can contribute!.

Follow the style used by the [.NET Foundation](https://github.com/dotnet/corefx/blob/master/Documentation/coding-guidelines/coding-style.md), with two primary exceptions:

- We do not use the private keyword as it is the default accessibility level in C#.
- We use hard tabs over spaces. You can change this setting in VS 2015 via Tools > Options and navigating to Text Editor > C# and selecting the "Keep tabs" radio option.

Read and follow the [Xamarin.Forms Pull Request template](https://github.com/xamarin/Xamarin.Forms/blob/master/PULL_REQUEST_TEMPLATE.md).

