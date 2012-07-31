# Example of how to setup EHCache web page filter

Example projects of how to use the EHCache web page filter. More info about the EHCache web filter is found here: http://ehcache.org/documentation/modules/web-caching

## How to make a test run in Eclipse
<ol>
<li>Checkout the project</li>
<li>Make the project a Maven project ("Convert to Maven project")</li>
<li>Start the Tomcat using https://github.com/jsimone/webapp-runner#create-a-launch-configuration</li>
</ol>

## Example urls
The example has three different url:s setup:
http://localhost:8080/cached/ (cached)
http://localhost:8080/cached-sub/ (cached)
http://localhost:8080/uncached/ (not-cached)

The EHCache log is turned on for debug.



