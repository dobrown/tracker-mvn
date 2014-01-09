tracker-mvn
===========

This is the release code for the Tracker video analysis and modeling tool from Open Source Physics (OSP). You can build Tracker from this code using Maven.

Before you start, check the following requirements:

  1. Git, Maven and Java must be installed on your local machine.
  2. The QuickTime for Java library "QTJava.zip" (not available from a Maven repository) must be in your classpath unless you delete the quicktime source files as described in step 2 below.

To build Tracker:

  1. Use Git to clone this repository (command: "git clone https://github.com/dobrown/tracker-mvn.git")
  2. If you don't want the QuickTime video engine (e.g., Linux users), delete the tracker-mvn/src/main/java/org/opensourcephysics/media/quicktime directory
  3. Set the current directory to the tracker-mvn directory (which contains the pom.xml file)
  4. Use Maven to create the tracker jar file (command: "mvn package")
  5. The tracker jar file will be in the tracker-mvn/target directory

===========

<strong>Note:</strong> The best way to install Tracker for educational or personal use is to use one of the installers available on the Tracker home page at http://www.cabrillo.edu/~dbrown/tracker/. 

The code in this repository is updated only when new Tracker versions are released. You can find the active development code in 3 separate repositories hosted by OpenSourcePhysics (https://github.com/OpenSourcePhysics).
