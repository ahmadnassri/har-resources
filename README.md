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

- [HAR Viewer](http://www.softwareishard.com/blog/har-viewer/)  
  Web application based on HTML/JS/CSS that can be used for visualizing HTTP Archive files. This project is intended as an extensible tool for preview and validation of HAR logs that can be also embedded in third party systems.

- [Firebug/NetExport](http://www.softwareishard.com/blog/netexport/)  
  Firebug extension that allows exporting all collected and computed data from the Net panel. Of course, created log is based on HAR. The extension can be automated and integrated with systems for page load performance analysis.

- [HttpWatch](http://www.httpwatch.com/)  
  HTTP viewer and debugger that integrates with IE and Firefox to provide seamless HTTP and HTTPS monitoring without leaving the browser window. Collected data can be saved into a HAR based file.

- [HAR to PageSpeed](http://code.google.com/p/page-speed/wiki/DownloadPageSpeed#Page_Speed_Command-Line_Utilities)  
  Command line utility that allows to get PageSpeed output from a HAR file.

- [GTmetrix](http://gtmetrix.com/)  
  Helps you develop a faster, more efficient, and all-around improved website experience for your users. Integrates Page Speed, YSlow, HAR Viewer.

- [Fiddler](http://www.fiddler2.com/fiddler2/)  
  Web Debugging Proxy which logs all HTTP(S) traffic between your computer and the Internet.

- [Catchpoint](http://www.catchpoint.com/)  
  Provides application performance monitoring to gauge user performance and pinpoint user problems

- [dynaTrace](http://blog.dynatrace.com/2010/11/17/dynatrace-ajax-edition-2-0-is-ready-for-download/)  
  dynaTrace Ajax Edtion 2.0 supports exporting captured Network Traffic in the HAR format.


- [PushToTest TestMaker](http://www.pushtotest.com/index.php?option=com_content&view=article&id=183)  
  TestMaker is an Open Source Test (OST) tool that repurposes HAR files as functional tests (regression test, smoke test, integration test,) load and performance tests, and production monitors.

- [REDbot](http://redbot.org/)  
  RED can create HAR files as output, containing both timings and its own analysis of the responses, as HAR extensions.

- [JMeter to HAR converter](http://labs.watchmouse.com/2010/08/from-jmeter-to-har/)  
  Converts Apache JMeter output to HAR.

- [Browser Mob](http://browsermob.com/performance-testing)  
  Provides FREE Website Monitoring and Load Testing.

- [Blaze.io](http://www.blaze.io/mobile/)  
  Blaze Mobile Performance Test uses real iPhone and Android agents to conduct a performance analysis of browsing your website on a mobile device.

- [3PMobile](http://www.3pmobile.com/)  
  Delivers real-time mobile data via the browser. It’s a Mobile browser that measures HTTP traffic performance and outputs the data in a HAR format. Check out an example.

- [CrossBrowserTesting](http://crossbrowsertesting.com/)  
  Allows to test websites live via browser and remote VNC sessions. Network activity is recorded during live tests and available as HAR logs.

- [Subgraph Vega](https://github.com/consiliens/harv/)  
  HAR exporter for Subgraph Vega.

- [Charles](http://www.charlesproxy.com/)  
  HTTP proxy / HTTP monitor / Reverse Proxy that enables a developer to view all of the HTTP and SSL / HTTPS traffic between their machine and the Internet. This includes requests, responses and the HTTP headers (which contain the cookies and caching information). Supporting HAR since Charles 3.6

- [HARLog](http://www.imagossoftware.com/harlog/)  
  Utility to take the HAR output and create a log format that can be imported into Excel or some other charting tool. HarLog can also generate a "pivot table" style report summarizing data from a collection of HAR files. This is useful if you wish to get average page performance over time and or you would like to baseline the performance of a site under development across versions.

- [HAR Storage](http://code.google.com/p/harstorage/)  
  HAR Storage is free and open source repository for automated client-side performance testing. Core features: measurements over time, detailed stats, aggregation and comparison of test results, chart and table exporting, content breakdowns, embedded [HAR Viewer](#har-viewer), integration with Page Speed, cross-platform, cross-browser.

- [har2gnuplot](https://github.com/fh-salzburg/har2gnuplot)  
  Convert a HAR file into a gnuplot file, so you can use your network-dumps in a paper. Just copy your har-file into the main directory and run make. gnu-files and png-files will be created.

- [Funomy](http://www.funomy.com/)  
  At Funomy we use HAR v1.2 to really store whole web pages. We have developed services that operate with HAR format in order to generate web performance analysis (WPO).

- [MIHTool 5.0](http://www.iunbug.com/mihtool)  
  Helps Front-End Engineers to debug and optimize their webpages on iPad and iPhone.

- [har-tools](https://github.com/outersky/har-tools)  
  Extract files from HAR file. Domain name and all fold info are kept.

- [Check My Website](http://www.checkmy.ws/)  
  Service to remotely monitor websites availability and performance every minute from various places around the world. It uses HAR to give better insights into performance bottlenecks.

- [OWASP ZAP](https://www.owasp.org/index.php/ZAP)  
  The Zed Attack Proxy (ZAP) project is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications. It is designed to be used by people with a wide range of security experience and as such is ideal for developers and functional testers who are new to penetration testing.

- [LoadStorm](http://loadstorm.com/)  
  The easy and cost effective load testing tool for web and mobile applications.

- [Netsparker](https://www.netsparker.com/)  
  False-Positive Free Web Application Security Scanner. Use Netsparker to automatically find vulnerabilities and security flaws in websites, web applications. Netsparker is available as Desktop Software Application and as Online Web Security Scanning Service.

### Services

- [HTTP Archive](http://httparchive.org/)  
  The HTTP Archive provides information about website performance such as # of HTTP requests, use of gzip, and amount of JavaScript. This information is recorded over time revealing trends in how the Internet is performing.

- [ShowSlow](http://www.showslow.org/HAR)  
  Supports HAR beacon that can be used either manually or with a simple script that posts HAR file as a POST body.

- [HTTP Archive Reader](http://www.brothersoft.com/http-archive-reader-download-350659.html)  
  Allows to read files exported from Firebug Net Panel

- [WebPagetest](http://www.webpagetest.org/)  
  Allows you to provide the URL of a webpage to be tested. Results can be also exported to HAR.

- [HAR to PageSpeed Online](http://stevesouders.com/flint/)  
  Online tool that utilizes [HAR2PS](#har-to-pagespeed) and provides a preview of a HAR file.

### Libraries

- [Java HarLib](http://www.frogthinker.org/projects/harlib)  
  Open source Java library for the HAR v1.2. Read/write HAR files from Java, Database mapping of HAR objects into any databases through JDBC, Open Source - Apache v2 license.

- [Archive::Har](http://search.cpan.org/~ddick/Archive-Har-0.05/)  
  Archive::Har is a Perl library that allows the user to interact with HAR files. It's an open source based on The Perl 5 License (Artistic 1 & GPL 1).

- [HTTPArchive.js](https://github.com/codeinchaos/httparchive.js)  
  JavaScript library to manipulate HTTP Archive 1.2 JSON objects. You can install with Bower or NPM. Licensed under the MIT license.

### Groups / Mailing Lists / Chat

- [**HTTP Archive Specification Google Group**](http://groups.google.com/group/http-archive-specification) *official*  
  Mailing list & forum for Web developers interested in the HTTP Archive file format.

- [HTTP Archive Google Group](http://groups.google.com/group/httparchive)  
  Official mailing list for [HTTPArchive.org](#http-archive)

## Videos

- [Make The Web Fast - The HAR Show: Capturing and Analyzing performance data with HTTP Archive format](https://www.youtube.com/watch/?v=FmsLJHikRf8)  
  > Need a flexible format to record, export, and analyze network performance data? Well, that's exactly what the HTTP Archive format (HAR) is designed to do! Even better, did you know that Chrome DevTools supports it? In this episode we'll take a deep dive into the format (as you'll see, its very simple), and explore the many different ways it can help you capture and analyze your sites performance.

  > Join +Ilya Grigorik and +Peter Lubbers to find out how to capture HAR network traces in Chrome, visualize the data via an online tool, share the reports with your clients and coworkers, automate the logging and capture of HAR data for your build scripts, and even adapt it to server-side analysis use cases! Yes, a rapid fire session of awesome demos - see you there.
