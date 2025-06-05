# raman_pepper

### Delete the `_ ` from beginning of file names
```powershell
Get-ChildItem -Name "_ *" | ForEach-Object { Rename-Item $_ ($_.Substring(2)) }
```
