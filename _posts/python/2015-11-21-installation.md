---
layout: post
title: "Installation"
date: "2015-11-21 12:17"
---

Python is supported by most operating systems. Unless you are using Windows, your operating system likely already has Python installed. We are using Python 2.7 because most tools used for animation, VFX, or games uses Python 2.7. The only exception that I know of is Blender and Natron, which both uses Python 3.

Windows Installation
--------------------
1. Click on the link [here](https://www.python.org/downloads/windows/). Pick the download labeled `Latest Python 2 Release - Python 2.7.x` The `x` is the latest minor version.
2. Select the right Windows version for your computer. If you have a 32 bit Windows, then select the `Windows x86 MSI installer`. If you have a 64 bit Windows, select the `Windows x86-64 MSI installer`. If you don't know which version you have, the 32 bit one is usually a safe bet.
3. Find where the installer was saved to your hard drive, or if you simply ran the installer from your internet browser, go through the installation steps.
4. (Optional) Add Python to the `PATH` environment variable. There's a tutorial [here](http://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/) that outlines how to add things to the environment variables. Before you add Python to the environment variables, you will want to find where your `python.exe` executable is. It is most likely in `C:\Python27`. Add that path to the `PATH` environment variable.

Mac OSX Installation
--------------------
1. Click on the link [here](https://www.python.org/downloads/mac-osx/). Pick the download labeled `Latest Python 2 Release - Python 2.7.x` The `x` is the latest minor version.
2. Select the right Mac OS X version for your computer. If you have a 32 bit Mac OS X, then select the `Mac OS X 32-bit i386/PPC installer`. If you have a 64 bit Mac OS X, select the `Mac OS X 64-bit/32-bit installer`. If you don't know which version you have, the 32 bit one is usually a safe bet.
3. Find where the installer was saved to your hard drive, or if you simply ran the installer from your internet browser, go through the installation steps.

Linux Installation
------------------
Python is most likely installed on your machine. Go to your terminal and type `python`. You should see something like this:

```
Python 2.7.5 (default, Jun 24 2015, 00:41:19)
[GCC 4.8.3 20140911 (Red Hat 4.8.3-9)] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

If you do, type `quit()`, and then press enter. We'll play around in that space more later.

Testing the Install
===================
If you are in Windows and didn't add the Python path to the `PATH` environment variable, then search for and run IDLE in the Windows Start Menu. If you added Python to the `PATH` environment variable, or not on Windows, then open your command shell and type `python`. You should see something like this:

```
Python 2.7.5 (default, Jun 24 2015, 00:41:19)
[GCC 4.8.3 20140911 (Red Hat 4.8.3-9)] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

If you do, then congradulations! You have Python successfully installed. Type `quit()` and press enter.

Next Steps
==========
Now that we have Python installed, we are ready to learn about [Python's types]({{ site.baseurl }}{% post_url /python/2015-11-21-types %}).
