# Glocalisation
MSc Thesis on evolvement of music diversity in the era of rising dominance of DSPs. It is based on a Big Data comparative content analysis of national music charts enriched with Spotify track metadata and their streaming performance. The research spans over 49 countries across the globe and covers the period between 2017 and mid-2020.

Interactive visualtiations are available through Tableau Public: https://public.tableau.com/app/profile/ruslan.pinskii/vizzes 

Full text of the research will become available later this month.

For questions and inquires: Ruslan.Pinskii@gmail.com

Dataset with chart data on 51 countries with Spotify track URI-s was retrieved from https://github.com/PabloBelloDelpon/Spotify_paper

This is a unique dataset that spans over 3,5 years between January 2017 and July 2020.

Note that Bulgaria and Nicaragua have a lot of missing values, hence could not be used for a comparative analysis

Feel free to use my code to make your own Spotify API requests. All the examples I've seen online so far lack extensive step-by-step explanation, so I had to write my own from scratch. I used "requests" library instead of the widely-praised Spotipy. For some reason Spotipy kept crashing whenever I tried to make a repeated API request despite me strictly following the Spotify official rate limit (https://developer.spotify.com/documentation/web-api/concepts/rate-limits)
