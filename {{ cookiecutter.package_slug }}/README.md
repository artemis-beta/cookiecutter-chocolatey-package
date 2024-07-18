# {{ cookiecutter.project_title }} Chocolatey Package
Allows the installation of [{{ cookiecutter.project_title }}]({{ cookiecutter.project_url }}) by {{ cookiecutter.project_authors }} via the [Chocolatey Package Manager](https://community.chocolatey.org/) for Windows. The setup will install {{ cookiecutter.project_title }} on a Windows system.

## Install
```pwsh
choco install {{ cookiecutter.package_slug }}
```

## Uninstall
```pwsh
choco uninstall {{ cookiecutter.package_slug }}
```

## Upgrade
```pwsh
choco upgrade {{ cookiecutter.package_slug }}
```
