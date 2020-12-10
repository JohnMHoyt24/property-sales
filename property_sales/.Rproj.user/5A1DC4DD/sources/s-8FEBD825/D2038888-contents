library(tidyverse)
#Data will imported from a .csv file
sales <- read_csv("data/nyc-rolling-sales.csv")

sales$X1 <- NULL #This function is will remove the X1 column from the dataframe
sales$`EASE-MENT` <- NULL
sales$`APARTMENT NUMBER` <- NULL
                 
head(x = sales, n = 5) #Displays the first five rows of data

total_sales <- nrow(sales) #Displays the number of rows of data

View(sales)
