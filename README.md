xPand
=====

xPand is a computer algebra code for doing cosmological perturbation theory on a set of homogenioues background.  It is 
part of the xAct distribution that runs on Mathematica.




INSTALLATION NOTES FOR THE xPand PACKAGE
****************************************

General Information:
*********************

Visit http://www2.iap.fr/users/pitrou/xpand.htm

In order to install xPand, you first need to install xAct.

Installation of xAct:
*********************

Download the latest the xAct package on 'http://www.xact.es/download.html'. Install instructions are provided on this website.

Once xAct is installed correctly, it should be located in one of the places that
Mathematica prepares for external applications:

Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Mathematica/Applications/

          or

        /usr/local/Wolfram/Mathematica/9.0/AddOns/Applications/

   - single-user installation:

        $HOME/.Mathematica/Applications/

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Mathematica/Applications/

          or

        /Applications/Mathematica 9.0.app/AddOns/Applications/

   - single-user installation:

        /Users/<user>/Library/Mathematica/Applications/

MSWindows:

   - system-wide installation:

        C:\Documents and settings\All Users\Application data\Mathematica\Applications\

          or

        C:\Program Files\Wolfram Research\Mathematica\9.0\AddOns\Applications\

   - single-user installation:

        C:\Documents and settings\<user>\Application Data\Mathematica\Applications\

Beware that in Windows these directories might be hidden!

Installation of xPand:
**********************

The package can be downloaded as a single tarball xPand_0.4.0.tar.gz.
When uncompressed (typing 'tar -xzvf xPand_0.4.0.tar.gz' under Linux),
it gives
-a folder 'xPand'
-a file 'xPand.m'
-this documentation file 'documentation_xpand.txt''

Note that in some cases, for instance if you uncompress the tarball by a double
click, these 3 items are likely to be placed below a folder named xPand_0.4.0.

The folder xPand, and the file 'xPand.m' must be placed inside the
xAct directory. For instance, in a single user installation with Mac
OS, there should be a folder
/Users/<user>/Library/Mathematica/Applications/xAct/xPand
and a file
/Users/<user>/Library/Mathematica/Applications/xAct/xPand.m

Documentation:
**************

To load the CMB documentation go to `Add-Ons and Packages' in the Documentation
Center (versions 6.0 of Mathematica at least required), then in 'xAct
Packages' and 'xPand'.

Then the package can be loaded using unix style

        <<xAct/xPand.m
	

or Mathematica style

        <<xAct`xPand`
      

If you encouter any problem, don't hesitate to contact me at

        pitrou@iap.fr

This is the "install" file of xPand. Last update: 8 Feb 2013.
