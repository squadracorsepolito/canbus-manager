# Canbus manager
This script allows you to convert data between JSON and [DBC](https://www.csselectronics.com/pages/can-dbc-file-database-intro) (CAN Bus Databases) formats. You can use it to parse data from a JSON file into a DBC file, or vice versa.

TO DO: conversion from DBC to JSON

## Functionalities
![diagram](https://github.com/squadracorsepolito/SCan/assets/71789321/69988a08-dde9-46d0-9eeb-80358693b9e7)  

The conversion between DBC to Library will be done using [cantools](https://github.com/cantools/cantools)

## How to run the code
1. Create executable or the program
2. `.\canconv.exe convert --in model.json`  
3. DBC file will be generated

## Dependencies
* [os](https://pkg.go.dev/os)
* [strconv](https://pkg.go.dev/strconv)
* [fmt](https://pkg.go.dev/fmt)
* [json encoding](https://pkg.go.dev/encoding/json)
* [ioutil](https://pkg.go.dev/io/ioutil)

