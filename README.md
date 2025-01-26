# Winget Configuration
## Description
Use this repository to setup and keep your Windows applications up-to-date!
## Usage
Open Windows Terminal, PowerShell, or Command Prompt and run this:
```
winget configure --accept-configuration-agreements --disable-interactivity -f configuration.dsc.yaml
```

Once you've installed your packages via the configuration file, you can update them all with this single command:
```
winget update --all
```
## Contributing
Edit `configuration.dsc.yaml` to add the configurations you want to install and maintain on your system!

Use `winget search` from the command line to search for new packages from both winget and msstore