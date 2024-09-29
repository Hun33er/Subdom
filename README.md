## Description:
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->

### Available Tools and online services:

1. Tools:
	- [Findomain](https://github.com/Edu4rdSHL/findomain)
	- [SubFinder](https://github.com/projectdiscovery/subfinder)
	- [Amass](https://github.com/OWASP/Amass)
	- [AssetFinder](https://github.com/tomnomnom/assetfinder)
	- [Httprobe](https://github.com/tomnomnom/httprobe): To Probe For Working HTTP and HTTPS Subdomains.
	- [anew](https://github.com/tomnomnom/anew): To delete duplicates when using -s/--silent option.
1. online services:
	- [WayBackMachine](http://web.archive.org/)
	- [crt.sh](https://crt.sh/)
 	- [AbuseIPDB](https://www.abuseipdb.com/)
	- [BufferOver](https://dns.bufferover.run/)
	- [subdomainfinder.c99](https://subdomainfinder.c99.nl/)
	- [Vedbex](https://vedbex.com/)
	- [Alienvault](http://alienvault.com/)


```

## Usage:

### Basic usage:

```bash
$ subdom -d target.com 
```

### Resolve The Found Subdomains:

```bash
$ subdom -d target.com -r 
```

### Agains a list of domains

```bash
$ subdom -l domains.txt -r
```

### Exclude:

```bash
$ subdom -d target.com -e Amass,wayback
```

### Use:

```bash
$ subdom -d target.com -u Findomain,Subfinder
```

exclude and use can be used with list of domains too 

```bash
$ subdom -l domains.txt -u crt,bufferover
```

### Parallel:
the tool `parallel` must be installed on you system, it runs all the functions at the same time which make the results faster, doesn't work with -u/--use or -e/--exclude options.

```bash
$ subdom -d target.com -p
```


### Silent:

this option helps when you want to pipe the results to another tool, or just to avoid the useless output.

```bash
$ subdom -d target.com -s 
dev.target.com
admin.target.com
api.target.com
..
..
```

happy hacking!


## Spport:

You can support me here:


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      
    </tr>
  </tbody>
</table>
