# Streaming_Service_App_Reviews_Text_Analysis_ADS509

Authors:
Emina Belekanich 
Roberto Cancel
Martin Zagari

Project for ADS509 - Text Mining

Objective: Prospective Project to evaluate Classification and Topic Modeling performance on Apple App Store reviews for 5 popular streaming services.

Summary:

After scraping, cleaning and preparing our data, we attempted a classification with relatively good success (given the circumstances) with Naive Bayes with 74.6% accuracy. The most informative features from our Naive Bayes Model provided a great deal of insights including: Hulu reviews were primarily classified by containing words related to ads/commercials and given their poor performance, this is indicative of a customers' dislike for the quantity and/or content of ads. HBOMax was disproportionately classified with app issues (buggy, offline, streamig, glitchy, crashing) - this was very eye opening.

In selecting our optimal Topic Model, we found that the NMF with countvectorizer outperformed the NMF with tf-idf with more balanced and well separated topics. We also chose NMF w/ countvectorizer as the overall optimal Topic Model since LDA had significant overlap and LSA put most reviews into a single topic. This was not surpirsing since NMF is more appropriate for shorter documents (such as app reviews).

Additional insight gained: HBOMax identified as a second potential client with their 2.00 rating and similar issues identified.

Recommendations for Hulu:

    Negative customer reviews indicate that ads are an issue - When reviewing the Hulu (No Ads) service offerings, we found that extra on-demand content that is not part of the Hulu streaming library may include ads. This might not be understood or known by customers and a change to the name (perhaps tiers for ad level might be beneficial).

    App technical issues and UX issues need to be remedied quickly - negatively affecting customer experience. Customers can't get past these issues to get to content.

    Programming and its availability should be further evaluated for opportunities and understanding user experiences with programming.

Recommendations for HBOMax pitch:

    Pitch deck should include low review NMF topics with HBOMax standings compared to competitors.
    Spend time understanding review data to gain insights from the customers to identify issues.
    Find appropriate corporate contacts to setup the meeting.
