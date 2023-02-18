# 1. Introduction
dbCNV is a tool to predict the pathogenicity for five-tier classification and binary classification of CNVs based on the deleterious significance of features. The quantitative evaluation of features was based on their pathogenicity levels in CNVs of different classifications.  According to the deleterious significance, we formulated quantitative methods for features, which fall into two categories: the first is variable type, including maximum, minimum and mean; the second is attribute type, which is measured by numerical sum. The reference genome version used by dbCNV is GRCh37/hg19.
# 2. Requirements
# 3. Usage and example

```
perl cal_feature_v1.pl -i example.txt -n 2
```

 -i FILE    CNV region file (Chr Start End Tye)
 -n number  the number of pathogenic classification  (2 or 5)
 -h HELP    help information
The results can be seen in the gain_2_predication_result.txt
