# We Study Git

1. Install Java
First you need to have the Java JDK (Java Development Kit) installed; having the JRE (Java Runtime Environment) is not enough. To check if you have the JDK installed, open a command prompt or terminal and type javac -version. If you have a JDK
 
installed, you will see your javac version output, eg. javac 1.7.0_01. If you get an error that javac is not a recognized command, download and install the Java JDK.

2. Download Gradle
Download from Gradle site (http://www.gradle.org/installation)
3. Unpack and Set System variables

Windows

Unzip the Gradle download to the folder to which you would like to install Gradle, eg. “C:\Program Files”. 
The subdirectory gradle-x.x will be created from the archive, where x.x is the version.
Add location of your Gradle “bin” folder to your path. 
Open the system properties (WinKey + Pause), select the “Advanced” tab, and the “Environment Variables” button, 
then add “C:\Program Files\gradle-x.x\bin” (or wherever you unzipped Gradle) to the end of your “Path” variable under System Properties. 
Be sure to omit any quotation marks around the path even if it contains spaces. Also make sure you separated from previous PATH entries with a semicolon “;”.
In the same dialog, make sure that JAVA_HOME exists in your user variables or in the system variables and it is set to the location of your JDK, e.g. 
C:\Program Files\Java\jdk1.7.0_06 and that %JAVA_HOME%\bin is in your Path environment variable.
Open a new command prompt (type cmd in Start menu) and run gradle –version to verify that it is correctly installed.

Mac/Linux

Extract the distribution archive, i.e. gradle-x.x-bin.tar.gz to the directory you wish to install Gradle. 
These instructions assume you chose /usr/local/gradle. The subdirectory gradle-x.x will be created from the archive.
In a command terminal, add Gradle to your PATH variable: export PATH=/usr/local/gradle/gradle-x.x/bin:$PATH
Make sure that JAVA_HOME is set to the location of your JDK, e.g. 
export JAVA_HOME=/usr/java/jdk1.7.0_06 
and that $JAVA_HOME/bin is in your PATH environment variable.
Run gradle –version to verify that it is correctly installed.
You now have Gradle set up! Stay tuned for another post on how to build a simple Gradle project.

More reading:

Gradle – Installation Instructions
Gradle – Users Guide

OpaOpa
111
