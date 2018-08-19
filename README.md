
# Mobile Web Specialist Nanodegree Scholarship
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, I incrementally converted a static webpage to a mobile-ready web application. In **Stage One**, I took a static design that lacks accessibility and converted the design to be responsive on different sized displays and accessible for screen reader use. I've  also added a service worker to begin the process of creating a seamless offline experience for my users.

## Evaluation points

### Responsive Design
* All content is responsive and displays on a range of display sizes.
  Content should make use of available screen real estate and should display correctly at all screen sizes.
  An image's associated title and text renders next to the image in all viewport sizes.

* Images in the site are sized appropriate to the viewport and do not crowd or overlap other elements in the browser, regardless of viewport size.

* On the main page, restaurants and images are displayed in all viewports. The detail page includes a map, hours and reviews in all viewports.

### Accessibility
* All content-related images include appropriate alternate text that clearly describes the content of the image.

* Focus is appropriately managed allowing users to noticeably tab through each of the important elements of the page. Modal or interstitial windows appropriately lock focus.

* Elements on the page use the appropriate semantic elements. For those elements in which a semantic element is not available, appropriate ARIA roles are defined.

### Offline Availability
* When available in the browser, the site uses a service worker to cache responses to requests for site assets. Visited pages are rendered when there is no network access.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code.
For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality. 

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Google Maps API Key:

This repository uses [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key). I have replaced `<your YOUR_GOOGLE_MAPS_API_KEY API KEY HERE>` with an API Key from [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key).

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 



