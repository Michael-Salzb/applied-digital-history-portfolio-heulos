Part 1 to 3

3) opening the .csv file directly leads to the content not being displayed in proper columns, whereas importing the files content via excel's 'Data' register immediately recognizes them.
4) yes 'Köln' for example is shown correctly, regardless of which way you chose to import the data.
6) an empty cell means that there is no content in it, so zero?
7) if year shows a timeframe (for example '[1507-1512]') then year-numeric will show the first of those two values




Part 4
1) What does one row represent?
an edition record, meaning that different editions of the same text can appear multiple times throughout the dataset
2) Does a row describe a physical copy, an edition, or an aggregate?
an edition
3) Which columns contain categories?
short_title, author, printer, place, language, format, country, decade
4) Which columns contain quantities?
year_numeric
5) Which columns are identifiers rather than quantities?
edition_id
6) How are dates represented in year, year_numeric, and decade?
in 'year' they are shown as text, 'year_numeric' extracts the numbers/values from the text in 'year' and 'decade' calculates its content from 'year_numeric'
7) How are missing values represented?
through a blank cell, does not mean that value is 0 but rather unknown (a blank cell in 'author' means that the information on the author is unknown, rather than there not being an author in the first place)
8) Are any categories uncertain, inconsistent, or historically constructed?
on a first glance the categories seem consistent

Part 5

string value: 'De herbarum virtutibus'
numerical value: '1590'
temporal value: '1581'
uncertain value: '[1507-12]'

Part 6

i am unsure wether RAWGRAPHS noting 'year' as number is correct or not. (RAWGRAPHS showed 13 values in this category to be faulty)

8. 'Von Sant Meinrat ein Lesen, was Elend und Armut er erlitten hat'; year: '[1507-1512]' vs. year_numerical: '1507'
