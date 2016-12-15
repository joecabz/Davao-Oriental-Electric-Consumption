# Davao-Oriental-Electric-Consumption
This is a project to conduct study in projecting electric consumption of Davao Oriental base on historical data.

# Data Preprocessing
mnthPower <- read.table("davOr.txt",header = TRUE, sep = "\t") 
tmp_mnthPower <- mnthPower[,1:2]
tmp_mnthPower #display data
class(tmp_mnthPower) # check the type of data (data.frame)
