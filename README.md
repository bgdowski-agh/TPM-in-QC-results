# TPM-in-QC-results
Results of tests covered in "Security Analysis of Tree Parity Machines Synchronization Process for Error Correction in Quantum Key Distribution" article + tests with different parameters

The results are split into folders - one per scenario presented in the article. The numerical data is presented in text files, as well as on charts.

There are two types of charts:
- charts that present victim's and attacker's synchronization percen per update (called "synch")
- charts that present attacker's synchonization with victims' keys, as well as number of updates performed by attacker (called "update")

Chart filenames contain:
* scenario number
* letters corresponding to the variables (and its values, if applicable)
* chart type ("synch"/"update")
* update algorithm  - "h" stands for hebbian, "r" stands for randomwalk
* QBER value in % (if applicable; in case of random keys, theres "X" instead of number)

In case of any questions regarding these results, please contact me through e-mail: bgdowski@agh.edu.pl
