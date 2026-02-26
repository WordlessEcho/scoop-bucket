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
### natmap (migrated)
This project is used to establish a TCP/UDP port mapping from an ISP NAT public address to local private address.

[ScoopInstaller/Main#7481](https://github.com/ScoopInstaller/Main/issues/7481)

~~scoop install echo/natmap~~

```pwsh
scoop install main/natmap
```

### intellij-jbr25*
JetBrains Runtime is a fork of OpenJDK available for Windows, Mac OS X, and Linux. It supports enhanced class redefinition (DCEVM), features optional JCEF, a framework for embedding Chromium-based browsers, includes a number of improvements in font rendering, keyboards support, windowing/focus subsystems, HiDPI, accessibility, and performance, provides better desktop integration and bugfixes not yet present in OpenJDK.

[ScoopInstaller/Java#576](https://github.com/ScoopInstaller/Java/issues/576)

```pwsh
scoop install echo/intellij-jbr25
scoop install echo/intellij-jbr25-jcef
scoop install echo/intellij-jbr25-sdk
scoop install echo/intellij-jbr25-sdk-jcef
```

### PeerBanHelper
Automatically block unwanted, leeches and abnormal BT peers with support for customized and cloud rules.

[ScoopInstaller/Extras#15752](https://github.com/ScoopInstaller/Extras/issues/15752)

Install a Java before, highly recommand JBR.
```pwsh
scoop install echo/intellij-jbr25
```

Or install liberica25-jre if you are using Windows 7.
```pwsh
scoop install java/liberica25-jre
```

Then:
```pwsh
scoop install echo/peerbanhelper
```
