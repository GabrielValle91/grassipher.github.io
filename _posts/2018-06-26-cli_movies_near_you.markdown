---
layout: post
title:      "CLI Movies Near You!"
date:       2018-06-26 21:55:08 +0000
permalink:  cli_movies_near_you
---


It's been a couple weeks since I started the program and here I am at the first big project, creating my first CLI gem. I decided on making a movie scraper, partly because I never know what movies are playing near me and largely because I binge watched all 19 Marvel movies, starting with the origianl Ironman and ending with Avengers Infinity Wars, with my girlfriend during the last week in May.

When I started this project I was not really sure where to begin. I had an idea of what I wanted... the ability to get a list of Movies playing in theaters in my area and also to be able to get more information about the movies other than the title, but other than that I had no idea how  to start. Thankfully a link to Avi's Daily Deal walkthrough was provided because it set me on the right path to starting this project.

After getting the basic file structure setup, I still was not sure just what kind of information I should provide to the user of this potential CLI gem. Instead of trying to decide on everything at once, I decided to follow Avi's advice and start creating the CLI and work my way down to the multiple classes I would need, which would eventually include a Scraper to grab any and all the information I wanted.

I knew my CLI would need to be able to display a list of movies and then ask a user for a movie to provide more information on or give the option to quit the application... Finally I had a rough sketch of my first programming task for the project. After getting my CLI working I knew I need to start on my Movie class to store all the movie objects I was about to scrape information for.

After creating my Movie class and setting up an initialize method, I realized I still was not sure what attributes I wanted to provide to the user, which would be the attributes stored in each instance of my Movie objects, so I put my Movie class on hold and started creating my Scraper class so I could get an idea of what kind of information would be available to me. When I started scraping imdb I realized I only had access to limited information, a movie title and a url, but I had a feeling I could use this url to scrape even more information that was movie specific. This movie specific url gave me a lot more information about each movie, it's rating, a runtime, a synopsis,  genres and more. Now I had everything I needed to present a list of movies and details for specific movies, I just needed to program it all.

After lots of typing, I had an application that prompted a user for a zip code, returned a list of movies playing in theaters playing near that zip code and could also provide more detailed information about a movie in the listed.
