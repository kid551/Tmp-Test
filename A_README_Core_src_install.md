
# Assets in SAFS Setup directory

FILE                         |         PURPOSE
------------ | -------------
A_README.txt                    |       This README file.
GNU General Public License.txt  |       Public License Text.
SAFSReleaseNotes....htm         |       Release Notes for this Release.
SetupSAFS.WSF                   |       Default Silent Install Script (WSH 5.6) <br /> <br /> Examples: <br /> If you prefer STAF 3, modify 2/3 to 3; If STAF 2, modify 2/3 to 2. <br /> 1. ```SetupSAFS.WSF -installstafversion 2/3 -noprompt``` -- to install SAFS with RATIONAL and STAF 2 or 3 <br /> 2. ```SetupSAFS.WSF -installstafversion 2/3 -noprompt -norational``` -- to install SAFS with STAF 2 or 3 <br /> 3. ```SetupSAFS.WSF -nostaf -noprompt -norational``` -- to install only SAFS <br /> 4. ```SetupSAFS.WSF -installstafversion 2/3 -noprompt -nosafs -norational``` -- to install only STAF 2 or 3 <br /> 5. ```SetupSAFS.WSF -removestaf c:\staf 2/3 -noprompt -nostaf -nosafs -norational``` -- to uninstall only STAF 2 or 3
SetupSAFS.WSF.README.txt        |       A README file to tell how to use *SetupSAFS.WSF*
SetupSAFS.VBS                   |       Deprecated. Use *SetupSAFS.WSF*.
SetupSAFS.README.htm            |       Instructions for SAFS Setup.
SetupRobotJ.README.htm          |       Instructions for RobotJ Project Setup.
SetupRuntime.README.htm         |       Instructions for running SAFS with Rational Robot.
SAFSInstall.JAR                 |       Java Install Program (called by script).
SAFSInstall.ZIP                 |       Files for Java Install Program.
STAF2611-setup-win32.JAR        |       STAF 2 Install Program (called by script).
STAF333-setup-win32.exe         |       STAF 3 Install Program (called by script).
SAFSTID.INI                     |       Used by Tool-Independent Driver.
Remove???Classpath.WSF          |       Used by scripts or invoked by user. (The question mark indicates multiple same type naming file.)
Setup???Classpath.WSF           |       Used by scripts or invoked by user. (The question mark indicates multiple same type naming file.)
_SharedFunctions.VBS            |       Functions used by scripts.
_SharedRationalFunctions.VBS    |       Functions used by scripts.
UninstallSAFS.wsf               |       Script to uninstall SAFS.