# Lies of Donald Trump on Media

## Data source
This dataset (t_lies.csv) is extracted from the New York Times website which contains Donald Trump's lies on media since he took office on Jan 20, 2017 until Nov 11, 2017.

Starting page: https://www.nytimes.com/interactive/2017/06/23/opinion/trumps-lies.html

## Data fields
* `date` - String, in the format of month, date followed by the year e.g. `Jan. 21, 2017`
* `lies` - String e.g. `I wasn't a fan of Iraq. I didn't want to go into Iraq.`

## Data volume
* 180 rows (lies)

## Data analysis
Using pandas library, the dataset was analyse to identify the trends and patterns of the lies told by Donald Trump during the 11 months in office. 
* Trump lied the most in February and there was a declining trend since then except in October when he presented his tax plan early in that month. He told the second highest number of lies in October. 
* During the period, Trump told the highest number of lies on media on June 21 with 8 times. 
* Using word_count, it is found that many of Trump's lies are about inaccurate presentation of numbers or number of dollars. 
* Among the countries that Trump mentioned in his lies, he mentioned Russia the most, followed by China and Iraq.
* The recorded lies of Donald Trump are presented by 2 word clouds, with the first one without 'stop words' and the other with 'stop words'.

## Charts used
* 2 bar charts
* 2 word clouds

## License
CC 4.0
