* Wrapper for cbt export and import *

You can configure two aspects for the script:

a) The 'run' directory.  This is where the packages, filters and such will go.
b) The 'cbt' directory.  This is where the cbt binaries and cbt.cfg usually 
   reside.

The 'run' directory can be created by ( feel free to change the main dir ):

mkdir /var/opt/opsware/cbt_exports; cd !$
mkdir {exports,imports,packages,filters}

The 'cbt' directory assumes a structure of:
    CBT_DIR/cbt.cfg
    CBT_DIR/bin/cbt

You can modify this if you'd like in the compile_options function

