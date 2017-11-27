# vPHP
Vanilla PHP Framework

vPHP is a simple yet effective PHP framework developed for Symions own development projects.
The framework consists of multiple classes. Down below you'l find a basic description of the available classes.

******************
### AUTHENTICATE CLASS

This is a simple PHP Class for user authentication. 
Currently supporting: 
- Basic HTTP (Username/Password Combo)
- API Key + Token
- Bearer Token

Example users array: (These are the used keys of the class. You may add otherones if you like)

```
[
  {
  "NAME" => "john Doe",
  "PASSWORD" => "jonnydoe",
  "KEY" => "rPbkvUYv66FHhE59gnzZ",
  "TOKEN" => "k4HYpFBtSf14xqfJ3QEwxZ2TJ1rFjKfO",
  "BEARER" => "XuMeVyLC1UxxRkw0gtIATaUTIcC9neCW"
  },
  {
  "NAME" => "",
  "PASSWORD" => "",
  "KEY" => "",
  "TOKEN" => "",
  "BEARER" => ""
  }
]
```

All the functions return an array with the following keys:

```
array(
  "status" => true/false,
  "message => "String with error or succes message",
  # if the user is authenitcated
  "user" => "string with username"
)
```
