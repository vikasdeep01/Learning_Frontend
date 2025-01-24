 //ANCHOR - In HTML if any element having two properties and both conflict like one property says colour:blue and another say colour:maroon  the the specificity will be calculated 


 --> If selector is same then the last applied will be winner

 Prority of various selectors  : 

  !Important > Inline styles > ID > classes and attribute selector > element selector > Universal selector  


 // SECTION - Calculate specificity   
 
                        !Important                       > 10000
                        Inline styles                    > 1000
                        ID                               > 100
                        classes and attribute selector   > 10
                        element selector                 > 1
                        Universal selector               > 0