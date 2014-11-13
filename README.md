	  _____                                   _____                _             
	 |  __ \                                 / ____|              | |            
	 | |__) |__ _ __ ___  ___  _ __   __ _  | |     _ __ ___  __ _| |_ ___  _ __ 
	 |  ___/ _ \ '__/ __|/ _ \| '_ \ / _` | | |    | '__/ _ \/ _` | __/ _ \| '__|
	 | |  |  __/ |  \__ \ (_) | | | | (_| | | |____| | |  __/ (_| | || (_) | |   
	 |_|   \___|_|  |___/\___/|_| |_|\__,_|  \_____|_|  \___|\__,_|\__\___/|_|   
	                                                                             
# Persona Creator 

A simple python3 command line application for creating user personas.

## Installation instructions

### Installing on Linux and Mac (recommended)

Ensure the latest version of python3 is installed. 

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3
```
Download Persona Creator to your computer. 

Using git:

```
cd ~
git clone https://github.com/Honeystone/PersonaCreator.git
cd PersonaCreator
```
Install globally.

```
sudo chmod +x pcreator.py
sudo cp pcreator.py /usr/local/bin/pcreator
pcreator
```

Persona Creator can be launched from any directory using the `pcreator` command.

### Installing on Windows

Ensure the latest version of python3 is installed from: 

https://www.python.org/downloads/windows/

Download Persona Creator to your computer. 

Using git bash:

```
cd ~
git clone https://github.com/Honeystone/PersonaCreator.git
cd PersonaCreator
```
Setting up the Windows(7) environment variable:

* Go to `Control Panel`
* Click `System and Security`
* Click `System`
* Click `Advanced system settings`
* Switch to `Advanced` tab
* Click `Environment Variables` 
* Select `Path` in the `System Variable` section
* Click `Edit`
* Add the path to Persona Creator to the end of the environment variable string e.g. ";c:\Users\[Username]\PersonaCreator" 

Persona Creator can be launched from the Windows command prompt in any directory using the `pcreator` command.

## License

The MIT License (MIT)

Copyright (c) 2014 Honeystone Consulting Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.