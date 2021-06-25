# Pengujian Normalitas

## Keruncingan dan Kemencengan
    . sktest bmi

                        Skewness/Kurtosis tests for Normality
                                                              ------ joint ------
        Variable |        Obs  Pr(Skewness)  Pr(Kurtosis) adj chi2(2)   Prob>chi2
    -------------+---------------------------------------------------------------
             bmi |      2,509     0.0000        0.0000           .         0.0000


## Shapiro Wilk
     . swilk bmi

                    Shapiro-Wilk W test for normal data

        Variable |        Obs       W           V         z       Prob>z
        -------------+------------------------------------------------------
             bmi |      2,509    0.89814    148.425    12.823    0.00000

             Note: The normal approximation to the sampling distribution of W'
                   is valid for 4<=n<=2000.

## Shapiro Francia
       . sfrancia bmi

                         Shapiro-Francia W' test for normal data

        Variable  |       Obs       W'          V'        z       Prob>z
     -------------+-----------------------------------------------------
              bmi |     2,509    0.89761    158.238    12.296    0.00001