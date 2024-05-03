# DataMiningProject
Data mining project for CSPB-4502

# Title: LetterBoxd Film Analysis

# Description:

The film industry is constantly evolving and with it the viewing public's tastes. Because of this it is becoming more important to understand these trends both as filmmakers and viewers. By understanding the underlying factors that influence a film’s success we can determine if any particular factor plays a greater role in determining a film's success. This project aims to do just that, by studying the data available from LetterBoxd, a crowd sourced film review site, we can make predictions of certain films. 


## Team Members: Clayton Brittan

# Questions and Answers: 

    Q: What are the key factors that contribute to a film's success in terms of audience reception and ratings?
        Answer: What our model showed is that Film Themes, Duration and Release date all play a role in shaping a films aggregate rating. 

    Q: How do different factors such as release year, duration, genre themes, and other features influence a film's ratings on a platform like LetterBoxd?
        Answer: Our models showed that each of these features hold respective weights on the total film score, those weights being:
        Feature: date, Importance: 0.29043848409355005
        Feature: minute, Importance: 0.2778505425441498
        Feature: Action, Importance: 0.011703056446202656
        Feature: Action, Importance: 0.011235682839982393
        Feature: Adventure, Importance: 0.008533547946722323
        Feature: Adventure, Importance: 0.008189287810357309
        Feature: Animation, Importance: 0.008612198422560698
        Feature: Animation, Importance: 0.008369390510258447
        Feature: Comedy, Importance: 0.01165249057830578
        Feature: Comedy, Importance: 0.011875824306294521
        Feature: Crime, Importance: 0.010376310414407178
        Feature: Crime, Importance: 0.009739365932093822
        Feature: Documentary, Importance: 0.026939740748641687
        Feature: Documentary, Importance: 0.028149153220886153
        Feature: Drama, Importance: 0.0385297366305656
        Feature: Drama, Importance: 0.04930353286462626
        Feature: Family, Importance: 0.005818285192779462
        Feature: Family, Importance: 0.0057899852627743675
        Feature: Fantasy, Importance: 0.008426180709725164
        Feature: Fantasy, Importance: 0.008876796410457168
        Feature: History, Importance: 0.002875169884527927
        Feature: History, Importance: 0.0027800669905419847
        Feature: Horror, Importance: 0.023402207819483847
        Feature: Horror, Importance: 0.02173065937728182
        Feature: Music, Importance: 0.005006225405535622
        Feature: Music, Importance: 0.005451216698182277
        Feature: Mystery, Importance: 0.007572364538553368
        Feature: Mystery, Importance: 0.007652828582773318
        Feature: Romance, Importance: 0.008918536034666217
        Feature: Romance, Importance: 0.008509011614838484
        Feature: Science Fiction, Importance: 0.011110500064099927
        Feature: Science Fiction, Importance: 0.012676733262682921
        Feature: TV Movie, Importance: 0.0033533569276875995
        Feature: TV Movie, Importance: 0.0033130658519739476
        Feature: Thriller, Importance: 0.013106470195703351
        Feature: Thriller, Importance: 0.011917447309169696
        Feature: War, Importance: 0.0026975832295430976
        Feature: War, Importance: 0.0026792381533785737
        Feature: Western, Importance: 0.002374804640056281
        Feature: Western, Importance: 0.00246292053397884

    Q: Are there any discernible trends or patterns in audience preferences over time, and how do these trends correlate with changes in the film industry?
        Audiences concistently prefer Drama Movies, yet the actors and sub genres vary over time significantly 

    Q: Can we accurately predict the success or ratings of a film based on its various attributes such as release year, duration, and genre themes?
        We can predict most films to an MSE of 0.19 however based on the distribution of the data, the model isn't very accurate with films that skew in either direction and therefor isn't accurate on unseen data. 

    Q: What insights can be gained from analyzing crowd-sourced film reviews and ratings on platforms like LetterBoxd, and how can these insights inform filmmakers and viewers about evolving trends in the film industry?
        We can analyze which actors preform better and which genres are most liked, if we incorporate more data we can also create better predictive models.

# Video Link: https://youtu.be/Ig3hEgqtYUo

# Final Writup: 

