## Project Description
WebAPI clean base template echoes current time in JSON. +CORS +Windows Auth

WebAPI 2.2 project and clean simple baseline without all those extra MVC GUI components.  "HelloController" echoes back the current system time to show a current HTTP 200 reply (not HTTP 304 cached).


## Get Started
* ZIP file at <https://github.com/spjeff/HelloTime/blob/master/HelloTime/deploy/HelloTime.zip>
* Download ZIP and extract
* Open SLN with Visual Studio 2013 or higher
* Open "Package Manager Console" and run "Update-Package" to download assemblies
* F5 to build and run
* Open http://whateversite/api/Hello to execute GET and see JSON reply


## Screenshots
* Solution Explorer showing controller classes (GET/POST/PUT/DELETE)
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/1.png)
* Controller source with key highlights (CORS + Windows Auth)
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/2.png)
* IE running IIS Express locally
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/3.png)
* IE download "/api/Hello" JSON
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/4.png)
* Verify JSON with NotePad++
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/5.png)
* Fiddler "Options tab > [X] Automatically Authenticate"
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/6.png)

## Notes
* Windows Authentication is enabled
* With Fiddler F9 Composer be sure to check "Options tab > [X] Automatically Authenticate"
* May need to enable Automatic Login for IE, FireFox. Read [http://www.scip.be/index.php?Page=ArticlesNET38]( http://www.scip.be/index.php?Page=ArticlesNET38) for how.


## Contact
Please drop a line to [@spjeff](https://twitter.com/spjeff) or [spjeff@spjeff.com](mailto:spjeff@spjeff.com)
Thanks!  =)

![image](http://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square)


## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
