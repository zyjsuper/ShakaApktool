### About

[![Join the chat at https://gitter.im/rover12421/ShakaApktool](https://badges.gitter.im/rover12421/ShakaApktool.svg)](https://gitter.im/rover12421/ShakaApktool?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
You know and not know are in progress.


It is NOT intended for piracy and other non-legal uses. It could be used for localizing, adding some features or support for custom platforms and other GOOD purposes. Just try to be fair with authors of an app, that you use and probably like.


#### Link
- [Project Page](http://www.rover12421.com/shakaapktool)
- [Apktool Project Page](http://ibotpeaches.github.io/Apktool/)
- [Smali Project Page](https://github.com/JesusFreke/smali/)
- [Source (Github)](https://github.com/rover12421/ShakaApktool/)
- [Source (Bitbucket)](https://bitbucket.org/Rover12421/shakaapktool)
- [Source (OsChina)](http://git.oschina.net/rover12421/ShakaApktool)
- [Source (CSDN)](https://code.csdn.net/rover12421/shakaapktool)
- [Source (CODING)](https://coding.net/u/rover12421/p/ShakaApktool)
- [How To Build](https://github.com/rover12421/ShakaApktool/wiki/How-To-Build)
- [Download](https://pan.baidu.com/s/1jIPOHZg)(ht4j)


1.Build First

Download ShakaApktool Source

git clone https://github.com/rover12421/ShakaApktool.git
or(ignore 'git submodule' later) 
git clone --recursive https://github.com/rover12421/ShakaApktool.git 

2. Init and Update Submodel apktool

```
cd ShakaApktool
git submodule init
git submodule update
```
3. Prepare
win: ./gradlew.bat
*nix: ./gradlew

remember the path for gradle3.5

3. Build Jar File

../installpath/bin/gradle3.5 fatjar
Run Jar Test

java -jar shaka.cli/build/libs/shaka.cli.jar

Build Again
Update ShakaApktool Source

git pull
Update Submodel apktool

git submodule update
Build Jar File

gradle fatjar
Run Jar Test

java -jar shaka.cli/build/libs/shaka.cli.jar

#### Other
- QQ Group : 198996891
