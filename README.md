## Unicode Escape - Sublime Text Plugin

non_ascii_string <--> Unicode_escape

__note__: Line Ending and Tab are ignored.


e.g.
```js
escape('中文'); // => '\u4e2d\u6587'
unescape('\u4e2d\u6587'); // => '中文'
```

##Installation
- Package Control:

	search and install `Unicode Escape`


- Custom install:

	1. Download from [here](https://github.com/iahu/escape/archive/master.zip).
	2. unzip and copy the package to sublime packages fold.
	Windows and Linux can find at sublime text menu `Preferences`>`Browse Packages...`
	Mac os x as `Sublime Text`>`Preferences`>`Browse Packages...`

##Usage

Windows:
```json
[
    {"keys": ["ctrl+f11"], "command": "escape"},
    {"keys": ["ctrl+f12"], "command": "unescape"}
]
```

Linux/Mac os x:
```json
[
    {"keys": ["ctrl+escape"], "command": "escape"}
    {"keys": ["ctrl+shift+escape"], "command": "unescape"}
]
```
