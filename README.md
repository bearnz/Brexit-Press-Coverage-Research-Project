# DATA301-Research-Project

Author: Josh Smith

This is a python program that utilises pySpark and the GDELT event project to answer the following research question: How did the global perception of the UK’s relationship with the EU, compared to the UK’s own perception, change following the Brexit vote in 2016? 

The results are measured on the Goldstein Scale of each event and the tone score of each source article that is analysed. Each article has its contents scraped and word frequency processed, with terms connected with brexit qualifying a source for entry into the overall analysis.

The Goldstein Scale is measured on a scale of -10 to +10 that captures the likely impact that type of event will have on the political stability of a country.

The Tone of a source covering an event is measured on a scale of -100 (negative) to +100 (positive)

Note: The processing time of this program will take over an hour if the scope of the data processing is equal-to or more-than 7 days for each data-point (currently 3 data points). Future versions utilising google cloud and more refined parallelism will hopefully cut this time down. 

Results from time of project submission are at the bottom of this page, re-running the program in it's current state will take >2 hours and may produce different results.

This was initially deveoped using the Google Colab cloud system and is designed to be run using Google cloud servers, running this locally will probably take far longer to process.
