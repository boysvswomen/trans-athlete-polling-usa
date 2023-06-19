# About the BoyVsWomen Trans Athlete Polling List #

This repo is maintained by [@boyvswomen](https://twitter.com/boysvswomen). The goal is to provide easy access to current and past support or opposition to trans athletes competing in the category with which they identify (as opposed to the category of their sex).

This list includes polling with many different questions and answers, so support or opposition should be understood broadly, and not, for example, as support or opposition for a specific bill or policy.

Polls need to be able to be categorized into either supporting or opposing whether trans athletes compete according to their gender identity.

# How to View & Use the Data #

The data is saved as a spreadsheet in the CSV format, in two files.

The easiest way to view the data is to view the file [here](https://github.com/boysvswomen/trans-athlete-polling-usa/blob/main/polling_data_evaluated.csv) on github. Use the horizontal scroll bar to scroll right and see the data.

- **polling_data.csv** This file contains formulas which you will need to allow your spreadsheet editor to evaluate in order to see all of the data.
  - [To download polling_data.csv: follow this link, right-click anywhere on the page -> *Save As*](https://raw.githubusercontent.com/boysvswomen/trans-athlete-polling-usa/main/polling_data.csv)
- **polling_data_evaluated.csv** In this file, the formulas have been evaluated (ie: there are no formulas).
  - [To download polling_data_evaluated.csv: follow this link, right-click anywhere on the page -> *Save As*](https://raw.githubusercontent.com/boysvswomen/trans-athlete-polling-usa/main/polling_data_evaluated.csv)

## Columns ##

These first columns are self explanatory:

- `Date Start`
- `Date End`
- `Pollster`	
- `Sample Size`
- `Link 1` 
- `Link 2`	
- `Notes`	
- `Question`
- `Answers`	

Next is the overall data (data that was not broken by sex/political party). The numbers here will need to be formatted as percents in your editor (multiplied by 100). Some polls asked respondents how strongly they felt, others only asked if they supported or opposed:

- `ALL % Oppose (Strong)`
- `ALL % Oppose (Somewhat)`
- `ALL % Oppose`
- `ALL % Support`
- `ALL % Support (Somewhat)`
- `ALL % Support (Strong)`
- `ALL % Undecided/Don't Know`

These Columns are calculated:

- `ALL % Oppose Total` - This is a sum of: `% Oppose (Strong) + % Oppose (Somewhat) + % Oppose`
- `ALL % Support Total` - This is a sum of: `% Support + % Support (Somewhat) + % Support (Strong)`
- `ALL % Oppose Among Decided` - This is `% Oppose Total / % Support Total`

Where data is available for Sex or Political Affiliation, the next columns were used in the same format as the above, but labeled with:

- `DEM` - Democrats
- `IND` - Independents
- `REP` - Republicans
- `MEN` 
- `WOMEN`

Lastly is the column `Had question about sex segregation in sport in general`. Some of the polling has data on support and opposition to sex segregation in sport, so a column was added to help track this. In the future, this will probably be moved to a separate list.

# Polls Where More Information Is Needed #

These polls had incomplete information when last checked. As time passes, better information may become available as it is release and picked up by Google. Also, it may be possible to contact people involved to request information.

- https://www.newsweek.com/americans-oppose-puberty-blockers-transgender-minors-1806621
  - The question in the article included medical treatment as a requirement. It's possible another question was asked, but there is no link to the toplines.
- https://www.commondreams.org/views/2022/09/08/debates-about-trans-athletes-and-competition-where-attention-trans-men
  - The data is incomplete, and the author of the article has not responded with more information: https://twitter.com/boysvswomen/status/1656308786523414530?s=20
- Crosstabs for all of the Rasmussen polls are behind a paywall (assuming they exist).