# Pitch-Description-Model
K-means clustering to label specific pitch based off movement profiles to give a full description of a pitchers arsenal including movement, release, and velocity

Data Dictionary
(Only FB’s, Sliders, Changeup’s, and Curveballs included)

Velocity: Broken into percentiles based off combined velo’s for individual pitches
-	Very Hard: 80-100 percentile
-	Hard: 60-80 percentile
-	Average: 40-60 percentile
-	Slow: 20-40 percentile
-	Very Slow: 0-20 percentile
Movement: Subcategories based off movement profiles
Fastballs:	
-	Ride: 18+ vb 
-	Cut-Ride: 18+ vb, 0-8 hb
-	Slight Sink: slightly more hb than vb
-	Slight Ride: slighty more vb than vb
-	Sink: 16+ hb with less vb
Sliders:
-	Gyro: Less than 14hb with low vb
-	Sweeper: more than 14hb
-	Cutter: low hb, with vb above 6
Changeups:
-	 Depth w/ fade: low vb with significant amount of hb
-	FB shape: average vb and hb, mimicks a FB
Curveballs:
-	Slider Type: positive vb with low hb
-	Small Curve: between 0 and -9vb with low hb
-	True Curve: more than -10 vb
-	Slurve: less than -5vb and large amount of hb
Releases: Based of release height
-	OverTheTop: greater than 6ft release height with a high side release
-	3/4: Between 5-6ft release height
-	Low ¾ | Sidearm: below 5ft release height
