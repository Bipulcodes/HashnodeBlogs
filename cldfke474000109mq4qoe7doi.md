# Web Server and how it works.

**Complete understanding of a web server and how can you use it and how it used to work in the previous era of the internet.**

**Web server:** In layman\*\*,\*\* the language web server is a computer that stores, processes and delivers files(It could be any kind of file like image, audio, video etc.) Web servers consist of both Hardware and Software that is used to give response to the internet user who requested to fetch some data(it could be any kind of data).

This is not the only part that you should consider there is a server **Software section** of the web server where things are happening this part is control the flow of the webpage, How the user can access the webpage how much will be the loading time for the webpage etc. Theoretically, this is an HTTP server. Now you might be thinking what is HTTP this is not other than some protocols uses by browsers to view your webpages created by the developer.

**The second thing is how can we access this?**

we can access this HTTP server by using the domain name more specifically an IP address.

**Do you know what is the most famous HTTP server?** **\-&gt;** *Apache2*

though there are more web server ***Apache Tomcat ,*** ***Nginx*** *etc.* But Apache2 is the oldest one and according to the data, 67% of the internet is using **apache2** webserver.

There are some popular hosting websites named GoDaddy, Bluehost etc. They used to give a <mark>particular folder</mark> where you dump your HTML, CSS file and this file will be served to everybody to view your website. As I already said to serve the internet you need a server so now you need this apache2. This is giving you a particular folder in the path name of **(/var/html/www)** in this folder you are basically dumping the files and this is going to map to a particular address(IP) this Hosting website is giving a fancy name to that IP that is the domain name for that you are paying them. Ip addresses are difficult to remember which is why this domain name is not only this there are many more reasons.

**Now you hosted the webpage, right? How can you control the website and how will you monitor analytics, and web traffics (How many users are visiting your page on a daily, monthly or yearly basis)?** Here comes the cPannel which provides you a GUI. Where you can perform actions from a user-friendly dashboard instead of running linux complex commands. This is like your system all the things that we are doing , also can be done by CMD but we are using gui instead of it like that.