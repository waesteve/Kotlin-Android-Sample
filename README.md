# Kotlin-Android-Sample

##Getting started with Android and Kotlin

This tutorial walks us through creating a simple Kotlin application for Android using Android Studio.

Installing the Kotlin plugin

The Kotlin plugin is bundled with Android Studio starting from version 3.0. If you use an earlier version, you'll need to install the Kotlin plugin. Go to File | Settings | Plugins | Install JetBrains plugin… and then search for and install Kotlin. If you are looking at the "Welcome to Android Studio" screen, choose Configure | Plugins | Install JetBrains plugin… You'll need to restart the IDE after this completes.

##Creating a project

It’s extremely easy to start using Kotlin for Android development. In this tutorial we’ll follow the warming up process with Android Studio. If using Intellij IDEA with Android, the process is almost the same.


##Converting Java code to Kotlin

Open MainActivity.java file. Then invoke action Convert Java File to Kotlin File. You can do it by several ways. The easiest one is to invoke Find Action and start typing an action name (like in a screencast below). Alternatively you can call this option via the Code | Convert Java File to Kotlin File menu entry or by using the corresponding shortcut (you can find it at the menu entry).

##Configuring Kotlin in the project

If you start editing this file, Android Studio shows you a prompt that Kotlin is not configured, so you can configure it.

##Building and publishing the Kotlin application for Android

You are now ready to build the application and run it on an emulator or device. This works in exactly the same way as in Java. You can make a release of the application and sign it similarly to what you do for an Android application written in Java.

Kotlin has a rather small runtime file size: the library is approximately 859KB (as of 1.1.2-2). This means Kotlin adds just a little to .apk file size.

Kotlin compiler produces byte-code, thus there really is no difference in terms of look and feel of Kotlin applications versus those written in Java.
