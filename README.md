SkipCinematics
==============

By *Yseult*

Ce module permet de sauter les cinématiques.

![Menu de configuration](http://imageshack.us/a/img832/5413/jzt3.png "Menu de configuration")

Download + Compile:
-------------------

1. Install Git
2. git clone --recursive https://github.com/Dofus/SkipCinematics.git
3. cd SkipCinematics/dmUtils/
4. Compile dmUtils library (see README)
5. cd ..
3. mxmlc -output SkipCinematics.swf -compiler.library-path+=./modules-library.swc -compiler.library-path+=dmUtils/dmUtils.swc -source-path src -keep-as3-metadata Api Module DevMode -- src/SkipCinematics.as

Installation:
-------------

1. Create a new *SkipCinematics* folder in the *ui* folder present in your Dofus instalation folder. (i.e. *ui/SkipCinematics*)
2. Copy the following files in this new folder:
    * SkipCinematics.swf
    * Yseult_SkipCinematics.dm
3. Launch Dofus
4. Enable the module in your config menu.
5. ...
6. Profit!
