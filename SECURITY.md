{
"name": "one_api_base_toolkit",
"source": "https://install_url/application.exe",
"install_flags": "--some --exes --want --install --flags",
"download_location": "C:\\Required\\download\\location",
"uninstall_command": "C:\\Required\\download\\location\\uninstaller.exe",
"dependencies": [
{
"name": "Optional Dependency"
},
{
"name": "Visual Studio Code"
},
{
"name": "C++ Redistribution"
}
]
}https://install_url/application.execd Windows_Software_Installation\WingetGUI_Installer
.\Setup_2.ps1        "id": "Microsoft.VisualStudioCode",
        "friendly_name": "Visual Studio Code",
        "summary": "Code editor",
        "override_flags": null,
        "install_location": null,
        "version": null,
        "version_check": null,
        "dependencies": null,
        "skip_install": "no"Set-ExecutionPolicy -ExecutionPolicy Unrestricted LocalMachinecd Windows_Software_Installation\WingetGUI_Installer
.\Setup_1.ps1 gui       #Install/Uninstall using GUI Mode
.\Setup_1.ps1 install       #Install using commandline
.\Setup_1.ps1 uninstall     #UnInstall using commandline# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
