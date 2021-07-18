# README

Step1: go build

```bash
go build -o privateCheck main.go
```

Step2: move binary file

```bash
sudo mv privateCheck /usr/local/bin/privateCheck
```

Step3: test

```bash
privateCheck 127.0.0.1 108.160.166.9 10.108.250.20
```



