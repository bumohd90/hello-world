# HARD: Hotel Arabic-Reviews Dataset
- [Description](#description)
- [Dataset](#dataset)
- [Citation](#citation)

## Description

This dataset contains **93700** hotel reviews in Arabic language. The hotel reviews were collected from [Booking.com](http://www.booking.com) website during June/July 2016. The reviews are expressed in Modern Standard Arabic as well as dialectal Arabic.

## DAtaset

- data/
                      
  - balanced-reviews.tsv: a tab separated file containing a balanced dataset of positive and negative reviews. The ratings are 
                     mapped into positive (ratings 4 & 5) and negative (ratings 1 & 2). No nuetral reviews are included. 
                     The dataset consists of *93700* reviews; *46850* for each positive and negative classes.
                     
   - balanced-reviews.csv: same as above dataset but using the CSV format.

- unbalanced-reviews.tsv: the whole dataset of *492,457* reviews.  The format of each review record is:
                     
                     rating<TAB>sentiment<TAB>review_id<TAB>hotel_id<TAB>user_id<TAB>no_nights<TAB>review
                     
    where:
                     rating: the user rating on a scale of 1 to 5
                     sentiment: -1 (negative) and 1 (positive)
                     review id: the id of the review (to access the review of a specific review)
                     hotel id: the id of the hotel
                     user id: the type of user (single, couple, ...)
                     nights: number of nights stayed in the hotel
                     review: the text of the review
                       
                   
## Citation

Please cite the following paper if you decise to use the dataset:

    Elnagar A., Khalifa Y.S., Einea A. (2018) Hotel Arabic-Reviews Dataset Construction for Sentiment Analysis Applications. 
    In: Shaalan K., Hassanien A., Tolba F. (eds) Intelligent Natural Language Processing: Trends and Applications. 
    Studies in Computational Intelligence, vol 740, pp: 35-52. Springer International Publishing. 
    doi="10.1007/978-3-319-67056-0_3. url="https://doi.org/10.1007/978-3-319-67056-0_3"
