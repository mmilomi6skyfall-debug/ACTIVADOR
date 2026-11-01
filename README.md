PS C:\Users\MILO_> Get-ChildItem "${env:ProgramFiles}\Microsoft Office","${env:ProgramFiles(x86)}\Microsoft Office" -Filter OSPP.VBS -Recurse -ErrorAction SilentlyContinue | Select-Object -ExpandProperty FullName# ACTIVADOR
irm https://massgrave.dev/get | iex
