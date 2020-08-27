#GET YT PLAYLIST TITLES AND URLS 

So, I had an assignment for my robotics class this summer (2020) which 
required us to categorize YouTube videos in a playlist by content using 
a categories she provided. Easy, right? Well, she wanted us to include 
the verbatim title and URL of every video in the playlist, which had 
over 60 videos.

I'm allergic to repetitive work and akin to automation. Plus, I'm a
programmer, right? I should be able to write a script to do the work
for me. So, that's what I did. 
------------------
This script fetches the URL and title of every video in playlist you 
specify within the script and returns a csv containing two columns of 
titles and URLs.

Open the ipynb in Jupyter Notebooks. You'll have to get an API key 
from Google if you don't have one. Edit "playlist_id" to the playlist
you want to fetch data from. Uncomment the first line of code in the 
2nd block to install the API client if you don't have it.

The csv named "_playlist" should appear in the same folder this script
is located in.
