# Explanation of the variables stored in the data set

| Variable Name              | Description                                                                                                                                                                                                                                   |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| subjid                     | the participant ID                                                                                                                                                                                                                            |
| community                  | data collection site                                                                                                                                                                                                                          |
| age_group                  | participant's age in full years (participant with age 5 years and 11 months classified as 5)                                                                                                                                                  |
| ageinyears                 | participant's age in decimals (e.g., 5.5 means five-and-a-half years)                                                                                                                                                                         |
| trialtype                  | touch (path of balloon visible), fam (path of balloon partially covered), or test (path of balloon completely covered)                                                                                                                        |
| voiceover                  | true or false, indicating whether audio instructions were played in this trial                                                                                                                                                                |
| trialnr                    | counting variable for trial (1-19)                                                                                                                                                                                                            |
| screen                     | 1 if participants have experience with screens/monitors, 0 if they do not                                                                                                                                                                     |
| touchscreen                | 1 if participants have experience with touchscreens, 0 if they do not                                                                                                                                                                         |
| household                  | number of household members, including the participant                                                                                                                                                                                        |
| children                   | number of children living in the household, including the participant                                                                                                                                                                         |
| younger_children           | number of children living in the household that are younger than the participant                                                                                                                                                              |
| targetposition             | area of the screen in which the balloon landed (1 very left, 10 very right)                                                                                                                                                                   |
| targetcentrality           | distance between the balloon center and the center of the screen (0 = balloon landed directly in the center, 960 furthest away)                                                                                                               |
| clickdistfromtargetcenterx | distance between the balloon center (X coordinate) and the participant's click (negative values mean clicking too far to the left of the balloon, positive values too far to the right; transformed into absolute values in the analysis.Rmd) |