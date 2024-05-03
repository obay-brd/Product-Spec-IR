# Information Retrieval and Text Analysis in R

This project involves performing text analysis on a dataset derived from an `electronics.xml` database. The main focus is on the "Specifications" column of the dataset, which contains qualitative and quantitative specifications of electronic products.

## Project Setup

### Data
The dataset used is `Products.csv`, which contains 20 rows and 5 columns. The columns include `Product ID`, `ProductName`, `Specifications`, `CategoryID`, and `SupplierID`.

### Environment
This project is implemented in R, using various packages for text processing and analysis.

## Dependencies
Install the required packages using the following commands:

```R
install.packages("tm", dependencies = TRUE)
install.packages("RWeka", dependencies = TRUE)
install.packages("textstem", dependencies = TRUE)
install.packages("textclean", dependencies = TRUE)
install.packages("text2vec", dependencies = TRUE)
