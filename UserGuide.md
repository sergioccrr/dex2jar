1. Download dex2jar from http://code.google.com/p/dex2jar/downloads/list
* Extract dex2jar-version.zip to a folder. for example /home/panxiaobo/, C:\  
unzip -x dex2jar-version.zip -d /home/panxiaobo
* use dex2jar to generate .jar file. dex2jar will generate a file named someApk-dex2jar.jar in the working folder.
 ```
 linux sh /home/panxiaobo/dex2jar-version/d2j-dex2jar.sh /home/panxiaobo/someApk.apk
 windows C:\dex2jar-version\d2j-dex2jar.bat someApk.apk
 ```
* use a decompiler to view the source.
 * [jd-gui](http://jd.benow.ca/)
 * [JAD](http://www.varaneckas.com/jad)

that's it
