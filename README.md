# Bayes Decision Rule
Implementation bayes decision rule using maximum posterior probability and minimum risk optimization 

1. Create a csv with 3 columns: lightness (substitute length), countSalmon, countSeaBass. The csv data is formed from the histogram data of the lightness feature (Figure 1.3) for the fish classification in Hart et al. (2001), as count data (lightness = value, class).
2. Implement the calculation of P (class) and P (x | class) based on these data.
3. Implement Bayes decision rule based on maximum posterior probability. Execute these rules to determine the class of each interval of lightness values ​​in the read csv.
4. Implement Bayes decision rule based on minimum risk. There are 2 actions alpha1 decide salmon, alpha2 decide seabass. Also define loss as 0 if the alpha-i for the fish category is correct, and 1 if the category is wrong. Execute these rules to determine the class of each interval of lightness values ​​in the csv read. Score.

Explanation video (indonesian version) : https://youtu.be/LrTST337JZc
