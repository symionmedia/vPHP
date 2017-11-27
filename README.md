# vPHP
Vanilla PHP Framework

vPHP is a simple yet effective PHP framework developed for Symions own development projects.
The framework consists of multiple classes. Down below you'l find a basic description of the available classes.

******************
### AUTHENTICATE CLASS
==================

This is a simple PHP Class for user authentication. 
Currently supporting: 
- Basic HTTP (Username/Password Combo)
- API Key + Token
- Bearer Token

Example users array:

```
[
  {
  "NAME" => "john",
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
