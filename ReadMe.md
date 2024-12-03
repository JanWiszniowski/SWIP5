A. Content of the repository
The https://git.plgrid.pl/projects/SWIP/repos/SWIP5_public/Release directory contains all the files needed for the program to run,
including exe and dll files, as well as files with a sample configuration.
There are sample seismic event files in the Data directory. The structure of the Release subdirectories is as follows:
Cache / Icons: The Cache directory is used to store temporary files. It has to exist to work program properly.
  Cache / Icons stores the "beach balls" of the moment tensors seismic. Its lack makes it impossible to draw them.
Config: The Config directory contains all configuration files. In the public version, it only contains an example configuration
  for the reservoir-induced seismicity area at Song Tranh 2, Vietnam.
Icons: The Icons directory contains program icons.
Locsat: The Locsat directory contains holograms for the LocSAT plug-in for locating quakes.
Logs: The logs directory contains program operation logs saved while the program is running - mainly "swip.log".
Plugins: This directory contains all program plugins - dll files. Their addition or deletion allows you
  to change the functionality of the program.

B. Downloading the program

1. The first way of downloading is to download compressed files. For this purpose,
on the site https://git.plgrid.pl/projects/SWIP/repos/SWIP5_public/browse/Release click the [...] button
and select Download. After saving the zip file, it should be unpacked in the selected directory.
Any decompression program can be used for this. The program will be copied to subdirectory:
.\Release\
It can be invoked with the SWIP5 command from the. \Release\ directory. Calling from a different directory
will result in wrong path assignments and, as a result, the program malfunctions.

2. The second way is to clone the program using GIT.  You need any GIT program.
There are many ways to install git on Windows as well. The official version is available for download on the Git website.
Go to http://git-scm.com/download/win and the download will start automatically.
The project is called Git for Windows (also msysGit). After installing the guitar, please enter your personal details:
git config --global user.name "First Name Last Name"
git config --global user.email mail@instytut.pl
then clone the program codes with the command:
git clone https://git.plgrid.pl/scm/swip/SWIP5_public.git
The program will be copied (cloned) to the subdirectory:
\SWIP5_public\Release\
It can be run with the SWIP5 command from the directory. \SWIP5_public\Release\. Calling from another directory
will result in assigning wrong paths and as a result, the program will not work properly.
