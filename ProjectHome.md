# Quick Windows Apt tools #

## Why QWinApt? ##

I like **ubuntu**'s Install/Uninstall tools very much. Hope to find a same tool under windows, but there is none. so, I deside to write a application by myself.

It will be simple, and enhance step by step.

for some personal reason, I use C# and .net2.0.

  1. Ubuntu Like GUI
  1. Easy Use
  1. Most of _Green_ and _Free_ softwares
  1. **Free**

# Tools #
  * ### QWinAptClient ###
> Like Ubuntu's install tool. It load Data from DB file. You can use it to download applications, or delete applications that you have already downloaded.Because Windows's installation is totally different from Linux's. So it only download file for you, you can install it as your like.
  * ### QWinAptConfigTool ###
> You can use this tool to config your own DB file. Actually I will use it to maintain the main   DB file on this server. I'm also glad to receive users' config file that make by this tool, then I could easy to merge it with main DB file.
  * ### QWinAptParser ###
> I use it(these) to create DB file from other page.

You can download source code in source tunck.

# Usage #
  * ### Download files ###
> Download files from this page, includes QWinApt-x.x.x.zip(Main Client Application),wget.zip(if you don't have one),zh-CN.zip(if you are Chinese user).
  * ### Install it ###
> It is totally Green, just extract to you disk.If you also downloaded zh-CN.zip, put the folder zh-CN in the same directory with WinApt.Client.exe.If you downloaded wget.zip, put wget.exe in system %PATH% so the application can find it.
  * ### Need to Know ###
> If you run it at first time, it will:
    1. Popup to request a simple config, which let you chose the base directory that need to save the downloaded files.
    1. Download DB file from Project Home, so make sure your NetWork works fine.
    1. You can Update DB file by click Update button in Main Form.
    1. When you finish download a file, click it with right mouse button, then you can explore it or install it. See pictures follow.

## Snap Shots: ##

### Main Form ###

![http://lh5.google.com/hzgnpu/Ruqp5gck-iI/AAAAAAAAAI0/3BJu7DOYDfM/winapttool.jpg](http://lh5.google.com/hzgnpu/Ruqp5gck-iI/AAAAAAAAAI0/3BJu7DOYDfM/winapttool.jpg)

### Download a File ###

![http://lh5.google.com/hzgnpu/Ruqp5gck-jI/AAAAAAAAAI8/W3o346RPiXA/winaptdownload.jpg](http://lh5.google.com/hzgnpu/Ruqp5gck-jI/AAAAAAAAAI8/W3o346RPiXA/winaptdownload.jpg)

### Explore & Install ###

![http://lh3.google.com/hzgnpu/RvISEjq6AbI/AAAAAAAAAKQ/LodwQaMt4Xc/winaptdemo.jpg](http://lh3.google.com/hzgnpu/RvISEjq6AbI/AAAAAAAAAKQ/LodwQaMt4Xc/winaptdemo.jpg)