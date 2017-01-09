This installation procedure was tested on Mac OS X Yosemite (10.10).

Prerequisite

1.  Xcode. See Xcode/Xcode5for10\_10.docx.

<!-- -->

1.  Install gfortran.
    =================

    a.  Dowload gcc-42-5666.3-darwin11.pkg from
        <http://r.research.att.com/tools/>. Please note that at the
        moment of writing these lines (June 4^th^ 2015), the latest
        version available is for Mac OS X Lion 10.7. It is still going
        to work on Yosemite 10.10.

    b.  Right click on the file gcc-42-5666.3-darwin11.pkg and then
        click open. If instead you double click it, you will most likely
        get a message telling “… can’t be opened because it is from an
        unidentified developer” and you will be stuck.

    c.  Install gcc-4.2.

    d.  \$ sudo ln –s /usr/bin/gfortran-4.2 /opt/local/bin/gfortran
        (note the space between gfortran-4.2 and /opt).


