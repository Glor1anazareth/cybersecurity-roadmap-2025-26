# Windows PowerShell

**Room:** [TryHackMe – Windows PowerShell](https://tryhackme.com/room/windowspowershell)
**Status:** In Progress

## Summary
Practiced PowerShell cmdlets for file/directory management and module
discovery — creating, copying, removing items, and reading file contents.

## Key Commands
\`\`\`powershell
New-Item -Path ".\captain-cabin\captain-wardrobe" -ItemType "Directory"
Copy-Item -Path .\captain-hat.txt -Destination .\captain-cabin\
Get-ChildItem -Path ".\captain-cabin\"
Remove-Item -Path ".\captain-cabin\captain-wardrobe\captain-boots.txt"
Get-Content -Path ".\captain-hat.txt"
Find-Module -Name "PowerShell*"
Install-Module -Name "PowerShellGet"
\`\`\`

## Notes
- `Copy-Item` / `Move-Item` are PowerShell equivalents of `copy` / `move`
- `Get-Content` works like `cat` (Linux) or `type` (CMD)
- Connected to a remote target over SSH via Remmina to complete lab tasks

## Evidence
<img width="1920" height="1080" alt="powershell creating and removing items" src="https://github.com/user-attachments/assets/f6744430-34fc-41c0-96a3-188f4caa4cc4" />
<img width="1920" height="1080" alt="powershell commands" src="https://github.com/user-attachments/assets/525a3bf3-9a8f-45fb-9129-174b2025b059" />

