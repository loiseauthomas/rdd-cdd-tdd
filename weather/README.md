# cli-weather

> cli-weather package

**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Package Presentation](#Package Presentation)
- [Requirements](#Requirements)
- [Package Installation](#Package Installation)
- [How to use it?](#How to use it?)
- [Licence](#licence)

##Package Presentation

This package gives the weather of a specified town around the world. It gives the temperature and the meteorological conditions (sunny, clear, cloudy...).

##Requirements

Install "node.js" available [here](https://nodejs.org/en/).

#Package Installation
- Download this pakage, clicking the button "Clone or download" available [here](https://github.com/92bondstreet/rdd-cdd-tdd).

- Open the terminal of your computer and go to the package directory with the command :
```sh
cd (your directory name)
```
- Go then to the directory "weather".
```sh
cd ./weather
```
- Install all dependencies of the package using the command :
```sh
npm install
```
It will install all depedencies present in the "package.json" file


##How to use it?
- Open the terminal of your computer and go to the package directory with the command :
```sh
cd (your directory name)
```
- Go then to the directory "weather".
```sh
cd ./weather
```
- Now you can run cli.js using the command :
```sh
node cli.js
```
`
Dhaka, Bangladesh
Condition: Clear
Temperature: 22C
`
By default the program gives the weather of Dhaka, Bangladesh in celcius. 

If we want another town, write then the name and the country of the town. For example :
```sh
node cli.js Chauvigné France
```
`
Chauvigné, France
Condition: Partly Cloudy
Temperature: 9C
`
Warning: don't forget the capital letters of the names.

If we want the temperature to be in Farenheit, write F after the country name. For example:
```sh
node cli.js Chauvigné France F
```
`
Chauvigné, France
Condition: Partly Cloudy
Temperature: 49F
`


If you want help from the program, use the command:
```sh
node cli.js --help
```
`
 Check the weather for your city from your terminal

  Usage
    $ weather <input>

  Options
    city [Default: Dhaka]
    country [Default: Bangladesh]
    scale (C/F) [Default: Celcius]

  Examples
    $ weather London UK C
    London, UK
    Condition: Partly Cloudy
    Temperature: 32C
`


## Licence
[Uncopyrighted](http://zenhabits.net/uncopyright/)