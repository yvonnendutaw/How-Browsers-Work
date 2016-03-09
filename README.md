# How-Browsers-Work
## Research on how browsers work
A **browser** is a group of structured codes that performs plenty of tasks to display a webpage on the screen. These codes are separated in to different components according to their tasks performed. The structure of a browser is shown in the below image. There are five major browsers;
* Chrome
* Firefox
* Safari
* Internet Explorer
* Opera

Browsers have a UI (_user interface_) that most commonly includes an address bar, back/forward button, and reload button. Sometimes developers refer to this as the “chrome” (little “c”, not Chrome by Google) of a browser. When you navigate to a URL in the address bar you are making a “request” for the content at that URL.That URL you typed into the address bar maps to an IP address. This is called a DNS lookup. DNS stands for “Domain Name System” and it maps numeric computer addresses to human readable names. All computers have an IP address. You can find out your personal computer’s IP address by typing “ifconfig” into your terminal window and looking for the number that is displayed in dot decimal format, such as 000.000.000.000. (_Note that 127.0.0.1 is used in your computer internally to refer to itself_).


For example, one IP address for Google is 74.125.134.102. You can enter 74.125.134.102 in the address bar and it will show the contents at www.google.com.


Once the browser has the IP address it sends an HTTP request to the web server at that address. HTTP stands for “Hypertext Transfer Protocol” and is used to facilitate requests from your client (the browser) and responses from the server. In our case the response is HTML from the web server at www.google.com.[Martha Girlder](http://skillcrush.com/2013/02/24/how-browsers-work/)

