# Surfs Up Analysis
## Devin Monsen
### 09/13/2022
---
## Overview of Analysis ##
---
<sub>The purpose of this analysis was to query a SQLite database, clean that list into a dataframe, and provide statistics for the months of June and December.</sub>
---
## Results June vs. December ##
---
- 1.The one obvious difference we see from the dataframes is that Junes average temp is well higher than Decembers.

- 2.We can also tell that there are 1,000+ more data points for June compared to December. This can skew our comparison and could be fixed by only accepting data from matching station ID's.

- 3.We can see that June has a lot more spread than December. 75% falls in the 74.0 degrees range. A box and whisker might be good here to visualize the quartiles and that December's temp. doesnt fall low often.

---
## Summary ##
---

