Tab Stack Safari Extension
==========================

This is a simple little Safari extension to mimic the 
[Tab Stack](https://chrome.google.com/webstore/detail/tab-stack/gfpdghcockbpiokcaaagmnneioeopnnb) 
Chrome extension. It's a simple workaround for "MRU" (most recently 
used) behavior for tabs. Instead of trying to override control+tab 
behavior, it simply moves the current tab to the left after a specified 
delay, so most recently used tabs are on the left of the tab list.

Setting
-------
* *Delay (ms)*: Sets the delay, in milliseconds, before a tab is moved. 
The default value is 1000.

Known Issues
------------
* When opening a new tab, movement of the new tab to the left will 
erase any text in the address bar, so any text typed immediately into 
the address bar after opening a new tab with command+tab before the tab 
is moved will be lost.
