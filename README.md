# jdk8u--with-freetype-src
build jdk8 with freetype sources on windows

currently under construction


hg clone http://hg.openjdk.java.net/jdk8/jdk8 jdk8
cd jdk8
./get_source.sh
copy the four .m4 files from the local git repository to jdk8/common/autoconf (overwrite existing)
hg status should then show the following:
```
{ jdk8 }  » hg status                                                                                             /cygdrive/c/openjdk/jdk8
M common\autoconf\help.m4
M common\autoconf\libraries.m4
M common\autoconf\toolchain.m4
M common\autoconf\toolchain_windows.m4
{ jdk8 }  »  
```
