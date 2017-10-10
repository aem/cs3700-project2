# cs3700-project2

This project gave us a fair number of challenges. There are lots of corner cases around activating/deactivating ports when building the MST. By breaking the problem down in to small manageable chunks instead of trying to tackle the whole algorithm at once, we were able to handle all of the BPDU processing much more easily.

Tweaking the timeouts to work exactly right also proved challenging. Too long and you miss packets entirely, too short and the run loop is running too quickly and you might end up with duplicate data or inefficient processing. 
