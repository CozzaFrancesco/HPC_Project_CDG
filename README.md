**Authors:**
- Francesca Del Gaudio
- Francesco Cozza

The two files contain two parallel implementations of the Frequent Itemset Counting.
Specifically, Apriori Roaring Bitmap parallelizes the Apriori algorithm using OpenMP and leverages Roaring Bitmaps.
DIC, on the other hand, parallelizes the Dynamic Itemset Counting (DIC) algorithm using OpenMP and additionally utilizes the bitset representation for both transactions and itemsets.

**Note!** The files need to be uploaded to Google Colab to be read.
