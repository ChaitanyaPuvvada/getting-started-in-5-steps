# Getting Started in 5 Steps
Learn to install and get started with Java, Eclipse, Maven, JUnit, Mockito &amp; Spring in 5 easy steps

# Java

## Prerequisites
- None

## Installation

Search for “install java jdk” on google. 
google-search-install-java-jdk.png

Choose the first link. You should go to the oracle site.
oracle-website-java-installation.png

Select the Java Platform JDK Link.  
java-installation-icon.png


Accept the license agreement.  
Choose the Java Install for your Operating System.  If you are windows 64 bit operating system, choose the Windows x64 java. 
Wait for the download to complete. Double click the file from the downloads folder. For Windows  
Java Installer would launch up. Click Continue.  
Click install on the next screen 
Have a coffee and wait for the installation to complete. When the installation is complete, you would see the screen below:  
Click close. We are ready to Rock and Roll. Do a Dance.

## Check

If you are on Windows : Open the Command Prompt window by clicking the Start button  , clicking All Programs, clicking Accessories, and then clicking Command Prompt. (or use Ctrl + Esc, and type in cmd and launch up command)

If you are on Mac or other OS, launch up Terminal.

Type in the command “java –version” as shown in the screen. If it does not work, go to the trouble shooting section.  


## Troubleshooting
15.	Troubleshooting:
a.	Check if there are any pre-existing Java installs. Uninstall them and reinstall again.
b.	Temporarily turn off firewalls and antivirus software.
c.	If you get file corrupt message, download the installation file again.
d.	Check if you are on 32-bit OS or 64-bit OS and ensure you are making use of the right java download.


# Eclipse

1.	Check if Java is installed properly. Type in the command “java –version” as shown in the screen. If it does not work, go to the trouble shooting section of Java or Reinstall Java.  
2.	Search google for “download eclipse” and choose the first result. 
3.	Choose the right Operation System. 
4.	We recommend to choose “Eclipse IDE for Java EE Developers”. Choose 32 bit or 64 bit based on your operating system. (Right-click My Computer, and then click Properties. If "x64 Edition" is listed under System, your processor is capable of running a 64-bit version of Windows.)
5.	Wait for the download to complete. Extract the zip file to a folder (Example : c:\eclipse).
6.	Note that there is a known problem with the built-in decompression utility on all current versions of Windows. We recommend that you use a more robust decompression utility such as the open source 7zip when decompressing an Eclipse download. Some people report success when initially decompressing Eclipse into a root directory (e.g. c:\) and then moving it to a more appropriate home (e.g. c:\Program Files\Eclipse)
7.	Refer to Troubleshooting section of https://wiki.eclipse.org/Eclipse/Installation for more details about troubleshooting Installations

## Prerequisites
- Java

## Installation

## Check

## Troubleshooting

## First 5 Steps

### 4. Importing Java Eclipse Project
1.	Download the zip file & Un zip (extract the contents) the zip file.
2.	Check if the folder contains a .project file.  Highlighted in the image below. You can also open the folder in windows explorer and check if it contains .project & .settings & .classpath files . (On mac these files are hidden. We used the command ls –la) 
3.	Copy the folder path into clipboard. (ctrl + c)  
4.	Launch up Eclipse and give folder name (Other folder name) as the workspace folder. Click OK.  
5.	Once Eclipse Launches up Go To File -> Import -> General -> Existing Projects into Workspace. Click Next. 
6.	Select Root Directory as the folder we copied earlier (the folder which contained .project, .classpath and .settings files).  
7.	You should see a project highlighted in the Projects section.  
8.	If you do not see any project, you are checking a wrong folder. Make sure you browse and select the correct folder containing the .project and the .classpath files.
9.	Click Finish.
10.	Your project would be imported and You are ready to work on it.  
11.	Good Luck and Have a Safe Party

### 5. Importing a Maven Project into Eclipse
1.	Download the zip file & Un zip (extract the contents) the zip file.
2.	Check if the folder contains a pom.xml file.  Highlighted in the image below. You can also open the folder in windows explorer and check if it contains pom.xml file.  
3.	Copy the folder path into clipboard. (ctrl + c)  
4.	Launch up Eclipse and give folder name (Other folder name) as the workspace folder. Click OK.  
5.	Once Eclipse Launches up Go To File -> Import -> Maven -> Existing Maven Projects. Click Next.  
6.	Select Root Directory as the folder we copied earlier (the folder which contained the pom.xml file).  
7.	You should see a project highlighted in the Projects section.  
8.	If you are in a multi module project, then you would see multi projects ready for import.  
9.	If you do not see any project, you are checking a wrong folder. Make sure you browse and select the correct folder containing the pom.xml files.
10.	Click Finish.
11.	Your project would be imported and You are ready to work on it.  
12.	Good Luck and Have a Safe Party


# Maven

## Prerequisites

