This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 
It is about the influence of soap operas on the fertility based on the paper "Soap Operas and Fertility: Evidence from Brazil" 
by Eliana La Ferrara, Alberto Chong and Suzanne Duryea (2012). 
The paper can be downloaded on this link: https://www.aeaweb.org/articles.php?doi=10.1257/app.4.4.1

To install RTutor and work on the problem set you follow these steps:

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)
  
install_github("ClaraUlmer/RTutorSoapOperas")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorSoapOperas)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorSoapOperas")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorSoapOperas",
       load.sav=TRUE, sample.solution=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
