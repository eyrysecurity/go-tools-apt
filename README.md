# EyrySecurity Go Tools Apt Repository
We are programatically pulling and building and distributing debian packages from common go tools (i promise they dont have backdoors to my knowledge, but convienience is the price you pay i guess).

# Packages
| Name        | Description                                                                                                                          | Maintainer       | Version   |
|:------------|:-----------------------------------------------------------------------------------|:-----------------|:----------|
| unfurl      | Unfurl URLs and extract useful information from them                               | TomNomNom        | 0.4.3     |
| httprobe    | Take a list of domains and probe for working HTTP and HTTPS servers                | TomNomNom        | 0.2       |
| gron        | Make JSON greppable!                                                               | TomNomNom        | 0.2       |
| waybackurls | Fetch all the URLs that the Wayback Machine knows about for a domain               | TomNomNom        | 0.1.0     |
| anew        | A tool for adding new lines to files, skipping duplicates                          | TomNomNom        | 0.1.1     |
| qsreplace   | Replace parameter values in URLs with different values                             | TomNomNom        | 0.0.3     |
| katana      | A HTTP crawler                                                                     | ProjectDiscovery | 1.1.0     |
| ffuf        | Fast web fuzzer written in Go                                                      | joohoi           | 2.1.0     |
| httpx       | Fast and Multi-purpose HTTP Toolkit                                                | ProjectDiscovery | 1.6.0     |
| subfinder   | Subdomain discovery tool that discovers valid subdomains for websites              | ProjectDiscovery | 2.6.6     |
| nuclei      | Nuclei is a fast tool for configurable targeted scanning based on templates        | ProjectDiscovery | 3.2.3     |
| dnsx        | DNSX is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries     | ProjectDiscovery | 1.2.1     |

# Installation
```bash
curl -s https://raw.githubusercontent.com/eyrysecurity/go-tools-apt/main/key.gpg | sudo apt-key add -
sudo cp /etc/apt/trusted.gpg /etc/apt/trusted.gpg.d
sudo add-apt-repository 'deb https://raw.githubusercontent.com/eyrysecurity/go-tools-apt/main jammy main'
```

# Usage
```bash
sudo apt update
sudo apt install <package-name>
```

# License
This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
