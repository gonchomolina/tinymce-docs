---
layout: default
title: TinyMCE vnumtxt
title_nav: TinyMCE vnumtxt
description: Release notes for TinyMCE vnumtxt
keywords: releasenotes bugfixes
---

{% comment %}
Replace vnumtxt with the version number such as: X.Y.Z
Replace vnumcode with the version number without points, such as XYZ
{% endcomment %}

These release notes provide an overview of the changes for {{site.productname}} vnumtxt, including:

- [TinyMCE vnumtxt new features and enhancements](#tinymcevnumcodenewfeaturesandenhancements)
- [Accompanying Premium Plugin changes](#accompanyingpremiumpluginchanges)
- [Accompanying Premium self-hosted server-side component changes](#accompanyingpremiumself-hostedserver-sidecomponentchanges)
- [Minor changes for TinyMCE vnumtxt](#minorchangesfortinymcevnumcode)
- [General bug fixes](#generalbugfixes)
- [Security fixes](#securityfixes)
- [Deprecated features](#deprecatedfeatures)
- [Known issues](#knownissues)
- [Upgrading to the latest version of TinyMCE 5](#upgradingtothelatestversionoftinymce5)

{{site.releasenotes_for_stable}}

## TinyMCE vnumtxt new features and enhancements

The following new features and enhancements were added for the {{site.productname}} vnumtxt release.

### Improvement Name

## Accompanying Premium Plugin changes

The following premium plugin updates were released alongside {{site.productname}} vnumtxt.

### Premium Plugin Name X.Y.Z

The {{site.productname}} vnumtxt release includes an accompanying release of the **<<Premium Plugin Name>>** premium plugin.

**<<Premium Plugin Name>>** X.Y.Z provides the following improvements:

- <Description>

For information on the <<Premium Plugin Name>> plugin, see: [<<Premium Plugin Name>> plugin]({{site.baseurl}}/plugins/<<Premium Plugin Name>>/).

## Accompanying Premium self-hosted server-side component changes

The {{site.productname}} vnumtxt release includes accompanying changes affecting the {{site.productname}} **self-hosted** services for the following plugins:

- The Enhanced Media Embed plugin (`mediaembed`)
- The Image Tools plugin (`imagetools`)
- The Link Checker plugin (`linkchecker`)
- The Spell Checker Pro plugin (`tinymcespellchecker`)

The Java server-side components (`ephox-spelling.war`, `ephox-hyperlinking.war`, and `ephox-image-proxy.war`) have been updated to **version X.Y.Z**.

This version requires Java 8 or higher. For information on the removal of Java 7 support, see: [Removal of Java 7 support for TinyMCE 5.3 and later]({{site.baseurl}}/release-notes/release-notes53/#removalofjava7support).

For information on:

- The Spell Checker Pro plugin, see: [Spell Checker Pro plugin]({{site.baseurl}}/plugins/premium/tinymcespellchecker/).
- The Link Checker plugin, see: [Link Checker plugin]({{site.baseurl}}/plugins/premium/linkchecker/).
- The Image Tools plugin, see: [Image Tools plugin]({{site.baseurl}}/plugins/opensource/imagetools/).
- The Enhanced Media Embed plugin, see: [Enhanced Media Embed plugin]({{site.baseurl}}/plugins/premium/mediaembed/).
- Deploying the server-side components, see: [Server-side component installation]({{site.baseurl}}/enterprise/server/).

### Security update for self-hosted server-side components

Version X.Y.Z provides security updates for the Java-based server-side components. To deploy the updated version of the server-side components:

1.

For information on:

- Deploying the server-side components, see: [Server-side component installation]({{site.baseurl}}/enterprise/server/).
- Deploying the server-side components using Docker, see: [Containerized service deployments]({{site.baseurl}}/enterprise/server/dockerservices/).

## Minor changes for TinyMCE vnumtxt

{{site.productname}} vnumtxt introduces the following minor changes:

* changelog

## General bug fixes

{{site.productname}} vnumtxt provides fixes for the following bugs:

* changelog

## Security fixes

{{site.productname}} vnumtxt provides fixes for the following security issues:

* changelog

## Deprecated features

The following features have been deprecated with the release of {{site.productname}} vnumtxt:

- [](#).

### The...

## Known issues

This section describes issues that users of {{site.productname}} vnumtxt may encounter and possible workarounds for these issues.

**Outline**

* [](#)

###

**Issue**:

This issue affects ....
<impact>

**Workaround**:

There was no known workaround at the time of the release.

{% assign enterprise = true %}

{% include install/upgrading-info.md %}

{% assign enterprise = false %}
