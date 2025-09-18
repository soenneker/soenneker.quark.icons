[![](https://img.shields.io/nuget/v/soenneker.quark.icons.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.quark.icons/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.quark.icons/publish-package.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.quark.icons/actions/workflows/publish-package.yml)
[![](https://img.shields.io/nuget/dt/soenneker.quark.icons.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.quark.icons/)
[![](https://img.shields.io/badge/Demo-Live-blueviolet?style=for-the-badge&logo=github)](https://soenneker.github.io/soenneker.quark.icons/)

# ![](https://user-images.githubusercontent.com/4441470/224455560-91ed3ee7-f510-4041-a8d2-3fc093025112.png) Soenneker.Quark.Icons
### Minimal, elegant icon component for Quark. Uses Bootstrap 5 classes and expects Font Awesome to be available in the host app.

## Installation

```
dotnet add package Soenneker.Quark.Icons
```

Ensure the host app includes Font Awesome CSS (CDN or local).

## Registration

```
services.AddIconAsScoped();
```

## Usage

```
<Icon Name="check" />
<Icon Name="user" Size="@Size.Large" />
```
