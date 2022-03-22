# 2020 National Library of Korea Big Data Analysis Contest #
- period : 08/25/2020 ~ 09/17/2020

## Analysis Process Description ##
**1. Data Preprocessing**
 - The data had its number  of the loaned book ranking. We knew the rank of loaned data, But Some data about the number of the loaned book had missing value. To infer the missing value, we replaced using the interpolation method.
 - We filtered children's books with ISBN(International Standard Book Number).
 
**2. Exploratory Data Analysis**
 - Check the percentage of children's books among loaned books
 - Identification of the number of children's books by book category
 - Identification of the number of books issued by children's books according to the type of publication(single book, series)

**3. Wordcloud**
 - Word Cloud is conducted by child loan and by child book borrowed by parents.
 - The year 2000 to 2019 was analyzed to see loan trends by era and four word-clouds were created by grouping them into five-year units.
 
## What I did felt ##
- I felt the importance of selecting a topic.
    - Considering that we won first place in the analysis category even though we only preprocessing and EDA, I think we received an award because of the topic selection.
    - When presenting in the finals, judges said it was novel to analyze the difference in views between children and parents who loaned children's books.
    - In addition, after the award was confirmed, our team made another announcement at the 2020 Library Big Data Performance Announcement, and the age group that the library was interested in was 8 to 13.
      - So we were asked a lot of questions, and when we conducted a written interview as the winner, they asked me about how to overcome the gap between parents and children in the library using the analysis results.

## Need to improvement ##
- There was no consideration for the series.
  - When I created the word cloud, the book name for the series was the largest, which can also be seen as representing the children's "series" books that were popular by era. 
  - Therefore, I think I would have gained better insight if I had done WordCloud after scaling the number of series. (or create each word cloud for a single book and series book.)

