# custom-pac
Cutomize your pac file for shadowsocks. Original repo is here: https://github.com/zhiyi7/gfw-pac

## Features
- Specify some ip ranges to use proxy (Others go direct).
- Corrected tld file.  
(To learn original features, go to the link above.)

## How to use
Just use it like the original one. But the ip file's format has changed. I've provided an example file in this repo.  
*E.g.* 173.245.48.0/20 --> 173.245.48.0|4096  
You must follow this format, otherwise this file won't work.  
