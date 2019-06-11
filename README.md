
OSS Control Repo

If you want to install an agent on an Ubuntu system:
`curl -k https://nh.cargohold.net:8140/packages/current/install.bash | sudo bash`

If a Windows system:
`[Net.ServicePointManager]::ServerCertificateValidationCallback = {$true}; $webClient = New-Object System.Net.WebClient; $webClient.DownloadFile('https://nh.cargohold.net:8140/packages/current/install.ps1', 'install.ps1'); .\install.ps1 -v`


