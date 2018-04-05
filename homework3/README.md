# Lies of Donald Trump

## Data source

This dataset is extracted from the New York Times website which contains Donald Trump's lies on media since he took office on Jan 20, 2017 until Nov 11, 2017.

Starting page: https://www.nytimes.com/interactive/2017/06/23/opinion/trumps-lies.html

## Data fields

* `date` - String, in the format of month, date followed by the year e.g. `Jan. 21, 2017`
* `lies` - String e.g. `I wasn't a fan of Iraq. I didn't want to go into Iraq.`

## Data volume

* 180 rows (lies)

## Data analysis
Using pandas library, the dataset was analysed to identify trends and patterns of the dataset. 
* Trump lied the most in February and there was a declining trend since then except in October 2017 when he presented his tax plan in early October. During that month, he told the second highest number of lies. 
* Using the word count module, it is found that many of Trump's lies are about the inaccurate representation of numbers or numbers of dollars. 
* Among the countries Trump mentioned in his lies, he mentioned Russia the most, followed by China and Iraq. 

## Charts used
* bar chart
* word cloud

## License

CC 4.0
