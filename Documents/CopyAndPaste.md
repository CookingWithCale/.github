# Cooking with Cale.Documents.CopyAndPaste

## Console

Get-ChildItem -Recurse -Include *.ps1 | Rename-Item -NewName { $_.Name.replace(".ps1",".ps1.bak") }

