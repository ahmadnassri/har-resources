# HAR Resources

A hand curated, [community driven](#contributing) list of resources, tools, projects and applications that support [HTTP Archive format (HAR)](https://groups.google.com/forum/?hl=en#!forum/http-archive-specification).

## About

### [HTTP Archive Spec](http://www.softwareishard.com/blog/har-12-spec/)

The widely used HTTP Archive Format (HAR) format specification was initially designed by the [HttpWatch](http://www.httpwatch.com/company/) and [Firebug](http://getfirebug.com/) teams *([Jan Odvarko](http://www.softwareishard.com/blog/about/) together with [Steve Souders](http://stevesouders.com/) and [Simon Perkins](http://www.httpwatch.com/company/))* as an open, portable JSON file format based on the HttpWatch XML file export. It is now supported by many browsers and HTTP sniffing / monitoring tools making it easier to exchange HTTP log files and to export collected data. it has since been adopted by all main HTTP tracking tools.

### Contributing

The content of this document are copied from various sources, Starting with the complete list by [Jan Odvarko](http://www.softwareishard.com/blog/har-adopters/) with updates for broken links and deleted tools. This list is available as an open-source project on Github, allowing anybody to contribute *(via [Pull Requests](https://github.com/ahmadnassri/har-resources/pulls))* to expand the content, and keep the list fresh.

## The List

## Browser Support

- [Google Chrome](http://blog.chromium.org/2011/02/chrome-developer-tools-back-to-basics.html)  
  You can export data from the Network panel into HAR format.

- [Internet Explorer](http://blogs.msdn.com/ie/archive/2010/04/22/ie9-developer-tools-network-tab.aspx)  
  The developer tools for IE9 include a Network tab that gives developers insight into what resources a web page is using. Captured data can be saved into an XML file (XML version of HAR).

- [DebugBar](http://debugbar.com/)  
  An Internet Explorer plug-in with support to view HTTP/S request to check cookies, GET and POST parameters, view server info. All can be exported into a HAR file.

## Applications

- [HAR Viewer](http://www.softwareishard.com/har/viewer/)  
  HAR Viewer is a web application that allows visualizing HTTP Archive logs (HARs). [Open Source](https://github.com/janodvarko/harviewer).

- [YSlow Command Line](http://yslow.org/command-line-har/)  
  YSlow for Command Line runs on Node.JS and requires a HAR file as input source in order to analyze page performance. It is currently available as a NPM package for installation.

- [Firebug/NetExport](http://www.softwareishard.com/blog/netexport/)  
  Firebug extension that allows exporting all collected and computed data from the Net panel. Of course, created log is based on HAR. The extension can be automated and integrated with systems for page load performance analysis.

- [HttpWatch](http://www.httpwatch.com/)  
  HTTP viewer and debugger that integrates with IE and Firefox to provide seamless HTTP and HTTPS monitoring without leaving the browser window. Collected data can be saved into a HAR based file.

- [Fiddler](http://www.telerik.com/fiddler)  
  Web Debugging Proxy which logs all HTTP(S) traffic between your computer and the Internet.

- [chromeHAR](http://ericduran.github.io/chromeHAR/)
  HAR viewer that mimics (or at least tries really hard to) Chromes network tab, [Open Source](https://github.com/ericduran/chromeHAR)

- [PhantomJS + Network Monitoring](http://phantomjs.org/network-monitoring.html)
  Inspect network traffic with PhantomJS and use [netsniff.js](https://github.com/ariya/phantomjs/blob/master/examples/netsniff.js) to get HAR output.

- [dynaTrace](https://community.compuwareapm.com/community/display/AJAX/Dynatrace+AJAX+Edition+Community+Home)  
  dynaTrace Ajax Edtion supports exporting captured Network Traffic in the HAR format.

- [pcap2har](https://github.com/andrewf/pcap2har) *[BSD License]*  
  A convertor from .pcap network capture files to HTTP Archive files.

- [Subgraph Vega](https://github.com/consiliens/harv/)  
  HAR exporter for Subgraph Vega.

- [Charles](http://www.charlesproxy.com/)  
  HTTP proxy / HTTP monitor / Reverse Proxy that enables a developer to view all of the HTTP and SSL / HTTPS traffic between their machine and the Internet. This includes requests, responses and the HTTP headers (which contain the cookies and caching information). Supporting HAR since Charles 3.6

- [HARLog](http://www.imagossoftware.com/harlog/)  
  Utility to take the HAR output and create a log format that can be imported into Excel or some other charting tool. HarLog can also generate a "pivot table" style report summarizing data from a collection of HAR files. This is useful if you wish to get average page performance over time and or you would like to baseline the performance of a site under development across versions.

- [HAR Storage](https://github.com/pavel-paulau/harstorage)  
  HAR Storage is free and open source repository for automated client-side performance testing. Core features: measurements over time, detailed stats, aggregation and comparison of test results, chart and table exporting, content breakdowns, embedded HAR Viewer, integration with Page Speed, cross-platform, cross-browser.

- [har2gnuplot](https://github.com/fh-salzburg/har2gnuplot)  
  Convert a HAR file into a gnuplot file, so you can use your network-dumps in a paper. Just copy your har-file into the main directory and run make. gnu-files and png-files will be created.

- [MIHTool](http://www.mihtool.com/)  
  Helps Front-End Engineers to debug and optimize their webpages on iPad and iPhone.

- [har-tools](https://github.com/outersky/har-tools)  
  Extract files from HAR file. Domain name and all fold info are kept.

- [Netsparker](https://www.netsparker.com/)  
  False-Positive Free Web Application Security Scanner. Use Netsparker to automatically find vulnerabilities and security flaws in websites, web applications. Netsparker is available as Desktop Software Application and as Online Web Security Scanning Service.

- [HTTP Archive Reader](http://www.brothersoft.com/http-archive-reader-350659.html)  
  Allows to read files exported from Firebug Net Panel

- [BenchLab](http://benchlab.cs.umass.edu/)
  A research project developed by the Laboratory of Advanced System Software at the University of Massachusetts Amherst. The source code and software distributions can be found on the [SourceForge Project Page](http://sourceforge.net/projects/benchlab/)

### Services

- [HTTP Archive](http://httparchive.org/)  
  The HTTP Archive provides information about website performance such as # of HTTP requests, use of gzip, and amount of JavaScript. This information is recorded over time revealing trends in how the Internet is performing.

- [ShowSlow](http://www.showslow.org/HAR)  
  Supports HAR beacon that can be used either manually or with a simple script that posts HAR file as a POST body.

- [WebPagetest](http://www.webpagetest.org/)  
  Allows you to provide the URL of a webpage to be tested. Results can be also exported to HAR.

- [REDbot](http://redbot.org/)  
  RED can create HAR files as output, containing both timings and its own analysis of the responses, as HAR extensions.

- [CrossBrowserTesting](http://crossbrowsertesting.com/)  
  Allows to test websites live via browser and remote VNC sessions. Network activity is recorded during live tests and available as HAR logs.

- [HAR to PageSpeed Online](http://stevesouders.com/flint/)  
  Online tool that utilizes HAR to PageSpeed *([see Applications](#applications))* and provides a preview of a HAR file.

- [GTmetrix](http://gtmetrix.com/)  
  Helps you develop a faster, more efficient, and all-around improved website experience for your users. Integrates Page Speed, YSlow, HAR Viewer.

- [Appvance PerformanceCloud](http://appvance.com/products/)  
  APC2 imports and runs existing scripts such as Selenium, Visual Basic, HTTP Archive (HAR), Perl, Groovy, Selenium RC, .NET, C#, PHP, Jruby, SoapUI, JMeter, Sahi, JUnit, Jython and others.

- [Neustar](https://www.neustar.biz/services/web-performance/load-testing)  
  Provides FREE Website Monitoring and Load Testing.

- [Catchpoint](http://www.catchpoint.com/)  
  Provides application performance monitoring to gauge user performance and pinpoint user problems

- [Check My Website](http://www.checkmy.ws/)  
  Service to remotely monitor websites availability and performance every minute from various places around the world. It uses HAR to give better insights into performance bottlenecks.

- [LoadStorm](http://loadstorm.com/)  
  The easy and cost effective load testing tool for web and mobile applications.

- [HTTP Archive Crawler](https://github.com/eddiejaoude/http-archive-crawler)
  A web application to allow you to crawl your URL & send it to HTTP Archive, which in turns is powered by Web Page Test

### Libraries

#### Java
  - [Java HarLib](https://sites.google.com/site/frogthinkerorg/projects/harlib) *[Apache v2 License]*  
    Read/write HAR files from Java, Database mapping of HAR objects into any databases through JDBC

#### Perl
  - [Archive::Har](http://search.cpan.org/~ddick/Archive-Har-0.05/) *[Perl 5 License (Artistic 1 & GPL 1)]*  
    Provides an interface to HTTP Archive (HAR) files

#### Ruby
  - [HAR::Archive](https://github.com/jarib/har) *[BSD 2-Clause License]*  

  - [http_archive](https://github.com/alihuber/http_archive) *[MIT License]*  
    Library to interact with HTTP Archive (.har) files  

#### Objective-C
  - [AFHARchiver](https://github.com/mutualmobile/AFHARchiver) *[MIT License]*  
    An AFNetworking extension to automatically generate HTTP Archive files of all of your network requests!

#### .NET
  - [http-archive-net](https://github.com/automatonic/http-archive-net) *[MIT License]*  
    .Net types for HTTP Archive (HAR) specification

#### PHP
  - [https://github.com/jmfontaine/php-http-archive](PHP library for manipulating HTTP Archives (Har)) *[BSD 3-Clause License]*  
    Library for manipulating HTTP archives

#### JavaScript
  - [HTTPArchive.js](https://github.com/codeinchaos/httparchive.js) *[MIT License]*  
    JavaScript library to manipulate HTTP Archive 1.2 JSON objects. You can install with Bower or NPM.

### Groups / Mailing Lists / Chat

- [**HTTP Archive Specification Google Group**](http://groups.google.com/group/http-archive-specification) *official*  
  Mailing list & forum for Web developers interested in the HTTP Archive file format.

- [HTTP Archive Google Group](http://groups.google.com/group/httparchive)  
  Official mailing list for [HTTPArchive.org](http://httparchive.org/)

## Videos

- [Make The Web Fast - The HAR Show: Capturing and Analyzing performance data with HTTP Archive format](https://www.youtube.com/watch/?v=FmsLJHikRf8)  
  > Need a flexible format to record, export, and analyze network performance data? Well, that's exactly what the HTTP Archive format (HAR) is designed to do! Even better, did you know that Chrome DevTools supports it? In this episode we'll take a deep dive into the format (as you'll see, its very simple), and explore the many different ways it can help you capture and analyze your sites performance.

  > Join +Ilya Grigorik and +Peter Lubbers to find out how to capture HAR network traces in Chrome, visualize the data via an online tool, share the reports with your clients and coworkers, automate the logging and capture of HAR data for your build scripts, and even adapt it to server-side analysis use cases! Yes, a rapid fire session of awesome demos - see you there.

## Articles / Blogs

- [HTTP Archive Specification: Firebug and HttpWatch](http://www.stevesouders.com/blog/2009/10/19/http-archive-specification-firebug-and-httpwatch/)  
  > By **Steve Souders** October 19, 2009

- [Web Performance Power Tool: HTTP Archive (HAR)](https://www.igvita.com/2012/08/28/web-performance-power-tool-http-archive-har/)  
  > By **Ilya Grigorik** on August 28, 2012

- [What is a HAR File and what do I use it for?](https://www.neustar.biz/blog/what-is-a-har-file)  
  > by **Alan Dyke** on August 29, 2012
