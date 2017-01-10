*New procedure that works for all OS versions*

Download and install Homebrew

-   Open a terminal and type : /usr/bin/ruby -e "\$(curl -fsSL
    <https://raw.githubusercontent.com/Homebrew/install/master/install)>"

Install Homebrew and its dependencies

-   brew install homebrew/science/gmt4-4.5.15

This installation procedure was tested on Mac OS X Lion (10.7), Mac OS X
Mountain Lion (10.8) and Mac OS X Yosemite (10.10).

Prerequiste

1.  MacPorts. See svn/Takuvik/Teledetection/SOP/MacPorts/MacPorts.docx.

Procedure

1)  Install GMT 4.

    a.  \$ sudo port install gmt4

    b.  Add to your .bash\_profile the following line:

        export PATH=.:/opt/local/lib/gmt4/bin:\$PATH

    c.  Test GMT.

        i.  \$ grdcontour

        ii. This should print the usage of the GMT command grdcontour on
            the terminal.

    d.  \$ sudo port install ImageMagick

2)  (Optional) Install local documentation.

    a.  Open a browser.

    b.  Enter <file:///opt/local/lib/gmt4/share/doc/html/index.html>

    c.  Bookmark.

If you experience difficulties to install GMT4 or GMT5 with Mac Port you
can try the following alternative.

a)  Follow this link :
    <http://gmt.soest.hawaii.edu/projects/gmt/wiki/Download>

b)  Download the latest version of GMT

c)  Copy the GMT file to your applications directory

d)  Open a new terminal and edit the file .profile

e)  add the following line :

    a.  export
        PATH="/Applications/GMT5.2.1.app/Contents/Resources/bin:\$PATH"


