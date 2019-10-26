# Web Crawler (Python)

I located the demo code for this project at [https://medium.freecodecamp.org/how-to-build-a-url-crawler-to-map-a-website-using-python-6a287be1da11](https://medium.freecodecamp.org/how-to-build-a-url-crawler-to-map-a-website-using-python-6a287be1da11). I ran into issues getting the code to run; I resolved the issues with the article located at [https://www.google.com/search?q=python+get+urls+deque&oq=python+get+urls+deque&aqs=chrome..69i57j33.7249j0j7&sourceid=chrome&ie=UTF-8](https://www.google.com/search?q=python+get+urls+deque&oq=python+get+urls+deque&aqs=chrome..69i57j33.7249j0j7&sourceid=chrome&ie=UTF-8).

This basic web crawler will iterate a single link and retrieve the links contained within the page.

To run in Windows 10 and select the Python version to use (if multiple are installed), run from the command line ```py -2 web-crawler.py``` where the numbered argument is the Python version.

There are several issues to resolve:

1. Update code to iterate recursively through all links
1. Update code to handle all characters that could be in the URL