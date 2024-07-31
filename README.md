st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.
This is my st-config archive, you can use. Thanks to all who made this available

Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Run the following commands (if necessary as root):
```
    git clone https://github.com/anordius/st-anord.git
    mv st-anord st
    cd st
    make clean install
```

Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

