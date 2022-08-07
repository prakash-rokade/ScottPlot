# ScottPlot

[![Build and Test](https://github.com/ScottPlot/ScottPlot/actions/workflows/ci.yaml/badge.svg)](https://github.com/ScottPlot/ScottPlot/actions/workflows/ci.yaml)
[![](https://img.shields.io/nuget/dt/scottplot?color=004880&label=Downloads&logo=NuGet)](https://www.nuget.org/packages/ScottPlot/)
[![](https://img.shields.io/nuget/vpre/scottplot?color=%23004880&label=NuGet&logo=nuget)](https://www.nuget.org/packages/ScottPlot/)
[![Discord](https://badgen.net/discord/members/Dru6fnY2UX?icon=discord&color=5562ea&label=Discord)](https://scottplot.net/discord/)

**ScottPlot is a free and open-source plotting library for .NET** that makes it easy to interactively display large datasets. The [**ScottPlot Cookbook**](https://scottplot.net/cookbook) demonstrates how to create line plots, bar charts, pie graphs, scatter plots, and more with just a few lines of code.

* **[ScottPlot Cookbook](https://scottplot.net/cookbook)** 👈 _Learn how to use ScottPlot_

* **[ScottPlot Demo](https://scottplot.net/demo/)** 👈 _See what ScottPlot can do_

* **Quickstart:** 
[**WinForms**](https://scottplot.net/quickstart/winforms/), 
[**WPF**](https://scottplot.net/quickstart/wpf/), 
[**Console**](https://scottplot.net/quickstart/console/), 
[**Avalonia**](https://scottplot.net/quickstart/avalonia/),
[**Eto**](https://scottplot.net/quickstart/eto/), 
[**PowerShell**](https://scottplot.net/quickstart/powershell/), 
[**Notebook**](https://scottplot.net/quickstart/notebook/)

<div align='center'>

<a href='https://scottplot.net'><img src='dev/graphics/ScottPlot.gif'></a>

<a href='https://scottplot.net/cookbook'><img src='dev/graphics/cookbook.jpg'></a>

</div>

## Windows Forms Quickstart

**Windows Forms:** Use NuGet to install [`ScottPlot.WinForms`](https://www.nuget.org/packages/ScottPlot.WinForms), drag/drop a `FormsPlot` onto your form, then add the following to your start-up sequence:

```cs
double[] xs = new double[] {1, 2, 3, 4, 5};
double[] ys = new double[] {1, 4, 9, 16, 25};
formsPlot1.Plot.AddScatter(xs, ys);
formsPlot1.Refresh();
```

![](dev/graphics/winforms-quickstart.png)

## More Quickstart Guides
* [**Console Application** Quickstart](https://scottplot.net/quickstart/console/)
* [**Windows Forms** Quickstart](https://scottplot.net/quickstart/winforms/)
* [**WPF** Quickstart](https://scottplot.net/quickstart/wpf/)
* [**Avalonia** Quickstart](https://scottplot.net/quickstart/avalonia/)
* [**Eto Forms** Quickstart](https://scottplot.net/quickstart/eto/)
* [**PowerShell** Quickstart](https://scottplot.net/quickstart/powershell/)
* [**.NET Interactive Notebook** Quickstart](https://scottplot.net/quickstart/notebook/)

## Plot in the Cloud with ScottPlot

**These images are generated by ScottPlot in the cloud.** Every hour an [Azure Function](https://azure.microsoft.com/en-us/services/functions/) hits the [GitHub API](https://docs.github.com/en/rest) to get an updated list of stargazers, then uses ScottPlot to create a figure from this data and saves it to web-accessible blob storage. Since this automatically-generated plot is just a static image accessible by a URL, it can be displayed in places where JavaScript is not permitted (like in this readme file) to display dynamic data.

<p align="center">
  <a href="https://stargraph.z20.web.core.windows.net/scottplot-stars.png?" target="_blank">
    <img src="https://stargraph.z20.web.core.windows.net/scottplot-stars.png?">
  </a>
</p>

<p align="center">
  <a href="https://nugetppt.z20.web.core.windows.net/plots/scottplot.png?" target="_blank">
    <img src="https://nugetppt.z20.web.core.windows.net/plots/scottplot.png?">
  </a>
</p>

**Try it out!** Give us a star and come back in an hour and your name will appear [here](https://stargraph.z20.web.core.windows.net/scottplot-stars.png)

## Major Versions

**✔️ ScottPlot 4** is stable and recommended for all users

**⚠️ ScottPlot 5** is experimental and not recommended for use

See the [roadmap](dev/roadmap.md) and [changelog](https://scottplot.net/changelog) for more information

## ScottPlot Discord Channel

* In July, 2022 maintainers started using the [ScottPlot Discord Channel](https://discord.gg/Dru6fnY2UX) to discuss progress developing the next major version of ScottPlot. Contributors and users are welcome to check it out!

## About ScottPlot

* The [ScottPlot Changelog](https://scottplot.net/changelog/) details the most recent features and bug fixes.

* ScottPlot was created by [Scott W Harden](https://swharden.com/about/) and enhanced by [many contributions](https://scottplot.net/contributors/) from the open-source community.

* ScottPlot is provided under the the permissive [MIT license](LICENSE) and is free to modify and use for any purpose.

* If you enjoy ScottPlot **give it a star!** ⭐