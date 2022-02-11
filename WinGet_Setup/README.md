# WinGet Setup

## winget settings

1. Open powershell, and type:

```powershell
winget settings
```

2. Replace everything in **settings.json**.

```json
{
  "$schema": "https://aka.ms/winget-settings.schema.json",

  // For documentation on these settings, see: https://aka.ms/winget-settings
  // "source": {
  //    "autoUpdateIntervalInMinutes": 5
  // },
  "visual": {
    "progressBar": "rainbow"
  },
  "installBehavior": {
    "preferences": {
      "scope": "user",
      "locale": ["en-US", "zh-TW"]
    }
  }
}
```

3. Install necessary apps via **.json** file:

```powershell
winget import -i <path>\winget_source.json --accept-source-agreements --ignore-versions
```

4. Install optional app in same way.

```powershell
winget import -i <path>\optional.json --accept-source-agreements --ignore-versions
```

5. Upgrade to stay latest.

```powershell
winget upgrade --all
```

6. Export your app those could be found on available sources to a json file.

```powershell
winget export -o <path>\winget_source.json -s winget
```
