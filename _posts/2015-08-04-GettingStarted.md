---
title: "Getting Started"
bg: purple
color: white
style: left
fa-icon: plug
---


# Getting Started

F# needs to be installed on your system in order to use Ionide:

* [Installing F# on Linux](http://fsharp.org/use/linux/)
* [Installing F# on OSX](http://fsharp.org/use/mac/)
* [Installing F# on Windows](http://fsharp.org/use/windows/)


The easiest way to get Ionide is via the Atom package manager. In Atom, open the **Settings** pane and navigate to the **Install** tab. There, you can search for *ionide-installer* package and click **Install** button to install it.

Unfortunately the Atom package manager's GUI does not currently indicate that the Ionide package installations are in progress. Once they've completed you may need to restart Atom for Ionide to load properly.

Alternatively, if you are more comfortable using the command line, you can install it using *apm*:

~~~
apm install ionide-installer
~~~

The first time you start Atom after installing the *ionide-installer* package, you will have to wait a few seconds for the installer to determine which Ionide packages it needs to install.

If you're interested in how Ionide functions within Atom, checkout the [Atom Getting Started Documentation](https://atom.io/docs)

NOTE - [Ionide-Yeoman](https://atom.io/packages/ionide-yeoman), the F# Project Scaffolding Tool, requires having [*generator-fsharp*](https://www.npmjs.com/package/generator-fsharp) installed on your system - please follow instructions on the *generator-fsharp* page to install it.
