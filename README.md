# Khmer Fonts
![Pub Version](https://img.shields.io/pub/v/khmer_fonts?style=flat-square)
[![Bless](https://img.shields.io/badge/bless-God-brightgreen?style=flat-square)](https://lunagao.github.io/BlessYourCodeTag/)

A flag Flutter package for `Android` / `iOS` / `Web`. Mobile Based by https://github.com/dnfield/flutter_svg , Web Based by `Image.network`


## svg source
* Flag list came from UN members. [UN Web Site](https://www.un.org/en/member-states/index.html)
* A lot of flag svg files came from wike. such as [Antigua and Barbuda](https://commons.wikimedia.org/wiki/File:Flag_of_Antigua_and_Barbuda.svg)
* Some flag svg files came from [Countryflags](https://www.countryflags.com/en/).


## Flag list

[Flag List](https://github.com/LunaGao/flag_flutter/wiki/UN-numbers-list)

Organisations
* `eu` European Union. Modify by [art-decor for European Union](https://www.art-decor.org/mediawiki/index.php?title=File:Flag_eu.svg)

## How to use

`Flag(COUNTRY_CODE, height: HEIGHT, width: WIDTH),`

Such as
* `Flag('AD', height: 100, width: null)`
* `Flag('AD', height: null, width: null)`
* `Flag('AD', height: 10, width: 100, fit: BoxFit.fill)`

