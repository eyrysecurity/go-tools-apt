# EyrySecurity Go Tools Apt Repository
We are programatically pulling and building and distributing debian packages from common go tools (i promise they dont have backdoors to my knowledge, but convienience is the price you pay i guess).

# Packages
| Name | Maintainer | Description | 
|------|------------|-------------|
| unfurl | TomNomNom | Unfurl URLs and extract useful information from them |
| httprobe | TomNomNom | Take a list of domains and probe for working HTTP and HTTPS servers |
| gron | TomNomNom | Make JSON greppable! |
| waybackurls | TomNomNom | Fetch all the URLs that the Wayback Machine knows about for a domain |
| anew | TomNomNom | A tool for adding new lines to files, skipping duplicates |
| qsreplace | TomNomNom | Replace parameter values in URLs with different values |
| katana | ProjectDiscovery | A HTTP crawler |
| ffuf | joohoi | Fast web fuzzer written in Go |
| httpx | ProjectDiscovery | Fast and Multi-purpose HTTP Toolkit |
| subfinder | ProjectDiscovery | Subdomain discovery tool that discovers valid subdomains for websites |
| nuclei | ProjectDiscovery | Nuclei is a fast tool for configurable targeted scanning based on templates offering massive extensibility and ease of use |
| dnsx | ProjectDiscovery | DNSX is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers |

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
