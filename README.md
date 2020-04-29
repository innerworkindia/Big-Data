#importing from excel
library(readxl)

#loading the csv file
read_excel("**sample_sheet.xlsx**")

#extracting the columns
variable_name <- **sample_sheet**$Column_name
.
.
#no.of columns to be extracted
.
.

#To concatenate all the columns
**Variable_name_binding**<-cbind(variable_name1,variable_name2,variable_name3.... )

#instaling packages and calling libraries
install.packages("xlsx")
library(xlsx)

#saving the extracted column to a new file
write.xlsx(**Variable_name_binding**, "file_name.xlsx", sheetName="Sheet1", col.names = TRUE, row.names = TRUE, append = FALSE, showNA = TRUE)

#to view thw file
View(file_name)
