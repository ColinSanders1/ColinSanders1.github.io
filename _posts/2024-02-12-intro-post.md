---
layout: post
title: "Intro Post"
author: "Colin Sanders"
date: "2024-02-29"
output: html_document
tag: NCAA
---
  The beginning of the 2024 college baseball season marks the start of another 4 month marathon culminating in Omaha in June. Now that we are headed into the third weekend of the season, I want to share a model that I have been working on for the past few months. It's a power ratings model that evaluates teams using a number of offensive and defensive statistics. It is powered by a random forest machine learning model whose goal is to accurately assess the strength of college baseball teams over the course of the whole season, in an effort to predict who will lift the national championship trophy at the end of the year and to compare teams across different seasons. 

  This model has been set up to be interpreted in two ways. The first is as a win projection tool. The formula the model uses will produce a number of expected wins based on their performance throughout the year. I prefer to use it as a relative strength tool, where the projected wins represent each teams relative strength compared to the others. It's important to note that these are not rankings like those provided by Baseball America, Perfect Game, or D1 Baseball. The model does not account for wins and losses, so if, for example, Georgia swept Georgia Tech this weekend, there is no guarantee that Georgia will have a higher rating than Tech in the next week's rankings. 

  Let's take a look at the top 25 before the start of games on March 1st: 
 
  <iframe src="file:///C:/Users/colin/OneDrive/Documents/top_25_teams.html" width="100%" height="500"></iframe>

  As you can see, there are some unexpected names at the top of the ratings, with Creighton as the strongest team so far this year and the consensus preseason #1 team Wake Forest not even in the top 12. These ratings will continue to adjust over the course of the year, and will only get better with an increased sample size for each team, but it's interesting to get an early look into how teams are perceived vs how they are performing to start the year. 


I also plan on using it to provide predictions and previews on the big series throughout the year. This weekend, I want to highlight two match ups that should be extremely entertaining. 

### Clean Old-Fashioned Hate

Georgia plays Georgia Tech in a home-road-neutral series in a match up of 2 extremely high powered offenses, led by Georgia's Charlie Condon and Tech's Drew Burress. According to the model, Georgia Tech has a slight advantage in the match up, and it gives them a 53% chance to win the series. Game one will be in Atlanta at Russ Chandler Stadium, Game two in Athens at Foley Field, with the rubber match at Coolray Field in Lawrencville. 

### Battle for the Palmetto State

Clemson plays South Carolina in another in-state matchup between two very high quality teams. Talented draft prospect Cam Cannarella leads the Tigers against Ethan Petry and the Gamecocks in what is always a hotly contested series. South Carolina should have the edge in this one, and the model gives them a 58% chance of winning the series. The gamecocks will host game one at Founder's park, game two will be at Segra Park in Columbia, and Clemson will host the final game of the series at Doug Kingsmore stadium. 
