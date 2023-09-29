# starmeds

Cost estimation dashboard in Shiny for Post-Market Surveillance activities based on STARMeds study

I modified app.R to include translation to Indonesian.

Not working properly for all labels, but getting there. Using a csv file with translation, which I created in the google sheet below - this is not very automatized, I add new items to the translation google sheet and then save it as a .csv file.

Link to googlesheet with translation function: https://docs.google.com/spreadsheets/d/11DncuKYrns6HTVeMt9rR50tH3TyhjbwYlw4dcGwyAMY/edit?usp=sharing

Versions:
app.R (former app4_5) ->  corrected bug on delete/add row in analysis and reporting.
                          stopped using webshot for plots. plots are now generated in the rmarkdown. 
                          report showing in tab does not contain plots. 
                          Small changes to intro.

app.R (former app4_4) -> only one download button for both languages in a new tab + report showing automatically at the end

app4_3 -> only one download button for both languages in a new tab. code contains attempts to show html in tab.

app4_2 -> new version with more tables, translation and report in english and indonesian