- Java
- Embedded with Eclipse

## Installation
- Recommended to use Maven embedded in Eclipse

## Check Embedded Maven in Eclipse

### Standalone installation
1.	Check if Java is installed properly. Type in the command “java –version” as shown in the screen. If it does not work, go to the trouble shooting section of Java or Reinstall Java.  
2.	Note that Maven 3.3 requires JDK 1.7 or above, Maven 3.2 requires JDK 1.6 or above, while Maven 3.0/3.1 requires JDK 1.5 or above.
3.	Download Apache Maven. Visit Maven official website, download the Maven zip file. Example : apache-maven-3.3.3-bin.zip  
4.	On Windows
a.	Unzip the distribution archive, i.e. apache-maven-3.3.3-bin.zip to the directory you wish to install Maven 3.3.3. These instructions assume you chose C:\maven. The subdirectory apache-maven-3.3.3 will be created from the archive.
b.	Add the unpacked distribution's bin directory to your user PATH environment variable by opening up the system properties (WinKey + Pause), selecting the "Advanced" tab, and the "Environment Variables" button, then adding or selecting the PATH variable in the user variables with the value C:\maven\apache-maven-3.3.3\bin.
c.	You can check if you are using the right value by opening up the folder using “cd C:\maven\apache-maven-3.3.3\bin” and then typing the command “mvn --version”.
d.	Make sure that JAVA_HOME exists in your user variables or in the system variables and it is set to the location of your JDK, e.g. C:\Program Files\Java\jdk1.7.0_51.
e.	Open a new command prompt (Winkey + R then type cmd) (or terminal on mac) and run “mvn –version” to verify that it is correctly installed.  
5.	Unix-based Operating Systems (Linux, Solaris and Mac OS X)
a.	Extract the distribution archive, i.e. apache-maven-3.3.3-bin.tar.gz to the directory you wish to install Maven 3.3.3. These instructions assume you chose /usr/local/apache-maven. The subdirectory apache-maven-3.3.3 will be created from the archive.
b.	In a command terminal, add unpacked distribution's bin to your PATH environment variable, e.g. export PATH=$PATH:/usr/local/apache-maven/apache-maven-3.3.3/bin.
c.	Make sure that JAVA_HOME is set to the location of your JDK, e.g. export JAVA_HOME=/usr/java/jdk1.7.0_51 .

## Check
d.	Run mvn --version to verify that it is correctly installed.  

## Troubleshooting

## First 5 Steps

###Important Maven Commands
Set Up
1.	First you need a maven project. You can download maven projects that are associated with the video. Extract the zip file from our website www.in28minutes.com and put it into a directory. Identify the top most directory containing the pom.xml. That’s your root pom.xml
2.	Below is the structure of Zip for our Maven Tutorial.  We want to run the third example. The root pom.xml for third project is present in the folder “3.multi-module-maven-project” 
3.	Open up Command prompt or Terminal. CD to this folder. For example  “cd c:\maven-example\3.multi-module-maven-project”
4.	List the files in the folder. Dir command on windows (and ls on unix based OS). You should see the pom.xml.  
5.	You are all set to run the maven commands on this project.
mvn clean install
1.	This command is used to build any project which is created using Maven.  It will build all projects (and subprojects or modules) which are present in the pom.xml.
2.	Follow the instructions in the Set Up section. You should be in cmd prompt or terminal and your present working directory should be the one containing pom.xml of the project you want to work on.  
3.	Run the command “mvn clean install”  
4.	All projects should build and you should see Build Success message.  
5.	If you don’t make sure you are in the correct directory. Go to the “Set Up” section and retry the steps again.

mvn tomcat7:run
1.	First run “mvn clean install” on the root project. Follow steps given above.
2.	Switch to directory containing the web application (war pom.xml).  In the below example the war directory is in28minutes-web-servlet-jsp. 
3.	 Run the command “mvn tomcat7:run”. Everything should succeed and you should see a message that the server is started. Note down the port number. 
4.	Run the application in browser http://localhost:8080/. It should work and you are all setup to run a web application  in tomcat. Good Luck with learning developing applications now..               
5.	 


# JUnit

## Prerequisites
- Java
- Eclipse
- Embedded Maven in Eclipse

## First 5 Steps

# Mockito

## Prerequisites
- Java
- Eclipse
- Embedded Maven in Eclipse
- Knowledge of JUnit

## First 5 Steps

# Spring

## Prerequisites
- Java
- Eclipse
- Embedded Maven in Eclipse

## First 5 Steps

# Kotlin

Coming Soon..

## Prerequisites
- Java
- Eclipse
- Embedded Maven in Eclipse

## Installing Kotlin Plugin for Eclipse

## First 5 Steps

# Postman

Coming Soon..

## Prerequisites
- Java
- Eclipse
- Embedded Maven in Eclipse

## Installing Kotlin Plugin for Eclipse

## First 5 Steps