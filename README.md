# HITANISH

## Description:
Project related to Computer Networks                                                                                       
A small web search engine - Search keywords from URLs                                                                 
Search keywords against websites that have been indexed/spidered by Google.<br />
* Choose what sites to search against, what keywords to search for.<br />
* Examples could be: hash values, private secrets, email addresses or simply domain names.<br />
* Optionally proxy your requests through custom proxies to avoid Google banning.<br />

## Proof of Concept:
 keywords.conf- mern                                                                           
 sources.conf - github.com                          

![hit](https://user-images.githubusercontent.com/85629794/197405517-490a461e-d992-4ba7-b3d3-2618c0098470.jpg)


## Install:

```bash
git clone https://github.com/HiteshSharma-github/Hitanish.git
cd Hitanish
pip install -r requirements.txt
```

## Usage:

```bash
python3 hitanish.py
```

Edit the three config files:<br />
* keywords.conf containing all the keywords you want to search for.<br />
* sources.conf all of the sites you want to search against.<br />
* proxies.conf proxies to route requests through, to avoid Google ban.<br />

## Examples:

<b>keywords.conf</b>
```bash
# These are the keywords to search against Google. They can be simply domain names, or specific terminology.
# Anything behind a hashtag like this line, will be ignored.
HITANISH
```

<b>sources.conf</b>
```bash
# These are new line separated domain names that you want to search against.
# The domain names must be able to be indexed/spidered by Google.
# Anything behind a hashtag like this line, will be ignored.
# pastebin.com
# pastie.org.ru
# paste.org
# hackforums.net
# antichat.ru
github.com
```

<b>proxies.conf</b>
```bash
# Enter new proxies below on a new line
# Anything behind a hashtag like this line, will be ignored.
# Format: schema://ip_or_domain:port
# http://1.1.1.1:80
# https://1.1.1.1:443
```
# Happy Hacking !
