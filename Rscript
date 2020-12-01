install.packages("riceidconverter")
library(riceidconverter)

rad <-read.table("input.txt",header = FALSE)
rad1 <- RiceIDConvert(rad,fromType = 'RAP', toType = 'SYMBOL')

write.table(rad1,file="output.txt", sep = "\t")
