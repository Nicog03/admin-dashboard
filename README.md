# Admin Dashboard

![Example picture](https://github.com/Nicog03/admin-dashboard/blob/main/readme-content/layout.png)

## Index

- [About the Project](#about)
- [Technologies Used](#technologies)
- [Features](#features)
  - [Resposiveness](#responsiveness)
- [Possible Improvements](#improvements)
  - [Responsiveness improvements](#improvement_resposiveness)
  - [Fix on chrome browser](#improvement_chromefix)

## <a id="about"></a> About the project

This project is a simple recreation of the layout of a simlpe admin dashboard. It was made with the main intent of practicing the usage of CSS (mainly the usage of the grid layout) to create an application with a responsive content display.

### Try it out [Here!](https://nicog03.github.io/admin-dashboard/)

## <a id="technologies"></a> Technologies used

- **HTML**
- **CSS**
  - Grid layout
  - Pseudo-classes selectors
  - Pseudo-elements selectors

## Features {#features}

### <a id="responsiveness"></a> Responsiveness

![Responsiveness GIF example](https://github.com/Nicog03/admin-dashboard/blob/main/readme-content/resp.gif)

The interesting thing about the 'responsiveness' on this page is that i didn't use the tag `@media` to create it. It basically works only through the use of the grid layout usage. But the downside is: as i only use the grid layout on the main content of the page, the other contents won't adapt to a smaller screen. So there is still a lot to improve on that aspect.

## <a id="improvements"></a> Possible Improvements

As mentioned before, this is a pretty simple project, so it's a little bit hard to think on some improvements. BUT i do have some things in mind, mostly regarding browser compatibility, or even improvements to the responsiveness.

### <a id="improvement_resposivenessresponsiveness"></a> Responsiveness

Let's be honest: the responsiveness is here, but it's not exactly THAT good, so theres a lot to improve in that aspect. I believe that the main objective here is to **make this page cross-device responsive, so that we can access it from any device, being it a mobile phone or a desktop.**

### <a id="improvement_chromefix"></a> Fix the site on chrome browser

| ![showcase of the header on the chrome browser](https://github.com/Nicog03/admin-dashboard/blob/main/readme-content/header-chrome.png) |
| :------------------------------------------------------------------------------------------------------------------------------------: |
|                                    _screenshot of the header being rendered in the chrome browser_                                     |

As you can see, the display of the header is a little bit off, specificaly on the chrome browser. This is mainly because chrome renders the `backdrop-filter` property different that firefox does. What ends up happening is what we are able seing in the above screenshot: some sections of the header seems to have no background at all.

_- So whats the solution?_

Well, what i still plan to do (in a hopefully not far future) is **implementing a method, of checking in which browser the page is being rendered on**, and depending on the result, the background of those 'defective' sections is changed for an appropriate one.
