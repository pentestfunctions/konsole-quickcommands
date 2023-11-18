# konsole-quickcommands 🚀

<p align="center">
  <img src="konsole_commands.png" alt="Penetration Testing Assistant Bot Mascot">
</p>

![GitHub top language](https://img.shields.io/github/languages/top/pentestfunctions/konsole-quickcommands)
![GitHub issues](https://img.shields.io/github/issues/pentestfunctions/konsole-quickcommands)
![GitHub forks](https://img.shields.io/github/forks/pentestfunctions/konsole-quickcommands)
![GitHub stars](https://img.shields.io/github/stars/pentestfunctions/konsole-quickcommands)
![GitHub license](https://img.shields.io/github/license/pentestfunctions/konsole-quickcommands)

📌 **Quick Start**

1. Install `konsole` 🖥️
2. Install `shellcheck` 🔍
3. Make sure konsole is closed and use another terminal
4. Move this file to `~/.config/konsolequickcommandsconfig`
5. Profit. 💸

### From another terminal you can do the following:
```bash
sudo apt-get install konsole shellcheck
curl https://raw.githubusercontent.com/pentestfunctions/konsole-quickcommands/main/konsolequickcommandsconfig > ~/.config/konsolequickcommandsconfig
```
Then simply launch your konsole terminal. 

🔨 **Status:** Still work in progress.

## Overview
This project allows for quick command execution using konsole (Bash).

![Example](sampleidea.gif)

## Commands

<details>
<summary>Default Commands</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 0. Clear the screen | Clearing the screen | [x] |
| 1. Set Target Variable | Set the target for scanning | [x] |
| 2. Host penetration testing directory | Host penetration testing directory | [x] |
| 3. Listen with netcat | Listen with netcat | [x] |
| 99. Check Everything is installed | Check Installations | [x] |

</details>

<details>
<summary>Port Scanning</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 0. Long form general enumeration | Long form general enumeration | [x] |
| 1. Verbose, syn, all ports, all scripts, no ping | Nmap Verbose, Syn, All Ports | [x] |
| 2. Identify ports on target | Rustscan | [x] |
| 3. Quick Port Scan | Quick Nmap scan | [x] |

</details>

<details>
<summary>Subdomain Scanning</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 1. Wfuzz Brute subdomains | Wfuzz Brute subdomains | [x] |
| 2. Retrieve Subdomains | Retrieve Subdomains from web archive | [x] |

</details>

<details>
<summary>CMS Scanning</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 0. Identify your targets software | httpx checking | [x] |
| 1. Whatweb | Whatweb | [x] |
| 2. Wafw00f | Wafw00f | [x] |
| 3. Wordpress/Wpscan | Wordpress/Wpscan | [x] |

</details>

<details>
<summary>Directory Scanning</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 0. Quick Directory Scan | dirsearch quick | [x] |
| 1. Dirsearch complex | dirsearch complex | [x] |
| 2. Gobuster | Gobuster directory scanning | [x] |

</details>

<details>
<summary>Bruteforce and FTP/SMB</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 0. Hydra To be fixed later | Hydra Commands | [x] |
| 0. FTP anonymous download | Anonymous login and retrieve all files | [x] |
| 1. SMB enumeration (Enum4Linux) | SMB enumeration with enum4linux | [x] |

</details>


<details>
<summary>DNS and Decoding</summary>

| Command | Description | Implemented |
|:--------|:------------|:-----------:|
| 0. (Dig) DNS information | Dig the DNS info | [x] |
| Base64 Decode | Decode a base64-encoded data | [x] |
| Base32 Decode | Decode a base32-encoded data | [x] |
| Base58 Decode | Decode a base58-encoded data | [x] |
| Base85 Decode | Decode a base85 (Ascii85)-encoded data | [x] |
| URL Decode | Decode a URL-encoded string | [x] |
| Hex Decode | Decode a hex-encoded string | [x] |
| ROT13 Decode | Decode a ROT13-encoded string | [x] |
| AES Decrypt | Decrypt AES-encrypted data (AES-256-CBC) | [x] |

</details>


## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Project Link: [https://github.com/pentestfunctions/konsole-quickcommands](https://github.com/pentestfunctions/konsole-quickcommands)
