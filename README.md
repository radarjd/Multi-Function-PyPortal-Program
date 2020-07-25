# Multi-Function-PyPortal-Program
A PyPortal application example that cycles through four functions: displaying current day/date/time, current weather, latest "shower thought" from the subreddit, and the value of the S&amp;P 500

There are a lot of examples of single-function applications available, such as weather, air quality, event count-down clock, and even how many astronauts are currently in space, along with their names. What I wanted to do was to have the device cycle through multiple applications. I ended up coding it to provideThe day, date, and time (inspired by how cruise ship's change out a piece of carpet every day in the elevators to tell you what day of the week it is),The current local weather,The latest "shower thought" post from the shower thoughts subreddit, and the current value and change from the previoius day for the S&P 500. (Since making this, the market data provider stopped provding index data in their free tier, so now use the SPY index-tracking ETF as a close surrogate.)

There's a main file (code.py) and then a separate module for parsing and formatting the data for each of the three functions. You'll need to edit the "secrets.py" file to provide your WIFI login information as well as sign up with the API providers and put your personal keys or ID in that file. Additional information is available on my blog at https://www.mcgurrin.info/robots/620/
