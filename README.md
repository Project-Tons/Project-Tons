<div align="center">

<img src="./assets/header.svg" width="100%" alt="Jiro — C#, .NET and WPF developer">

<br>

<a href="https://github.com/Project-Tons/WallpaperTONS-App"><img src="https://img.shields.io/badge/WallpaperTONS-Source-161b22?style=flat-square&logo=github&logoColor=white" alt="WallpaperTONS source"></a>
<a href="https://project-tons.free.nf/"><img src="https://img.shields.io/badge/WallpaperTONS-Website-512BD4?style=flat-square&logo=googlechrome&logoColor=white" alt="WallpaperTONS website"></a>
<a href="https://github.com/Project-Tons/T.O.N.S_Workshop"><img src="https://img.shields.io/badge/T.O.N.S_Workshop-Source-161b22?style=flat-square&logo=github&logoColor=white" alt="Workshop source"></a>
<a href="https://walltons.free.nf/"><img src="https://img.shields.io/badge/T.O.N.S_Workshop-Website-0078D6?style=flat-square&logo=googlechrome&logoColor=white" alt="Workshop website"></a>

</div>

<br>

## About

I build Windows desktop software with **C#, .NET and WPF** — with a focus on custom XAML controls, smooth animations and clean MVVM architecture. I care about apps that feel native, fast and polished.

## Projects

<p align="center">
  <a href="https://github.com/Project-Tons/WallpaperTONS-App"><img src="./assets/card-wallpapertons.svg" width="49%" alt="WallpaperTONS"></a>
  <a href="https://github.com/Project-Tons/T.O.N.S_Workshop"><img src="./assets/card-workshop.svg" width="49%" alt="T.O.N.S Workshop"></a>
</p>

## Stack

<p align="center">
  <img src="./assets/stack.svg" width="100%" alt="Tech stack">
</p>

## How I structure code

```csharp
public sealed partial class WallpaperViewModel : ObservableObject
{
    [ObservableProperty] private bool isTaskbarTransparent;
    [ObservableProperty] private string status = "Ready";

    [RelayCommand]
    private async Task ApplyAsync(WallpaperItem item)
    {
        await _engine.SetLiveWallpaperAsync(item);
        Status = "Applied";
    }
}
```

## Currently

- Building and polishing **WallpaperTONS** and the **T.O.N.S Workshop**
- Exploring **WinUI 3** and advanced composition
- Performance tuning for WPF rendering

<br>

<p align="center"><sub>Make it work, make it right, make it beautiful.</sub></p>
