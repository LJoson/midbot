# Grbl CNC for the MidTBot

This is a fork of Grbl 1.1f for the MidTBot. 

![midTbot](http://www.buildlog.net/blog/wp-content/uploads/2018/03/20171015_134513.jpg)

The official Grbl Repo by Sungeon Jeon is [https://github.com/gnea/grbl](https://github.com/gnea/grbl).

This fork turns on the CoreXY functions, sets the correct defaults and adds pen up/down control of a hobby servo for the pen.

Any work coordinate system Z>0 is pen up. Any work coordinate system Z<=0 is pen down.

The MidTBot is documented on the [http://www.buildlog.net/blog/?s=midtbot](http://www.buildlog.net/blog/?s=midtbot). Please ask all question on the blog.

Note: This needs to be installed as an Arduino library.  See the [Grbl wiki pages](https://github.com/gnea/grbl/wiki/Compiling-Grbl) on how to do that.