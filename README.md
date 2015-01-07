# Rule-based-model-of-DNA-supercoiling

# Introduction

The two strands of DNA form a double helix structure, which can further twist with itself
and form sup ercoils. The sup erhelical d ens ity of a DNA region can b e measured by u sing the
following equation:
          σ = ∆ LK /LKrelaxed
where ∆ LK is the difference b etween the linking nu mb er of a DNA (LK) and the linking
numb er of its relaxed form (LKr el axed). Its degree is essential for many biological processes,
like protein-DNA interaction and transcription. Accordingly, a group of enzymes called topoisomerase is responsible for regulating the DNA supercoiling process. For example, there are three
topoisomerases identified in M.genitalium: DNA gyrase, topoisomerase I and topoisomerase IV.
Among them, topoisomerase I can relax negatively supercoiled DNA, whereas DNA gyrase and
topoisomerase IV can act on positively supercoiled DNA and induce negative supercoils.

# Assignment

The overall goal of this assignment is to explore the National Emissions Inventory database and see what it say about fine particulate matter pollution in the United states over the 10-year period 1999–2008. You may use any R package you want to support your analysis.

## Preparing the Data Set 

 ```{r setup,echo=FALSE}
if(!file.exists("./data")){
        dir.create("./data")
}
fileUrl = "https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2FNEI_data.zip"
destfile="./data/exdata_data_NEI_data.zip"
download.file(fileUrl, destfile, method ="auto")
unzip(destfile, overwrite = T, exdir = "./data")
```
 
![alt tag](https://github.com/lvncnt/ExDataAnalysisII/blob/master/plot1.png)

* Have total emissions from PM2.5 decreased in the United States from 1999 to 2008? 

The total emissions from PM2.5 have decreased in the United States from 1999 to 2008. 
 
