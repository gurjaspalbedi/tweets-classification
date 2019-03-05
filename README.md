**Determine Location of Tweet**
Finding the city from where the user tweeted.

**Input:** 
    Each line in the input file is in the following format

    <Location> <space> <Tweet>

*Location:* From where the user tweeted
*Tweet:* The actual tweet we are trying to classify

This implementation uses simple Naive Bayes approach to classify the tweets.

**How to Run the code?**

    python geolocation.py <train_file_name> <test_file_name> <output_file>

Example:

    python ./geolocation.py tweets.train.clean.txt tweets.test1.clean.txt output.txt

**Result:**

The accuracy using the Naive Bayes approach is approximately 70%
