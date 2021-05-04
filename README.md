# ElementaDetectionProbabilities
Data used in the Elementa manuscript "Characterizing detection probabilities of advanced mobile leak surveys: implications for sampling effort and leak size estimation in natural gas distribution systems" by Luetschwager, von Fischer, and Weller.

There are two data sets in this respository:

(1.) TemporalCorrelation_SizeEstimation_Data.csv

This data set was used to create Figures 1, 2, 5 and S1.

Variables in this data set include: LeakID, MaxExCH4, HoursSinceJan1, DaysSinceJan1, FracDay

(2.) LeakSize_Drives_Data.csv

This data set was used to create Figures 3, 4, 5, S2, and S3.

Variables in this data set include: CityId, LeakId, Then the number of drives/detections/excess CH4 measurements. Each row represents a location where at least one leak indication (i.e., elevated CH4 levels) were detected by the survey vehicle.

For columns C and beyond, each column represents a drive-by (or lack there-of) of the leak indication location. Specifically, the entries in each column denote the following:

-> a "0" means the survey vehicle drove by the location but did not detect CH4 above baseline
-> any value greater than 0 denotes a detection on that drive-by and respresents the max excess CH4 measurement (max CH4 - background) from that drive by
-> a blank means that the location was not driven by that number of times; that is, if Columns C, D, and E of a row have numerical entries followed by blanks, it implies that leak indication location had exactly three drive-bys


Note: the leak id's are unique to each data set (not the same between sets)
