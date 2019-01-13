<img src="https://raw.githubusercontent.com/kleinrein/dot-spinners/master/DotSpinners.Resources/DotSpinners.png" width="150">

[![NuGet](https://img.shields.io/nuget/dt/DotSpinners.svg)]()
[![NuGet](https://img.shields.io/nuget/v/DotSpinners.svg)]()

# Dot Spinners
Console spinners in .NET

<img src="https://github.com/kleinrein/dot-spinners/blob/master/DotSpinners.Resources/DotSpinners.gif" width="600">

## Install
```posh
Install-Package DotSpinners 
```
[Nuget](https://www.nuget.org/packages/DotSpinners/)

## Usage
The public API is small and supports method chaining.
```c#
private static async Task DoWork() => await Task.Run(() => DoMoreWork());

// Spin until passed task is completed
new DotSpinner(SpinnerTypes.Pulse, DoWork()).Start();
```

### Spinnertypes
There are 30 spinner types to choose from. All of them can be found in this comma-separated file:
https://github.com/kleinrein/dot-spinners/blob/master/DotSpinners/spinners.txt

## License
[The MIT License (MIT)](https://opensource.org/licenses/MIT)
