Tab Stack Safari Extension
==========================

This is a simple little Safari extension to mimic the 
[Tab Stack](https://chrome.google.com/webstore/detail/tab-stack/gfpdghcockbpiokcaaagmnneioeopnnb) 
Chrome extension. It's a simple workaround for "MRU" (most recently 
used) behavior for tabs. Instead of trying to override control+tab 
behavior, it simply moves the current tab to the left after a specified 
delay, so most recently used tabs are on the left of the tab list. The 
delay allows you to navigate through tabs (find a tab) without affecting 
the ordering.

Settings
--------
* **Delay (ms)**: Sets the delay, in milliseconds, before a tab is moved. 
Having a short delay allows you to navigate through tags quickly without 
affecting the ordering &ndash; e.g., to find a specific tab. 
The default value is 1000.

* **No delay for new tab**: When creating a new tab, move it immediately 
to the left. Since Safari clears the address bar when a tab is moved, this 
allows you to open a new tab with &#8984;T and start typing a URL or 
your search phrase without losing it when tab movement is delayed. 
Defaults to true.

Known Issues
------------
* When opening a new tab, movement of the new tab to the left will 
erase any text in the address bar, so any text typed immediately into 
the address bar after opening a new tab with &#8984;T before the tab 
is moved will be lost. Unfortunately, Safari extensions do not have 
access to manipulate the address bar, so there's no way to prevent the 
clearing of the address bar when the tab is moved. The *No delay for 
new tab* setting attempts to mitigate the problem by moving new tabs 
immediately (hopefully before you begin typing into the address bar).
workaround this problem
