# Subdomains Enumerator
A docker image which will enumerate, sort and unique the results of various subdomains enumeration tools. 

## Building the docker image
You can build the docker image yourself using the following:
```bash
git clone https://github.com/Anon-Exploiter/subdomainsEnumerator && cd subdomainsEnumerator
docker build -t uexpl0it/subdomains-enumerator .
```

## Usage
```bash
docker run -it --rm uexpl0it/subdomains-enumerator
```
## Tools
Currently integrated tools include:
* [Sublist3r](https://github.com/aboul3la/Sublist3r)
* [Subfinder](https://github.com/projectdiscovery/subfinder)
* [Amass](https://github.com/OWASP/Amass)
* [OneForAll](https://github.com/shmilylty/OneForAll/)
* [Asset Finder](https://github.com/tomnomnom/assetfinder)
