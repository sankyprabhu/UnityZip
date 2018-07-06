# Unity-ZipDownload

## Overview

A sample which download a ZIP file from a remote web server with the given url and save it to the persistence folder then unzip all image files that were in zip file. 
After finishing unzip, it loads one of image file and assign it to a mesh renderer's main texture.

Note that the path manipulation done here is with [Application.persistentDataPath](http://docs.unity3d.com/ScriptReference/Application-persistentDataPath.html), so it works for all known platforms of Unity3D.

There issample scene.

* SimpleZipDownloader - It downloads a zip file via coroutine. and display Image

* Main Script is - SimpleZipDownloader
