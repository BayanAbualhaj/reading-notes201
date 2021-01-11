# Read 13

## The past, present and the future of the local storge for web applications

* Cookies were invented early in the web’s history:
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

* old web application didn't have a big storge 

* the develper knew that we need the following :
a lot of storage space and its on the client persists beyond a page refresh and isn’t transmitted to the server

### before HTML5
 * there was a **userData** allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
 * In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects.
 * In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.
 * in 2009, dojox.storage could auto-detect Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.

 ### HTML Storge (web storge)
 *  Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. the browser the latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer.

 #### using HTML5 storge :
 he data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string.

 #### changes to the HTML5:
 If you want to keep track programmatically of when the storage area changes, you can trap the storage event.

*** The storageevent object ***
![screenshot31](https://raw.githubusercontent.com/BayanAbualhaj/reading-notes201/main/pics/Screenshot%20(31).png)


