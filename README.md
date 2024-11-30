# How Weather Influences My Music Habits

## Project Summary
This project is actually all about exploring a personal question (a random thought that brought up while chatting with my friend): does the weather affect the type of music I listen to? I'll be using my Spotify listening history and weather data from the days I listened to those songs to see if there’s a connection between the weather and the mood or energy of the music I enjoy.

The idea is to look for patterns that might reveal how things like a sunny day or gloomy weather influence the "vibe" of my music choices. It’s part psychology, part data science, and a little curiosity that was born from a random chat with my friend.

## What I’m Planning to Do

1. **Gather My Spotify Data**: I’ll download my listening history to get a list of songs, timestamps, and artists.
2. **Analyze the Songs**: Using Spotify’s API, I’ll fetch data about each song, like how “happy” or “energetic” it is (features like valence and energy will help me with this one but I should do more research on this I believe).
3. **Get Weather Data**: I’ll use basically any weather API to look up the weather for those timestamps—temperature, rainy or sunny, etc.
4. **Get location data**: I believe location data will somehow be crucial because even though my dataset will be in a specific area (for the most part), there might be weather data of wrong areas if I was in a different city etc. So this one might become crucial to eliminate outlier data points.
5. **Find Patterns**: By combining the two datasets, I’ll try and see if the weather affects my music habits or not.
6. **Visualize the Results**: I’ll make some cool graphs to show any trends, to visualize my results.

   
## **Tools I’ll Use** (at least the foreseeable ones)
- **Spotify API**: To get detailed information about the songs I’ve listened to.
- **Any weather API**: To grab historical weather data.
- **Python Libraries**: Pandas for dataset creations/manipulations, Matplotlib for visualizations, and Spotipy (at least I believe I will use this one for now) to work with the Spotify API.

## **What I’ll Deliver**
- A cleaned dataset combining Spotify and weather data.
- Insights into how my music habits change with the weather.
- Graphs and charts that make these patterns which will make the answer to the question obvious.
- A short report summarizing the key findings. (So basically updating this README file)

## **What’s Next?**
Once I’ve gathered all the data and done the analysis, I’ll share everything here, from the code to the visualizations. I’m curious to see if the weather really does influence my music habits or if my music taste really is just completely random.
