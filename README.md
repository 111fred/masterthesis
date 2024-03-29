# Event detection in social media: An analysis of Tweets from the Turkish Gezi Park Uprising

This is a code repository for my masters thesis, in which I used Python and hierarchical clustering to detect crisis-related events in over 2 million Tweets from the Gezi Park Uprising (Turkey, summer of 2013). 

The goal was to find out to which degree events that took place during the first 13 days of the riots could be detected with an unsupervised learning method.

Events are defined as "something that happens in a specific time and place with consequences" (Allan, 2012).
Examples: 

* Thousands join a protest march across the Bosphorus Strait bridge, Istanbul, in the early morning of June 1, 2013
* Police storms potesters' barricades in the Dolmabahce area of Istanbul at 5 am on June 3, 2013

### Results:

Detection rate of events reported in the media: 
88 % of major events were detected (65 % with a clear match and 23 % with a weak match).

Rate of informative outputs regarding events: 
On two of 13 riot days over 85 % of the produced clusters contained highly relevant information about reported events; on 9 of 13 days this rate was above 50 %.

### Abstract:

This paper takes an explorative approach to determine to which degree events that occur within in the context of a political uprising can be detected from social media posts with computational methods. This is based on two pillars: A comparison of systems and approaches that have been developed in previous research of this topic, and the application of a selected hierarchical clustering method to the case of the Turkish Gezi Park Uprising. The combined learning from these two steps is critically assessed, showing that event detection in the context of a political uprising is feasible, and that such a system can be used for situational awareness. Clustering methods are the most suitable choice for the detection of events by previously unknown categories. Combined applications of clustering and classification are highly suitable for the practical purpose of detecting events by known categories, whereas graph-based methods offer a more versatile approach for specific applications. On the use-cases side, intelligence services and humanitarian agencies are found to have an interest in event detection methods, which holds ethical implications for the deployment of such a system.
