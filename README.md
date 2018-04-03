# pastebin-scraper


## About
This tool leverages the API of https://psbdmp.ws/ to find emails/domains dumped in pastebin which could lead to finding some juicy information.

## Usage 

```
./scrape.sh 
Usage:
Search for domains - ./script.sh -d domain.com
Search for emails  - ./script.sh -e foo@bar.com
General search	   - ./script.sh -g foobar
```

## Example 

``` 
./scrape.sh -d facebook.com
Searching pastebin...
Task completed. Output present in ./output/general/facebook.com/
```

## Installation
* $ git clone https://github.com/streaak/pastebin-scraper.git
* $ cd pastebin-scraper
* $ mkdir output/domain/ output/email/ output/general/

## Output


Outputs will be stored in ./output/domain (or) ./output/email (or) ./output/general depending on what you search for. The output will contain 2 files, output.json and urls.txt. Output.json will contain the original json returned by the API in a beautified format and urls.txt will contain the URLs returned by the API in a txt format. 


## TODO

* Add more features


## Acknowledgments

* [Tomnomnom](https://twitter.com/tomnomnom)
* [Ed](https://twitter.com/edoverflow)
