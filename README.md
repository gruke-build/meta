<table align="center">
    <tr>
        <td align="center" width="25%">
            <img src="https://raw.githubusercontent.com/gruke-build/src/refs/heads/develop/images/icon-social.png" alt="gruke" >
        </td>
        <td align="center" width="75%">
          
# GRUKE meta files

A set of helper scripts, served by Cloudflare redirect rules from my domain.

These are helpers for installing & updating the *global tool*. Utilities for creating & updating GRUKE project scripts are contained within the global tool.

[![Discord](https://img.shields.io/discord/405806471578648588?color=5865F2&label=Greem%27s%20Projects&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/H8bcFr2)
        </td>
    </tr>
</table>

- `install-nuke.greemdev.net` -> [`install-global-tool.sh`](https://github.com/gruke-build/meta/blob/main/install-global-tool.sh)
- `update-nuke.greemdev.net` -> [`update-global-tool.sh`](https://github.com/gruke-build/meta/blob/main/update-global-tool.sh)
- `install-nuke.greemdev.net/alpha` -> [`install-prerelease-global-tool.sh`](https://github.com/gruke-build/meta/blob/main/install-prerelease-global-tool.sh)
- `update-nuke.greemdev.net/alpha` -> [`update-prerelease-global-tool.sh`](https://github.com/gruke-build/meta/blob/main/update-prerelease-global-tool.sh)

<details>

<summary>Install latest GRUKE release</summary>

- Bash: `curl -Ls https://install-nuke.greemdev.net | bash`
- Zsh: `curl -Ls https://install-nuke.greemdev.net | zsh`
- PowerShell: `iex ((New-Object System.Net.WebClient).DownloadString('https://install-nuke.greemdev.net'))`

</details>

<details>

<summary>Update to latest GRUKE release</summary>

- Bash: `curl -Ls https://update-nuke.greemdev.net | bash`
- Zsh: `curl -Ls https://update-nuke.greemdev.net | zsh`
- PowerShell: `iex ((New-Object System.Net.WebClient).DownloadString('https://update-nuke.greemdev.net'))`

</details>

<details>

<summary>Install latest GRUKE pre-release</summary>

- Bash: `curl -Ls https://install-nuke.greemdev.net/alpha | bash`
- Zsh: `curl -Ls https://install-nuke.greemdev.net/alpha | zsh`
- PowerShell: `iex ((New-Object System.Net.WebClient).DownloadString('https://install-nuke.greemdev.net/alpha'))`

</details>

<details>

<summary>Update to latest GRUKE pre-release</summary>

- Bash: `curl -Ls https://update-nuke.greemdev.net/alpha | bash`
- Zsh: `curl -Ls https://update-nuke.greemdev.net/alpha | zsh`
- PowerShell: `iex ((New-Object System.Net.WebClient).DownloadString('https://update-nuke.greemdev.net/alpha'))`

</details>
