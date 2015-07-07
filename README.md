##Nayra - LFI Exploitation Tool
--------
This is a small tool to exploit a LFI (Local File Inclusion) web vulnerability.
The tool provide a functional shell prompt. In the future, I will add some extras options very useful.

###Disclaimer

* __Legal__:
This tool is designed only for __educational__ purposes and __ethical__ hacking. Use it at your own responsibility. Damages or legal problems caused by the tool are the responsibility of the user.

* __License__:
This tool is subject under the following license:

 >Creative Commons Attribution-ShareAlike 3.0
		
 ![](https://licensebuttons.net/l/by-sa/3.0/88x31.png "Creative Commons")

 More Info: [Here](https://creativecommons.org/licenses/by-sa/3.0/ "Legal Description")


###Usage
* __Required Parameters__:
```python
-t, --type              Specifies the type of action
-u, --url                URL vulnerable to LFI (Local File Inclusion)
```

 * __List of types__:
```python
shell                    Exploit the vulnerability to get a shell
```

 * __Optional Parameters__:
```python
-m, --method (=GET)      It can be -> [GET|POST]
-l, --lang (=php)        Used to specify the corresponding attack
                         payload in "data.json"

-c, --cookies            Session cookies
-x, --proxy              Using a proxy -> [http://user:passwd@host:port]
-p, --path               When it is necessary to make a directory traversal
```
* __Other Parameters__:
```python
-h, --help               Display this message
```

###About
This tool was created by: __@codexlynx__.

* Twitter: [https://twitter.com/codexlynx](https://twitter.com/codexlynx)
* GitHub: [https://github.com/codexlynx](https://github.com/codexlynx)

----------------
About the tool name:

__In Spanish:__ [https://es.wikipedia.org/wiki/Nayra](https://es.wikipedia.org/wiki/Nayra)