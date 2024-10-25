# myworkstation
A script to setup my laptop. The aim is to get a standardize Windows setup with all my favorites app and tools.

# Install

```powershell
winget import -i winget-export.json --accept-package-agreements
```

`winget-export.json` was created with following command:
```powershell
winget export -o winget-export.json 
```