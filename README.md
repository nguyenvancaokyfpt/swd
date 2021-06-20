# swd
<img  src="https://raw.githubusercontent.com/SegoCode/swd/main/media/demo.gif">

Easy to use, simply wrapper for [steamworkshopdownloader.io](https://steamworkshopdownloader.io/) API.

## Usage & info

swd downloads the files compressed in a zip file with the steam workshop article id.

```shell
id_steamworkshop.zip
```

run from source code (Golang installation required).

```shell
git clone https://github.com/SegoCode/swd
cd swd
go get -d ./...
go run swd.go https://steamcommunity.com/sharedfiles/filedetails/?id=...
```
Or better [donwload a binary](https://github.com/SegoCode/swd/releases).

## Parameters

It's simple, there is only one parameter, the url of the steam workshop article you want to download.
```shell
swd https://steamcommunity.com/sharedfiles/filedetails/?id=......
```

## Downloads

https://github.com/SegoCode/swd/releases/
