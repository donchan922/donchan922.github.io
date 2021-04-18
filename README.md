# Portfolio
![screenshot](https://user-images.githubusercontent.com/31620041/115137652-46ccd400-a062-11eb-966b-0bfc8c656bec.png)
[https://donchan922.com](https://donchan922.com)

## Requirement
- Hugo >= 0.82.0

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
