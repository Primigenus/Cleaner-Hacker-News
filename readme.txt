# Cleaner Hacker News

Cleaner Hacker News is a loose collection of CSS rules that you can use to improve the style of Hacker News (http://hackerne.ws or http://news.ycombinator.com).

Here's a screenshot: https://github.com/Primigenus/Cleaner-Hacker-News/blob/master/screenshot.png

The styles improve the legibility of the page by:

 * replacing Verdana with Lucida Grande on Mac OS X and with Segoe UI on Windows, and tweaking the font size; the new fonts are narrower than Verdana and easier to read
 * giving everything more room to breathe
 * removing the container color so there's no longer a border to the left of the list of submitted articles
 * reduces the contrast of each item's number and increases the contrast of links so the page becomes easier to scan

See screenshot.png for a preview of how it looks in Google Chrome.

Tested in Google Chrome v16 on Mac OS X.

To apply the styles in Google Chrome, install the Stylebot extension (https://chrome.google.com/webstore/detail/oiaejidbmkiecgbjeifoejpgmdaleoha), head to Hacker News, click the Stylebot button in the address bar (the one that says "css"), click Edit Css at the bottom, and then paste the contents of cleaner-hn.css.

To preview the styles you can paste this Javascript into your address bar:

javascript:(function(){var st = document.createElement('link');st.type = "text/css";st.href = "https://raw.github.com/Primigenus/Cleaner-Hacker-News/master/cleaner-hn.css";st.rel = "stylesheet";document.body.appendChild(st)})()

(thanks to jQueryisAwesome on HN)

Also available via Stylebot.me: http://stylebot.me/styles/1107

January 11, 2012
github.com/primigenus