# YouTube video search

The purpose of this project is to develop a code that would help users search videos on YouTube. The core of this is the function called youtube_video_search(). This function generates a method that will help search videos on YouTube by several parameters such as a search term, a language code, a region code and the desired number of results. 

The values of the above mentioned parameters are obtained via input functions. In the input langauge and region code fields write 'list' to get the list of all the language or region codes.

The list of language codes is obtained using BeatifulSoup library to extract the data from Wikipedia. The list of region codes is obtained via the YouTube funnction youtube.i18nRegions().  
