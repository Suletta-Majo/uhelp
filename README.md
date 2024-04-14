![uhelp banner](images/uhelp_banner.png)

<p>
<img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-F2C63C.svg?logo=python&style=for-the-badge">
</p>
&nbsp;
<table><tr><td><h1>W</h1></td><td>elcome to Your own help👋</td></table>
> it show dictionaly your own wrote command usage and memo

> *and if not assigned show Built-in dictionary*  
> *You can also search for an excellent community base cheat sheet [tldr](https://tldr.sh)*  
> *and you can also set it to be displayed at the same time as your own.*  


## NOTE : *Now Making*
> **The package has not been completed yet for Packaging, please wait.**  
> *If you want to try it even if it's not a compiled package, please try the explanation a little ahead* **pip from git method**

&nbsp;
## Instal

Cannot be installed on Termux!Proot-Distro environment is possible
<details> I made it with Termux and Debian, but it doesn't work with Termux.  
(When I tried the installation in Termux, it was installed half way and I wandered around the apt or dpkg command to recover its state.  
If possible, I'd like to explore how to make it a termux pkg as a future task.</details>

Ways 1 using pip (from this repository) 

Package and install directly from this repository with pip
```sh
pip install git+https://github.com/Suletta-Majo/uhelp.git
```  
This works in Python


Ways 2 using .deb  
*choose Debian deb package your CPU architecture*  

~~[x64](https://)~~ &nbsp;/&nbsp;[arm64](https://) 

```sh
apt install ./uhelp-1.0.deb
```
This is the deb package that is compiled with the OneFile option by [nuitka](https://github.com/Nuitka/Nuitka)



### git clone (for debug, for Contribute)  
Be sure to change the pathstyle = "xxx" at the beginning of
 uhelp.py to "python".
for Developers, contributors, and anyone wanting to tweak the build  

Create a directory for that purpose, go into it, and then  

```sh
git clone https://github.com/Suletta-Majo/uhelp.git
```  

In that directory you can run like  

```sh
python3 ./uhelp.py ls
```  
...to test program


&nbsp;
## Usage

If you install with pip, you can call it with `uh`,  
and if you install deb with apt, you can call it with `uh` or `uhelp`.

show your command reference below example `ls`

```sh
uh ls
```  
```sh
uhelp ls
```

*priority is User Dictionary > Built-in Dictionary*

&nbsp;

&nbsp;


### Edit your own help item
```
uh -e [command name]
```
The text editor opens and you can edit it with reference to the description.


### Remove your own help item
```
uh -r [command name]
```

#### Change Theme
```
uh -v [theme name]
```
Now you can choose from 5 options: default, retro, retro2, simple, fruits

default
![default style](images/default_style.png)  

| retro                                | retro2                                |
| -------------------------------------| ------------------------------------- |
|![retro style](images/retro_style.png)| ![retro2 style](images/retro2_style.png)|  

| simple                               |fruits                                 |
| -------------------------------------| ------------------------------------- |
| ![simple style](images/simple_style.png)| ![fruits style](images/fruits_style.png)|  



### Tldr viwer Mode
```
uh -t [command name]
```
Command help mode using only TLDR pages


***

&nbsp;

As a bonus feature, there is a function to take a short note before falling asleep

```sh
uh -s i try fix suboutput function.but I think I'm going to sleep
```
```sh
uh -s "i try fix suboutput function.but I think I'm going to sleep"
```
Record up to 10 records

To view choose on  prompt 'no'


&nbsp;
## Author

👤 **Suletta-Majo**

* Github: [@Suletta-Majo](https://github.com/Suletta-Majo)

## Show your support

Give a ⭐️ if this project helped you!  



appendix: [A very useful tools used to create this page!!](appendix.md)  
  

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
