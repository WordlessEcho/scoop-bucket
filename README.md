# Scoop Bucket Template

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/WordlessEcho/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/WordlessEcho/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/WordlessEcho/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/WordlessEcho/scoop-bucket/actions/workflows/excavator.yml)

PR from me doesn't accepted by Scoop yet.

## Install

```pwsh
scoop bucket add echo https://github.com/WordlessEcho/scoop-bucket
scoop install echo/<manifestname>
```

## Packages
### natmap
This project is used to establish a TCP/UDP port mapping from an ISP NAT public address to local private address.

[ScoopInstaller/Main#7481](https://github.com/ScoopInstaller/Main/issues/7481)

```pwsh
scoop install echo/natmap
```

## intellij-jbr25*
JetBrains Runtime is a fork of OpenJDK available for Windows, Mac OS X, and Linux. It supports enhanced class redefinition (DCEVM), features optional JCEF, a framework for embedding Chromium-based browsers, includes a number of improvements in font rendering, keyboards support, windowing/focus subsystems, HiDPI, accessibility, and performance, provides better desktop integration and bugfixes not yet present in OpenJDK.

[ScoopInstaller/Java#576](https://github.com/ScoopInstaller/Java/issues/576)

```pwsh
scoop install echo/intellij-jbr25
scoop install echo/intellij-jbr25-jcef
scoop install echo/intellij-jbr25-sdk
scoop install echo/intellij-jbr25-sdk-jcef
```
