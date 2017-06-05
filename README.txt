FvwmSkeleton: Fvwm,Bash,Vim configuration for diskless (and non diskless) multiuser 
office environments. 

Summary: 

FvwmSkeleton is a compendium of common hacks used to create a fast multiuser installation for 
Fvwm. It is oriented towards data centric users, which is to say that it is designed to be 
fast for sysadmins, network admins, programmers, analysts, accountants. However the Interface 
does include a great number of scripts for integrating the most popular desktop applications, 
like: 

LibreOffice 
Blender 
ffmpeg 
mplayer 

The list will grow as FvwmSkeleton matures.  There will be no games or nicities added. FvwmSkeleton 
is for work environments. In consideration of the poor security histories of pretty much every 
popular browser (whether by actual insecurity, or by direct intrusion by their respective 
vendors) FvwmSkeleon does not install configurations for a browser by default. The included 
scripts are easy enough to modify for that purpose. However none are expected to be included 
in the base distribution. Ever...  

The institutional knowledge that is retained in the digital systems of a business must be able to 
grow and expand. However frivilous development also must be constrained. To do this, the window 
manager needs to be installed in a way that allows for easy installation for multiple users, but 
that also constrains those users from being able to modify that installation. IOW, PC desktop 
computing has always been a poor architecture for business. Large or small. 

FvwmSkeleton is intended to be an adjunct tool for managing Linux installations in diskless or 
thin client environments. This does not mean that is bad for using on the desktop. (it is in 
fact quite nice) It means that file layout is highly compartmentalized, and always will be. 

FvwmSkeleton installs in: /Skel

/Skel is intended to be monolithic, meaning that the GUI should run from a mount, once 
a diskless system has booted and mounted a directory with its core libraries. 

FvwmSkeleton provides a user installation script, which symlinks .bashrc and many other 
.rc files to the ones in /Skel. While this could be done with /etc/skel in the normal 
fashion, FvwmSkeleton is separated to allow for localization. 

See INSTALL.txt for details. Foo. 

