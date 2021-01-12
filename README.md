# The Brandon Ramierez Social Platform

This new social media platform aims at providing users free speech. We are not in it for politics, but for fun! So enjoy 
designing this!

At the Brandon Ramierz Social Platform (SRSP for short), we aim to keep users engaged on their current conversations, but
be able to let users devalue conversations they find unimportant. It is not up to the platform to deem worthiness of speech,
but rather let the user filter their own context.

### User Personas

* The Poster
  
        He posts his ideas
  
* The Commenter

        He comments on the posts 
  
* The Guy No One Likes

        He is the guy when you see his post or comment, you're like "ugh, I dont want to see his stuff"

### The Kata's Goal

1. Design a system that notifies either the Poster or the Commenter after either one publishes to a common thread. 
 The notifications should be ordered such that the most active conversation is ranked 1st, the least active conversation is 
ranked last, and the Guy No One Likes, be it one or many, is grouped in a separate collection. Ranking activity should be 
   determined by them most interactions for a unique thread over a period of time, decaying in importance but never forgotten. 

2. If time permits, write a producer to feed the system and write a consumer to handle notifications. For the purpose of brevity, the consumer can simply 
write to stdout.