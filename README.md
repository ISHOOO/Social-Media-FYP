# Social Media FYP
Consists of 2 dataset files:<br>
**SocialMediaUsers.csv**: contains informations about users' interests, country, gender and username. <br>
**influencers.csv**: contains information about content-creators' category of content, followers count, Engagement rate, Country and username. <br><br>
Recommends Content creators to users by calculating a recommendation score based on descending order of followers and user preferences using Cosine Similarity and Z-Score Normalization.
Converts location data of users and Influencers to latitude and Longitude using OpenCage API and calculates distance between each and every user in contrast with Influencer to use them as weights. 
