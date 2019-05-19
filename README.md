# MuxWithGoModulesAndVendor

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/brothergiez/MuxWithGoModulesAndVendor)

Implementation Golang with Gorilla Mux, MongoDB, Custom Package Model with Go Modules & Vendoring.

### Installation

Clone this repository:

```sh
$ git clone git@github.com:brothergiez/MuxWithGoModulesAndVendor.git
```

After cloning complete then run Go Vendor command:

```sh
$ go mod vendor
```

if you have issue with file permission run that command with sudo.

```sh
$ sudo go mod vendor
```

When the installation dependency process is complete, there will be a new directory with the vendor name containing the installed dependencies.

### How to use

Make sure your machine is installed and running MongoDB. If you use the MongoDB cloud service, you can change the configuration settings in the config.toml file

```
Dbhost="localhost"
Dbname="movies_dbs"
```

If all the settings are correct, then run the following command:

```sh
$ go run app.go
```

### Thanks to:

[Mohamed Labouardy](https://github.com/mlabouardy/movies-restapi) --- https://github.com/mlabouardy

[Noval Agung Prasetyo](https://github.com/novalagung/dasarpemrogramangolang) --- https://github.com/novalagung/
