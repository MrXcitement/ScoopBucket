# Scoop Bucket Template

[![Tests](https://github.com/mrxcitement/ScoopBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/mrxcitement/ScoopBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/mrxcitement/ScoopBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/mrxcitement/ScoopBucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.
This bucket contains a small selection of tools that are not in the official Scoop buckets.
To add bucket, type `scoop bucket add MrXcitement https://github.com/MrXcitement/ScoopBucket` from Powershell.

Tool | Description | Website
-- | -- | --
[pipx](./bucket/pipx.json) | A utility to install Python programs as standalone apps | https://pypa.github.io/pipx/
[johns-background-switcher](./bucket/johns-background-switcher.json) | John’s Background Switcher: periodically changes the background image on your Windows computer to something awesome | https://johnsad.ventures/software/backgroundswitcher/windows/

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add ScoopBucket https://github.com/mrxcitement/ScoopBucket
scoop install ScoopBucket/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
