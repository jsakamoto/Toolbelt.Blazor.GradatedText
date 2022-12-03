# Blazor Gradated Text [![NuGet Package](https://img.shields.io/nuget/v/Toolbelt.Blazor.GradatedText.svg)](https://www.nuget.org/packages/Toolbelt.Blazor.GradatedText/)

## Summary

Make your text on Blazor to be with gradation.

![fig1](https://raw.githubusercontent.com/jsakamoto/Toolbelt.Blazor.GradatedText/main/.assets/fig.001.png)

## Usage

Install the `Toolbelt.Blazor.GradatedText` NuGet package to your Blazor project.

```shell
$ dotnet add package Toolbelt.Blazor.GradatedText
```

Open the namespace `Toolbelt.Blazor.Components` in your `_Imports.razor`.

```razor
@* _Imports.razor *@
...
@using Toolbelt.Blazor.Components @* 👈 Add this line *@
```

Surround contents with the `GradatedText` component.

```html
<GradetdText>
  <h1>Hello, World!</h1>
</GradatedText>
```

You will see that contents with gradation.

![fig1](https://raw.githubusercontent.com/jsakamoto/Toolbelt.Blazor.GradatedText/main/.assets/fig.001.png)


## License

[Mozilla Public License Version 2.0](https://raw.githubusercontent.com/jsakamoto/Toolbelt.Blazor.GradatedText/main/LICENSE)
