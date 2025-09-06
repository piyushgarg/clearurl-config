# clearurl-config

## Install ClearURLs
https://addons.mozilla.org/en-US/firefox/addon/clearurls/

## source repo
https://github.com/ClearURLs/Addon

## documentation
http://docs.clearurls.xyz/

## make changes
1. change data.minify.json
2. generate sha256sum data.minify.json `sha256sum -z data.minify.json | cut -d ' ' -f 1 | tr -d '\n' > rules.minify.hash`
3. copy the checksum in rules.minify.json

## Click Extension Settings
### Update the following URLs
https://raw.githubusercontent.com/piyushgarg/clearurl-config/refs/heads/main/data.minify.json

https://raw.githubusercontent.com/piyushgarg/clearurl-config/refs/heads/main/data.minify.hash
