# Azure Pipelines Windows Container 1803 image

The following software is installed on machines in the Azure Pipelines **Windows Container 1803** (v20190930.2) pool.

Components marked with **\*** have been upgraded since the previous version of the image.


## Chocolatey

_Version:_ 0.10.15<br/>
_Environment:_
* PATH: contains location for choco.exe

## Docker

_Version:_ 19.03.2<br/>
_Environment:_
* PATH: contains location of docker.exe

## Docker-compose

_Version:_ 1.24.0<br/>
_Environment:_
* PATH: contains location of docker-compose.exe

## Powershell Core

_Version:_ 6.2.3<br/>

## Docker images

The following container images have been cached:
* microsoft/aspnet:4.7.2-windowsservercore-1803 (Digest: sha256:75bcfa62a231715c8864271db05f126cec9c86b3fd3c9d3048e48144eeddc314)
* microsoft/dotnet-framework:4.7.2-sdk-windowsservercore-1803 (Digest: sha256:4002d333d9adb3ab00cfc01e9ee11f2bb8ceacd9612eea916a7d68fa70b5f05c)
* microsoft/windowsservercore:1803 (Digest: sha256:9b22618ec9b832f7e74c5461b67761423fea83dd10bf627fe715e232aad0dc1e)
* microsoft/nanoserver:1803 (Digest: sha256:47aa6f7f8ff1a02acc34b9f22689e9c89b3387efdd7c0f2cf6da9db810c0d4de)
* mcr.microsoft.com/windows/servercore:1803 (Digest: sha256:4374dbc78737bfec459fe6e2047466faa7c21a03aec362ce61735692ed54e598)
* mcr.microsoft.com/windows/nanoserver:1803 (Digest: sha256:bc5c1878a69c4538d55bc74e50b7dbafafff1a373120e624e8bad646a0a505dc)
* microsoft/aspnetcore-build:2.0-nanoserver-1803 (Digest: sha256:82ad5218bb554d0b44ca54c21aba78b5ae10b92cead389d71328614b99fc47af)

## Node.js

_Version:_ 10.16.3<br/>
_Architecture:_ x64<br/>
_Environment:_
* PATH: contains location of node.exe<br/>
* Gulp CLI version: 2.2.0 Local version: Unknown<br/>
* Grunt grunt-cli v1.3.2<br/>
* Bower 1.8.8<br/>
* Yarn 1.19.0<br/>

> Note: You can install and use another version of Node.js on Microsoft-hosted agent pools using the [Node tool installer](https://docs.microsoft.com/vsts/pipelines/tasks/tool/node-js) task.

## npm

_Version:_ 6.9.0<br/>
_Environment:_
* PATH: contains location of npm.cmd

## .NET Core

The following runtimes and SDKs are installed:

_Environment:_
* PATH: contains location of dotnet.exe

_SDK:_
* 2.2.105 C:\Program Files\dotnet\sdk\2.2.105
* 2.2.104 C:\Program Files\dotnet\sdk\2.2.104
* 2.2.103 C:\Program Files\dotnet\sdk\2.2.103
* 2.2.102 C:\Program Files\dotnet\sdk\2.2.102
* 2.2.101 C:\Program Files\dotnet\sdk\2.2.101
* 2.2.100 C:\Program Files\dotnet\sdk\2.2.100
* 2.1.505 C:\Program Files\dotnet\sdk\2.1.505
* 2.1.504 C:\Program Files\dotnet\sdk\2.1.504
* 2.1.503 C:\Program Files\dotnet\sdk\2.1.503
* 2.1.502 C:\Program Files\dotnet\sdk\2.1.502
* 2.1.500 C:\Program Files\dotnet\sdk\2.1.500
* 2.1.403 C:\Program Files\dotnet\sdk\2.1.403
* 2.1.402 C:\Program Files\dotnet\sdk\2.1.402
* 2.1.401 C:\Program Files\dotnet\sdk\2.1.401
* 2.1.400 C:\Program Files\dotnet\sdk\2.1.400
* 2.1.4 C:\Program Files\dotnet\sdk\2.1.4
* 2.1.302 C:\Program Files\dotnet\sdk\2.1.302
* 2.1.301 C:\Program Files\dotnet\sdk\2.1.301
* 2.1.300 C:\Program Files\dotnet\sdk\2.1.300
* 2.1.202 C:\Program Files\dotnet\sdk\2.1.202
* 2.1.201 C:\Program Files\dotnet\sdk\2.1.201
* 2.1.200 C:\Program Files\dotnet\sdk\2.1.200
* 2.1.2 C:\Program Files\dotnet\sdk\2.1.2
* 2.1.105 C:\Program Files\dotnet\sdk\2.1.105
* 2.1.104 C:\Program Files\dotnet\sdk\2.1.104
* 2.1.103 C:\Program Files\dotnet\sdk\2.1.103
* 2.1.102 C:\Program Files\dotnet\sdk\2.1.102
* 2.1.101 C:\Program Files\dotnet\sdk\2.1.101
* 2.1.100 C:\Program Files\dotnet\sdk\2.1.100
* 2.0.3 C:\Program Files\dotnet\sdk\2.0.3
* 2.0.0 C:\Program Files\dotnet\sdk\2.0.0
* 1.1.9 C:\Program Files\dotnet\sdk\1.1.9
* 1.1.8 C:\Program Files\dotnet\sdk\1.1.8
* 1.1.7 C:\Program Files\dotnet\sdk\1.1.7
* 1.1.5 C:\Program Files\dotnet\sdk\1.1.5
* 1.1.4 C:\Program Files\dotnet\sdk\1.1.4
* 1.1.13 C:\Program Files\dotnet\sdk\1.1.13
* 1.1.12 C:\Program Files\dotnet\sdk\1.1.12
* 1.1.11 C:\Program Files\dotnet\sdk\1.1.11
* 1.1.10 C:\Program Files\dotnet\sdk\1.1.10
* 1.0.4 C:\Program Files\dotnet\sdk\1.0.4
* 1.0.1 C:\Program Files\dotnet\sdk\1.0.1

_Runtime:_
* 2.2.3 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.3
* 2.2.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.2
* 2.2.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.1
* 2.2.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.2.0
* 2.1.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.9
* 2.1.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.8
* 2.1.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.7
* 2.1.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.6
* 2.1.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.5
* 2.1.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.4
* 2.1.3 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.3
* 2.1.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.2
* 2.1.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.1
* 2.1.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.0
* 2.0.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.9
* 2.0.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.7
* 2.0.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.6
* 2.0.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.5
* 2.0.3 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.3
* 2.0.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.0
* 1.1.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.9
* 1.1.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.8
* 1.1.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.7
* 1.1.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.6
* 1.1.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.5
* 1.1.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.4
* 1.1.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.2
* 1.1.12 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.12
* 1.1.11 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.11
* 1.1.10 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.10
* 1.1.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.1
* 1.0.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.9
* 1.0.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.8
* 1.0.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.7
* 1.0.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.5
* 1.0.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.4
* 1.0.15 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.15
* 1.0.14 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.14
* 1.0.13 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.13
* 1.0.12 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.12
* 1.0.11 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.11
* 1.0.10 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.10

## Git

_Version:_ 2.23.0<br/>
_Environment:_
* PATH: contains location of git.exe

## Git Large File Storage (LFS)

_Version:_ 2.8.0<br/>
_Environment:_
* PATH: contains location of git-lfs.exe
* GIT_LFS_PATH: location of git-lfs.exe

## Subversion

_Version:_ 1.8.17<br/>
_Environment:_
* PATH: contains location of svn.exe
