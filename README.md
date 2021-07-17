## Langkah-langkah
1. Install PowerShell 7 https://github.com/PowerShell/PowerShell/releases
2. Install Windows Terminal https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab
3. Install Nerd Fonts https://www.nerdfonts.com/ (ex: UbuntuMono NF)
4. Setting PowerShell untuk menggunakan Nerd Fonts terpilih (settings>powershell 7>appearance)
5. Install terminal icons PS> Install-Module -Name Terminal-Icons -Repository PSGallery
6. Buat profil Power Shell PS> New-Item -Path $PROFILE -Type File -Force
7. Edit PowerShell profile \Documents\PowerShell\Microsoft.PowerShell_profile.ps1
8. Tambahkan Import-Module -Name Terminal-Icons di file tersebut
9. install Oh My Posh https://ohmyposh.dev/ (PS> Install-Module oh-my-posh -Scope CurrentUser)
10. Edit PowerShell profile untuk menambahkan Set-PoshPrompt -Theme slim
11. Pilih Theme dapat melihatnya dingan cara PS> Get-PoshThemes
12. Setting VSCode Terminal fonts di File>Preferences>Settings 
13. Cari Terminal>Integrated:Font Family dan sesuaikan dengan Nerd Fonts pilihan diposisi paling kanan (ex: UbuntuMono NF, ...)
14. Atur Font size juga agar ramah mata
