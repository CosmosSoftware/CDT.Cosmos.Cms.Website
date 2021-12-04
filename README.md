# Cosmos CMS (Publisher)

Each Cosmos CMS website is actually made up of two parts--and two repositories stored in GitHub:

* The "[Editor](https://github.com/CosmosSoftware/Cosmos.Cms)" is the web application used to create content for a website.
* The "[Publisher](https://github.com/CosmosSoftware/CDT.Cosmos.Cms.Website)" application is used to publish web content on the web.

Notes:

* This repository is for the _*Publisher*_.
* Use the Nuget package [CDT.Cosmos.Cms.Common](https://www.nuget.org/packages/CDT.Cosmos.Cms.Common/) to turn your website into a "Publisher."

This dual system ensures that the publishing website is unhindered with the overhead of the publishing logic and infrastructure, and it allows the publisher site to almost any kind of funtionality included in it.  

## Cloud-first Design

C/CMS is built for [the cloud](https://github.com/CosmosSoftware/Cosmos.Cms), and makes use of services such as:

* Content Distribution Networks 
  * Akamai
  * Microsoft
  * Verizon
* Blob storage for assets
* Google Translate (v3)
* OAuth
  * Google
  * Microsoft

C/CMS also takes advantage of the cloud's ability to automatically scale, and, run simultaneously in multiple regions.
