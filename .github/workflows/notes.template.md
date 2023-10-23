# Interlok (Build ${interlok-version}-RELEASE) Downloads

This is the Interlok download page; you have the chance to download the following items.

You can find the [release notes here](https://interlok.adaptris.net/interlok-docs${doc-version}/#/pages/overview/changelog?id=version-${interlok-version-int}) and some [specific installation instructions here](https://interlok.adaptris.net/interlok-docs${doc-version}/#/pages/overview/adapter-installation). Have Fun !

# Files

- [base-filesystem.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-base-filesystem/1.1.0/interlok-base-filesystem-1.1.0.zip)
- [base-filesystem-with-templates.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-base-filesystem/1.1.0/interlok-base-filesystem-1.1.0-with-templates.zip)
- [interlok-installer-cmd.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer-cmd/${interlok-version}-RELEASE/interlok-installer-cmd-${interlok-version}-RELEASE.zip)
- [interlok-installer-linux.jar](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-linux.jar)
- [interlok-installer-linux.tar.gz](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-linux.tar.gz)
- [interlok-installer-mac.jar](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-mac.jar)
- [interlok-installer-mac.tar.gz](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-mac.tar.gz)
- [interlok-installer-win.jar](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-win.jar)
- [interlok-installer-win.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-win.zip)

# Java based Installer

This installer variant allows you to pre-select optional components that you want to bundle into your installation (it uses gradle behind the scenes) and can optionally generate the gradle bootstrap files required for managing projects.

This project is hosted publicly at [GitHub](https://github.com/adaptris/interlok-installer).

# Before you start...

- You will need to install Java ${java-version} (or later) to successfully run Interlok.
- However, Java ${java-version} is currently required if you wish to use the java installer.
  - [Azul Systems](https://www.azul.com/downloads/zulu-community/) offer pre-built images of OpenJDK for most platforms; they also have a JavaFX enabled bundle
  - [Amazon](https://aws.amazon.com/corretto/) offer pre-built images of OpenJDK for some platforms
  - [AdoptOpenJDK](https://adoptopenjdk.net/) offer pre-built images of OpenJDK for some platforms
  - [OpenJDK](https://openjdk.java.net/install) have pre-built images for Linux systems and Windows (latest versions only)
  - You can still download one from [Oracle](http://www.oracle.com/technetwork/java/index.html) or contact your OS manufacter
- More information regarding installation can be found in our [interlok-docs](https://interlok.adaptris.net/interlok-docs${doc-version}/#/pages/overview/adapter-installation).

# Windows Notes

The Windows install options are:

- Download [interlok-installer-win.jar](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-win.jar)
java -jar ./interlok-installer-win.jar
- Follow the installer instructions

or alternatively:

- Download and unzip [interlok-installer-win.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-win.zip)
Execute \bin\interlok-installer.bat
- Follow the installer instructions

# Linux Notes

The Linux install options are:

- Download [interlok-installer-linux.jar](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-linux.jar)
java -jar ./interlok-installer-linux.jar
- Follow the installer instructions

or alternatively:

- Download and unzip [interlok-installer-linux.tar.gz](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-linux.tar.gz)
Execute \bin\interlok-installer
- Follow the installer instructions

# macOS Notes

The macOS install options are:

- Download [interlok-installer-mac.jar](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-mac.jar)
java -jar ./interlok-installer-mac.jar
- Follow the installer instructions

or alternatively:

- Download and unzip [interlok-installer-mac.tar.gz](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer/${interlok-version}-RELEASE/interlok-installer-${interlok-version}-RELEASE-mac.tar.gz)
Execute \bin\interlok-installer
- Follow the installer instructions

# Command Line Installer Notes

Command line installer for Interlok. This automatically downloads the selected optional components along with the base system to build an Interlok installation in your preferred location.

- Download [interlok-installer-cmd.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-installer-cmd/${interlok-version}-RELEASE/interlok-installer-cmd-${interlok-version}-RELEASE.zip)
- Unzip or untar the archive file
- Launch bin/interlok-installer.bat or bin/interlok-installer depending if you are on windows or linux/mac
- Use the property interlokDistDirectory to specify the directory where you want to install Interlok.
- `./interlok-installer -DinterlokDistDirectory=/opt/Adaptris/Interlok`

# Manual Install Notes

These downloads for intended for people who wish to upgrade/install without running an installer.

If you are selecting the non-installer option, you may want to read our documentation on [running Interlok directly from the commandline](https://interlok.adaptris.net/interlok-docs${doc-version}/#/pages/overview/adapter-commandline?id=running-directly-from-the-commandline)

- [base-filesystem.zip](https://nexus.adaptris.net/nexus/service/local/repositories/releases/content/com/adaptris/interlok-base-filesystem/1.1.0/interlok-base-filesystem-1.1.0.zip) : The base filesystem
