# Oyster card data analysis and visualization

Jupyter Notebook [<code>oyster.ipynb</code>](https://github.com/ZaraTam/oyster/blob/master/oyster.ipynb)

<br>

### Goal

Origin and destination analysis and visualization of Transport for London (TfL) tube journeys based on districts of Greater London

<br>

### Data sets

Data sets are not hosted on GitHub.

#### Oyster card journey

Available for download at: https://api-portal.tfl.gov.uk/docs

This data set provides a 5% sample of all Oyster card journeys performed in a week during November 2009 on bus, Tube, DLR and London Overground.

Column descriptions
(Source: http://data.london.gov.uk/dataset/oyster-card-journey-information)
- downo - a number between 1 and 7, 1 being Sunday, 2 being Monday etc
- daytype - Sun to Sat
- SubSystem - the mode(s) of the journey. LUL - London Underground, NR - National Rail, LTB - London Buses, DLR- Docklands Light Railway, LRC - London Overground, TRAM - Croydon Tram
- StartStn - Station the journey started at
- EndStation - Station the journey ended at
- EntTime - Entry time of the journey in minutes after midnight
- EntTimeHHMM - Entry time in HH:MM text format
- ExTime - Exit time of the journey in minutes after midnight
- EXTimeHHMM - Exit time in HH:MM text format
- ZVPPT - zones of Oyster Season ticket, if used
- JNYTYP - Product types involved in the journey. PPY - Pure PAYG, TKT - Pure Oyster Season, MIXED - Combined PAYG and Oyster Season
- DailyCapping - it shows as Y when PAYG journey was capped
- FFare - Full PAYG Fare before any discounts
- Dfare - PAYG Fare after usage based discounts
- RouteID - The Route Number of the Bus, if a Bus has been boarded
- FinalProduct - Combined Product Description used for journey


#### TfL station locaitons

Available for download at: https://api-portal.tfl.gov.uk/docs

This data set is a geo-coded KML feed of most London Underground, DLR and London Overground stations.


#### Districts of Greater London

Available for download at: https://data.gov.uk/dataset/county-and-unitary-authority-december-2015-full-extent-boundaries-in-england-and-wales/resource/cf40a4f7-3686-4818-b0ea-79e8b259ea16

This data set contains digital vector boundaries for counties, metropolitan districts, London boroughs and unitary authorities in England and Wales as at December 2015.
