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
Dhaka, Bangladesh<return>
Condition: Clear<return>
Temperature: 22C
`
By default the program gives the weather of Dhaka, Bangladesh in celcius. <return>

If we want another town, write then the name and the country of the town. For example :
```sh
node cli.js Chauvigné France
```
`
Chauvigné, France<return>
Condition: Partly Cloudy<return>
Temperature: 9C
`
Warning: don't forget the capital letters of the names.<return>

If we want the temperature to be in Farenheit, write F after the country name. For example:
```sh
node cli.js Chauvigné France F
```

`
Chauvigné, France<return>
Condition: Partly Cloudy<return>
Temperature: 49F
`


If you want help from the program, use the command:
```sh
node cli.js --help
```

`
Check the weather for your city from your terminal<return>
<return>
Usage<return>
$ weather <input>
Options<return>
city [Default: Dhaka]<return>
country [Default: Bangladesh]<return>
scale (C/F) [Default: Celcius]<return>
<return>
Examples<return>
$ weather London UK C<return>
London, UK<return>
Condition: Partly Cloudy<return>
Temperature: 32C
`


## Licence
[Uncopyrighted](http://zenhabits.net/uncopyright/)