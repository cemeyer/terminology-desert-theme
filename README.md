terminology-desert-theme
========================

This is a theme for the EFL-based terminal, "terminology." It uses colors similar to the gvim "desert" theme.

Building
========

You will need 'edje' installed. Then checkout this repository and run:

    $ sh build.sh
  
You should then install 'desert.edj' into the terminology themes directory. On my system, that's this:

    $ sudo install -m644 desert.edj /usr/share/terminology/themes/
