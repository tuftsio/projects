---
title: SoulSearcher
description: Analyze & visualize emotion in Facebook conversations using IBM Watson's AlchemyAPI
author: Max Ettelson, Ryan Havens, Ben Pall, Morgan Gellert, Eric Snyder, and Nika Korchuk-Wakulich.
email: maxwell.ettelson@tufts.edu
updated: 2016-11-07 11:45
status: Stable
tags: web, AlchemyAPI, emotions, IBM Watson
link: http://go.tufts.io/soulsearcher
---

Analyze & visualize emotion in Facebook conversations using IBM Watson's AlchemyAPI

## Where did the idea come from?
The idea for this project originally came about as a dating service idea.  I had been playing around with the concept of “Tinder with sentiment analysis” during my summer in New York.  I had sketched out some ideas and played around with IBM’s Watson APIs, but nothing came to fruition.

When I arrived at the hackathon, I saw it as a perfect opportunity to assemble a team and build this app.  The team I joined had originally planned to use sentiment analysis with videos.  Though it was a great idea, it lost its appeal once we realized that this exact technology already existed. We quickly shifted to the idea of using sentiment analysis to visualize conversations, and that’s how Soulsearcher was born.

## Who worked on it?
Our team consisted of myself, Ryan Havens, Ben Pall, Morgan Gellert, Eric Snyder, and Nika Korchuk-Wakulich.

## What knowledge was useful going in?
One thing that definitely helped us at the offset was understanding the limitations of the AlchemyAPI’s emotional analysis.  We knew that it was limited to the five primary emotions, and although it wasn’t accurate for single messages, but could usually parse a larger chunk of a conversation with greater accuracy.

This is what led us to our idea of Faces.  Using icons to represent each emotions, we enabled the user to find the most emotional moments in their conversations, which ended up being the most impressive feature of the project.

## What difficulties did the team face?
The primary challenge of the project was coming to grips with Facebook Graph’s limited functionality.  In order to obtain a user’s facebook messages, we were forced to use a soon-to-be deprecated endpoint in the Graph API, which was limited to 25 conversations per request.

To make things worse, we could only obtain the messages by having user directly give us their API keys.  For obvious reasons, this is not something that could be expected for the expected user of the app, but we made do for the Hackathon.

## Do you plan to keep working on it?
Our team plans to continue to work on this project, but we will definitely be shifting away from Facebook in the near future.  The next step is most likely to build our own messaging app, but there are a remarkable number of applications for this technology, including mental health and even dating apps like I had originally planned.  Who knows where this will take us, but surely this is not the end.
