### Evidence

Identify two forms of inconsistency that were directly visible in facets: typographic (Photograph vs. photograph), different labels for same concept (Prague vs Praha)  

Identify one field in which a blank value, unknown, and an uncertain statement should not automatically be treated as equivalent: (year_raw)

### Inference

Give one example of two values you inferred referred to the same person, place, or category. What evidence supported the merge?: 'Lisboa' and 'Lisbon', evidence = different language for same city  

Give one example you chose not to merge. What evidence was missing? 'E. Atget' with 'Eugene Atget'; cannot merge because initials are not enough to securely identify the creator.

### Interpretation

Explain one way that normalizing place, creator, date, or subject values could change a later historical analysis: Normalization can speed up the process of understanding the data and makes it easier to work with for future projects.  

Why might a count of normalized place names differ from a count based on the raw metadata?: Because normalized names are grouped whereas the raw data may have multiple entries referring to the same concept but with different labels or typography.

### Limits and uncertainty

What information in the dataset would be lost if date_raw were replaced by a single year?: Uncertainties, unkowns, ranges and estimations.  

Why are repeated filenames, titles, or composite keys evidence of possible duplication rather than proof? because based on those alone one cannot securely claim that the entry is a duplicate. for that further information would be required (such as a physical inspection for example)  

### Journal
What material did I work with?  raw data (CSV-File), OpenRefine Tool

What transformation did the tool perform?  Cleaning, normalizing of data

Which decisions did I make? what entries should be grouped, normalized or cleaned and in what way.

What failed, remained unclear, or produced an unexpected result? some procedures such as reconsiliation remained unclear; what exactly is the use-case? 

What does the output allow me to infer historically? what different labels can be used for the same concept

What does the output not allow me to infer?  Wether entries are duplicates or not

Could this method contribute to my final project? Why or why not?  Yes, this is presumably the most important step in working with historical data, as it allows for proper investigation of data and saves a lot of time.
