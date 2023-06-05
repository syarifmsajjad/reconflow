# reconflow
# This is my reconflow

## Subdomain Enumeration
```
subfinder -dL scope.txt -o subdomains-subfinder.txt
amass enum -passive -norecursive -noalts -df scope.txt -o subdomains-amass.txt
cat scope.txt | assetfinder -subs-only | anew subdomains-assetfinder.txt
```
