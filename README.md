# Portfolio
![screenshot](https://user-images.githubusercontent.com/31620041/112150921-fb223880-8c23-11eb-9b59-aa7a4bcae08c.png)
[https://donchan922.com](https://donchan922.com)

## Requirement
- Hugo >= 0.74.0

## Installation
```bash
$ git clone https://github.com/donchan922/donchan922.github.io.git
$ cd donchan922.github.io
$ git submodule update --init --recursive

# if you need to update theme
$ git submodule update --remote --merge

$ hugo server -D
```

Access to http://localhost:1313/

## Deploy
```bash
$ hugo
$ git add .
$ git commit -m "xxx"
$ git push origin HEAD
```
