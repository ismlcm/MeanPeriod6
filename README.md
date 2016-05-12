# Period-6

 Explain the concept of Hybrid Mobile App Development:

The concept about hybrid apps are that you are able to create a mobile application via webtechnologies and then use Cordova/PhoneGap as a layer to intepret the web code to native code. Thereby making app creation for multiple platforms easy. Explain the Pros & Cons of using Hybrid Mobile App Development compared to Native App Development Hybrid apps are very easy to create and only demands a programmer with knowledge to webtechnologies. You only need one code base to compile for android, ios etc. The disadvantage is speed and some native specific functions to be unavailable.

 Explain about the "building blocks" involved in an ionic Hybrid Application:
Pro's are:

Multi platform, you don't need to be profficient in multiple languages to create and app for both Android and iOS
Deployed in app store, compared to a HTML5 app
Unlimited possibilities because its created with HTML
Con's are:

Loading might be slow compared to Native apps
They don't feel as great as native apps

 Explain and demonstrate ways to debug Hybrid Mobile Applications Running on a real device:

 Angular controls the logic of the presentation layer. 
 The app is build and styled by HTML and CSS
 Cordova is used to access the devices native components.

 Explain when and why CORS is a problem for Hybrid Mobile Applications:

Cross Origin Ressource Sharing (CORS) is a safety feature in modern
browsers that does not allow the website to make an HTTP request to a url that 
is not the same as the root of the site. This can cause problems in Hybrid 
App development when trying to use an API like Google Maps that has a 
different url than the app has when developing it.
There is different ways to solve this problem.
one solution is to make a Access-Control-Allow-Origin * to allow request from all locations
Another is to specify the request to go through a proxy and make the proxy 
talk to the backend instead of you directly. 

 Explain how and why it is possible for a Hybrid Application to access native phone devices like location, calendar etc.:
  
Screens are small, apps are big, and life as we know it is on its head again. In a world that's increasingly social and open, mobile apps play a vital role, and have changed the focus from what's on the Web, to the apps on our mobile device. Mobile apps are no longer an option, they're an imperative. You need a mobile app, but where do you start? There are many factors that play a part in your mobile strategy, such as your team’s development skills, required device functionality, the importance of security, offline capability, interoperability, etc., that must be taken into account. In the end, it’s not just a question of what your app will do, but how you’ll get it there.
Like Goldilocks, you may have to try a couple beds that are too soft or too hard, before you find the one that’s just right. And sometimes there’s just no perfect choice. Each development scenario has its pros and cons, and those might in be inline, or at odds, with your means. Unlike Goldilocks, there are no bears to contend with, and it’s our intent that this article keeps you from burning your lips on hot porridge (well, figuratively).
While this article addresses mobile app development in general, it is specifically targeted at developers looking to create mobile applications that interact with Salesforce.com, Force.com, or Database.com. Currently, the Salesforce Mobile SDK supports building three types of apps:
Native apps are specific to a given mobile platform (iOS or Android) using the development tools and language that the respective platform supports (e.g., Xcode and Objective-C with iOS, Eclipse and Java with Android). Native apps look and perform the best.
HTML5 apps use standard web technologies—typically HTML5, JavaScript and CSS. This write-once-run-anywhere approach to mobile development creates cross-platform mobile applications that work on multiple devices. While developers can create sophisticated apps with HTML5 and JavaScript alone, some vital limitations remain at the time of this writing, specifically session management, secure offline storage, and access to native device functionality (camera, calendar, geolocation, etc.)
Hybrid apps make it possible to embed HTML5 apps inside a thin native container, combining the best (and worst) elements of native and HTML5 apps.


Hybrid development combines the best (or worst) of both the native and HTML5 worlds. We define hybrid as a web app, primarily built using HTML5 and JavaScript, that is then wrapped inside a thin native container that provides access to native platform features. PhoneGap is an example of the most popular container for creating hybrid mobile apps.
For the most part, hybrid apps provide the best of both worlds. Existing web developers that have become gurus at optimizing JavaScript, pushing CSS to create beautiful layouts, and writing compliant HTML code that works on any platform can now create sophisticated mobile applications that don’t sacrifice the cool native capabilities. In certain circumstances, native developers can write plugins for tasks like image processing, but in cases like this, the devil is in the details.
On iOS, the embedded web browser or the UIWebView is not identical to the Safari browser. While the differences are minor, they can cause debugging headaches. That’s why it pays off to invest in popular frameworks that have addressed all of the limitations.
Hybrid.png
You know that native apps are installed on the device, while HTML5 apps reside on a Web server, so you might be wondering if hybrid apps store their files on the device or on a server? Yes. In fact there are two ways to implement a hybrid app.
Local - You can package HTML and JavaScript code inside the mobile application binary, in a manner similar to the structure of a native application. In this scenario you use REST APIs to move data back and forth between the device and the cloud.
Server - Alternatively you can implement the full web application from the server (with optional caching for better performance), simply using the container as a thin shell over the UIWebview.
Netflix has a really cool app that uses the same code base for running the UI on all devices: tablets, phones, smart TVs, DVD players, refrigerators, and cars. While most people have no idea, nor care, how the app is implemented, you’ll be interested to know they can change the interface on the fly or conduct A/B testing to determine the optimal user interactions. The guts of decoding and streaming videos are delegated to the native layer for best performance, so it’s a fast, seemingly native app, that really does provide the best of both worlds.
 
