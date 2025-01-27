# Winget Configuration
## Description
Use this repository to setup and keep your Windows applications up-to-date!
## Getting Started
> NOTE: Make sure you're logged into the Microsoft Store app before starting

Open Windows Terminal (PowerShell)

Enable winget configure
```
winget configure --enable
```

Ensure Git is installed
```
winget install git
```

Clone this repository using Git
```
git clone https://github.com/nyx3l/winget-configure.git
```

## Apply Configuration
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