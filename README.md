PAML_test
=========

Data used to compute probabilities of branch specific mutation rates with codeml in paml v4.7

##PAML Google-Group Question posted

Dear PAML experts,

following the example data set "lysozymesSmall" in the latest PAML package version 4.7
I tried to compute the probability of branch specific mutation rates being different from the background mutation rate in the rest of the phylogenetic tree.

Using codeml on the example lysozyme data I get 
log likelihood values and estimated omega values in the output file "mlc".

Somehow I can not get codeml to work with my own input data. 
I carefully read the manual and studied the examples without success.

The data and control files are available here:
https://github.com/asishallab/PAML_test

Click the **download ZIP** at the bottom right corner to obtain this test data.

I tried different approaches:
* Usage of '$1' in the tree instead of '#1'
* Leaving out of the quotation around the above $ or # markers
* Excluding stop codons from my input sequences

I get the warning or error "NG86 unusable", but can not make head or tails out of it.

Any help will be much appreciated.

Kind regards! 
