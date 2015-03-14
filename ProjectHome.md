<b>Latest Release</b><br>
<br>
mkisofs-2.01-cjk-md5 has been released on 2011/03/20 in 3 packages: source/binary/sample.<br>
<br>
It's enough for people to build ISO images. You can download source and add your features.<br>
<br><br>
C:\>mkisofs -version<br>
GNU Released by Joerg Schilling, Modified by Wwashington. With Great<br>
<br>
Thanks To: Japan NOBORU(NLS-CJK Patch), Alex Kopylov(MD5-Opt Patch).<br>
<br>
mkisofs 2.01-bootcd.ru-cjk-md5 (i686-pc-mingw32)<br>
<br><br>
Sample: mkisofs -V "mydoc-测试" -r -duplicates-once -iso-level 2 -input-charset cp936 -cjk4dos-filenames -cjk4unx-filenames -o mydoc5.iso mydoc<br>
<br><br>
<b>About mkisofs-orig</b><br>
<br>
This an advanced edtion for original mkisofs, which is a famous ISO image creating tool.<br>
<br>
The orignal mkisofs is written by <a href='http://blogs.sun.com/webmink/entry/livemink_ogb_special_joerg_schilling'>Joerg Schilling</a>, please find the source and binary here.<br>
<br><br>
Latest News: <a href='http://cdrecord.berlios.de/old/private/AN-3.0.html'>http://cdrecord.berlios.de/old/private/AN-3.0.html</a><br>
......... The new MD5 implementation has been made portable. (Have MD5 Optimization?)<br>
......... Fixed a bug introduced with introducing support for MD5 Sums.<br>
CDR Tools: <a href='http://cdrecord.berlios.de/old/private/cdrecord.html'>http://cdrecord.berlios.de/old/private/cdrecord.html</a><br>
The Author: <a href='http://schily.blogspot.com/'>http://schily.blogspot.com/</a><br>

<b>About mkisofs-md5</b><br>
<br>
The mkisofs-md5 project was in <a href='http://mkisofs.cosoft.org.cn'>cosoft</a> until Feb, 2011. It adds "gbk" Chinese Code and<br>
<br>
"md5" Space Optimization. But the site was out of service, so we moved to google code.<br>
<br>
There is only Cygwin Binary for 1.15. I will build Binaries in Cygwin & MinGW for 2.01.<br>
<br><br>
China Project: <a href='http://wwashington.51.net/soft/mkisofs/'>http://wwashington.51.net/soft/mkisofs/</a><br>
China Author: <a href='http://wwashington.51.net/resume/jackyz.htm'>http://wwashington.51.net/resume/jackyz.htm</a><br>

<b>About mkisofs-w32</b><br>
<br>
Some version is compiled under Mingw32("Minimalist GNU for Windows") gcc, it doesn't<br>
<br>
need the Cygwin1.dll. People said that this version suports multilang & md5 optimization.<br>
<br>
You can try more binaries to find the one which is the best fit for you (charset and md5).<br>
<br><br>
Mingw Release: <a href='http://bbs.znpc.net/viewthread.php?tid=976&page=1'>http://bbs.znpc.net/viewthread.php?tid=976&amp;page=1</a> (By Sysoft Rinrin)<br>
Cygwin Release: <a href='http://cdob.boot-land.net/index.php?dir=mkisofs_duplicates_once/'>http://cdob.boot-land.net/index.php?dir=mkisofs_duplicates_once/</a><br>
Cygwin Chinese: mkisofs -V "mydoc-测试" -r -J -jcharset cp936 -o mydoc1.iso mydoc<br>
Cygwin Optimize: mkisofs -V "mydoc-测试" -r -J -duplicates-once -jcharset cp936 -o mydoc2.iso mydoc<br>
<br><br>
Cygwin Cdrtools: <a href='http://smithii.com/cdrtools/'>http://smithii.com/cdrtools/</a> ........ (Notes: No md5 optimize, No cp936)<br>
Mingw DVDTool: <a href='http://fy.chalmers.se/~appro/linux/DVD+RW/tools/win32/'>http://fy.chalmers.se/~appro/linux/DVD+RW/tools/win32/</a> ... (No cp936)<br>
Mingw CDRTool: <a href='http://smithii.com/files/cdrtools-2.01-bootcd.ru-w32.zip'>http://smithii.com/files/cdrtools-2.01-bootcd.ru-w32.zip</a> ...... (No cp936)<br>
Mingw Version: mkisofs 2.01-bootcd.ru (i686-pc-mingw32)<br>

<b>Front-End GUI</b><br>

Please use ISO Maker v1.23 Build 12 as your GUI application, this will save your time.<br>
<br>
The package ISOMaker_123.rar already contains current binary mkisofs-md5 v1.15a40.<br>
<br>
To Do: Write ISO Maker 2.x with mkisofs 2.01 and ISO Maker 3.x with mkisofs 3.00.<br>
<br>

<b>Version History</b><br>
<br>
C:\>mkisofs -version<br>
GNU Released by Joerg Schilling, Modified by Wwashington.<br>
Thanks to dfbb, COMMAN at smth.edu.cn for the great help.<br>
mkisofs 1.15a40 +gbk +md5 (i686-pc-cygwin)<br>

<b>Alternate Site</b><br>
<br>
<a href='http://sourceforge.net/projects/mkisofs-md5/'>http://sourceforge.net/projects/mkisofs-md5/</a><br>