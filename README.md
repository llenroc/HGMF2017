# HGMF2017
The unofficial app of the 2017 Duluth Homegrown Music Festival

## Setup

### App
1. Install Visual Studio 2017 + the optional Xamarin tools during installation OR install Visual Studio for Mac.
2. Rename the `SettingsTemplate.cs` file (not included to the solution) to `Settings.cs`.
3. Replace all the values in `Settings.cs` with your various API keys.

### Backend
1. Deploy the files from the `Backend` folder to an Azure Functions instance.
2. Update the URL of your Azure Function in the `DuluthHomegrown2017/Data/AzureFunctionDayDataSource.cs` file.
