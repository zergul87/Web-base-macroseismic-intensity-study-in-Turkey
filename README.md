# Web-base-macroseismic-intensity-study-in-Turkey
Web-base macroseismic intensity study in Turkey: user comments in eksisozluk.com

## topics
Entries with username, date/time and link information of earthquakes.
## analyzed Topics
Entries with username, date/time, link, felt report, city, town, neighborhood, intensity and magnitude guess
information of earthquakes.
## suser_mag_guesses
Analysis of magnitudes guesses done by users of the eksisozluk vs. the measured magnitudes.
## shakemaps
Shake map graphs that are created by using the method of 
Tiberi, Lara, et al. "The 1895 Ljubljana earthquake: 
can the intensity data points discriminate which one of the nearby faults was the causative one?." 
Journal of seismology 22.4 (2018): 927-941.
## settlements
Folder contains the city, town, district and neighborhood information of Turkey.
## Codes
find_eq_topics.py - Get all earthquake topics in eksisozluk.com.

get_entries.py - Reads the 20 most commented earthquake topics in the website.

match_entry.py - Reads all entries in topics and finds entries with city, town, district, neighborhood information. Felt (e_feel)
, city (e_city), town (e_town), neighborhood (e_neighborhood) and magnitude guess (e_guess) of the user can be given via command-line interface.

intensity.py - Read e_feel = 1 entries of all topics. Intensity grade of the entry (e_intensity) can be given via command-line interface.


# Citation
Soon to be announced...