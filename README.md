## INTRO

Global Proxy App for Android System

ProxyDroid is distributed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.txt) with many other open source software, 
here is a list of them:

 * cntlm - authentication proxy: http://cntlm.sourceforge.net/
 * redsocks - transparent socks redirector: http://darkk.net.ru/redsocks/
 * netfilter/iptables - NAT module: http://www.netfilter.org/
 * transproxy - transparent proxy for HTTP: http://transproxy.sourceforge.net/
 * stunnel - multiplatform SSL tunneling proxy: http://www.stunnel.org/

## This fork uses GitHub Actions to build the APKs

[![Android CI](https://github.com/detunized/proxydroid/actions/workflows/ci.yml/badge.svg)](https://github.com/detunized/proxydroid/actions/workflows/ci.yml)

The APKs could be downloaded from the latest succesful [run](https://github.com/detunized/proxydroid/actions/workflows/ci.yml).

## PREREQUISITES

* JDK 1.6+
* Maven 3.0.5
* Android SDK r17+
* Android NDK r8+

## BUILD

Invoke the building like this

```bash
cd android-studio-project && ./gradlew build
```
