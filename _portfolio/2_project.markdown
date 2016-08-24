---
layout: post
title: Trext Trip Planner 
description: making travel easy
img: /img/trext1.jpg
---

For our databases course final project back at Duke University, three other computer science students and myself built a web application we called Trext (a play on the phrase ‘next trip’) that helps travelers plan their travel itineraries better, faster and more conveniently. We used AngularJS and Bootstrap for our front end frameworks, with a Python Flask server and PostgreSQL database on the backend. 

There are three main pages in the web app: plan, trips and explore. 

<br>
"Plan" - The process of finding one's ideal trip is the following: the user can specify destinations of his desire, and/or general location(s) along with general areas of interest and activities. For the lazy or adventurous traveler, we can also random these parameters for this search. 
<div class="vid_row">
 <iframe src="http://screencast.com/t/NzXaakQJGrvU" width="1000" height="700" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

<div class="col three caption">
Our algorithm uses the Yelp API to help us propose an itinerary for user. The user can then refine this itinerary by fitting the best routes between the attractions, deleting undesired attractions, or re-search using different parameters.
</div>
<br>
<br>
<br>
"Trips" - Once a registered user is pleased with a proposed itinerary, he can save the itinerary trip into his list of trips, with a optional travel date. He can also share an itinerary with his friends and family via our email sharing feature.
<div class="vid_row">
  <iframe src="http://screencast.com/t/FQgqwZtEu7N" width="1000" height="700" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

<div class="col three caption">

</div>


<div class="vid_row">
  <iframe src="http://screencast.com/t/WRlNvjKZmf" width="1000" height="700" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>
<div class="col three caption">

</div>
"Explore" - This is a views page that contains the Editor's Picks -- our favorite themed trips for popular destinations. In the future, we can also implement views of popular user-created trips.

<br>

More screenshare videos:


<a href="http://screencast.com/t/UOqUCgjqAq">User authentication</a> - New users will be automatically logged in upon successful registration. Logged in users will remain authenticated during their session and have the opportunity to log out.

<a href="http://screencast.com/t/NzXaakQJGrvU">Trip Planning, Part A</a> - Playing around with search parameters and generating an itinerary.

<a href="http://screencast.com/t/FQgqwZtEu7N">Trip Planning, Saving </a> - After setting the desired start and endpoints of a route, the user can now save this trip into his history.

<a href="http://screencast.com/t/WRlNvjKZmf">Trip Sharing via Email </a> - A trip planner can share his itinerary to a friend via email.

<a href="http://screencast.com/t/HMnymerX04">View Trips </a> - Authenticated users have a Trips tab that shows a history of all his planned trips. Note that this includes our newly added trip.

View the source code on <a href="https://github.com/catzhangy1/cs316_trext">GitHub</a>. 