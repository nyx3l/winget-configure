# Winget Configuration
## Description
Use this repository to setup and keep your Windows applications up-to-date!
## Usage
Open Windows Terminal, PowerShell, or Command Prompt and run this:
```
winget configure --accept-configuration-agreements --disable-interactivity -f configuration.dsc.yaml
```
## Contributing
Edit `configuration.dsc.yaml` to add the configurations you want to install and maintain on your system!

Use `winget search` from the command line to search for new packages

Use the [Microsoft Store](https://apps.microsoft.com/home?hl=en-US&gl=US) to search for packages too