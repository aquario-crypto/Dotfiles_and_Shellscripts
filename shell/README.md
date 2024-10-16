## some quick and useful shell commands

<br>


* downloading all pdfs of url

<br>

```shell
$ wget --recursive --level=2 --no-directories --no-host-directories --accept pdf
```

<br>


* extended attributes of files

```shell
$ xattr -l $file
```

<br>

* check signatures of apps

<br>

```shell
$ codesign -dvvv $file.app
```

<br>

* show all the configs

<br>

```shell
$ system_profiler -detaillevel full
```

<br>

*  瑪麗


<br>


```shell
$ convert -size 360x360 xc:white -font "FreeMono" -pointsize 12 -fill black -draw @ascii.txt
```