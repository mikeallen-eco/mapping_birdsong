# Geography of Birdsong Project (mapping_birdsong)
Steps:
1. Download this repository to your computer and unzip it (don't change folder or file names or locations yet).
2. Look through your field guide paying special attention to species range maps and comments about their vocalizations. Select a species that interests you and might have an interesting evolutionary story to tell.
3. Go to https://www.macaulaylibrary.org/ and enter the species name to retrieve media.
4. Apply filters to limit your selection to 1) audio by clicking the speaker button in the header, and 2) song (unless you want to analyze call notes) by clicking "More filters" and checking the "song" box.
5. Download the spreadsheet for the resulting data.
6. Move the file into the "data" folder.
7. Open the R project by double clicking the .Rproj file (you should already have R and RStudio free version installed).
8. Open the RMarkdown file and follow the directions in it.

Directions below here need editing once Rmarkdown is done...

0. Click the upper left corner to highlight all cells
11. data tab click the Filter button
on header "average community rating" uncheck all then re-check only those with >= 4
Latitude" uncheck the box next to "blanks" ensuring you only have records with geographic info
How many records are left?
Sort by latitude or longitude (whichever you are intersted in). What is the range? How many degrees are covered?
We'll now divide up our samples into latitude or longitude "bins"
Add a column named "samples" next to the sorted latitude or longitude column.
Calculate the a number of samples "n" per bin required to give you a total sample size of at least 25
Put a 1 in the "samples" column for the top "n" samples in each bin. Some bins may only have one sample. That's ok. If you still need more samples to reach 25 once you are done with that, go back through and place an extra 1 in every other bin with enough records. Repeat if necessary to reach 25.
Sort by the "samples" column so that all of your chosen samples are on top. Are there at least 25? 
In the Data tab, click the "Filter" button again so that all data are visible. 
Delete all rows that do not have a 1 in the sample column.

Now start to explore your samples. Paste the ML catalog number after the following URL:
https://macaulaylibrary.org/asset/
For example Prairie Warbler sample 110249 would be:
https://macaulaylibrary.org/asset/110249

Now it is time to select a measurement or specific research question. Listen to the songs and look at the sonograms. What might be an interesting aspect to measure that might vary across space?

Trill rate?
Minimum, maximum, or range of frequency (kilohertz)?
How often (e.g., what proportion of total) certain syllable types appear?
How close together in time the phrases are?
The number of syllables per phrase?

how to measure: use a ruler to measure height or width in mm
also include: the length of 1 s and 1 kHz in mm on your screen


 






