# machine-learning-all-important-notes

1. যদি কোন datasets এর কলাম নেইম বড় হই তখন কলাম নাম চেইন্জ করার জন্য: df.rename(columns={'Gender':'gender','Age':'age','Annual Income (k$)':'income','Spending Score (1-100)':'score'},inplace=True)
2. একসাথে অনেকগুলো কলামকে matrix আকারে গ্রাফ দেখার জন্য : ![output](https://user-images.githubusercontent.com/68488154/144737567-bc3afce8-8bc3-4212-a511-e12872dfb3f1.png)
seaborn.pairplot(df[['age','income','score']])
 

