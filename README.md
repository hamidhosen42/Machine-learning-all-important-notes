# machine-learning-all-important-notes

### Top Python Machine Learning Libraries
1) NumPy
2) SciPy
3) Scikit-learn
4) Theano
5) TensorFlow
6) Keras
7) PyTorch
8) Pandas
9) Matplotlib

1. যদি কোন datasets এর কলাম নেইম বড় হই তখন কলাম নাম চেইন্জ করার জন্য: df.rename(columns={'Gender':'gender','Age':'age','Annual Income (k$)':'income','Spending Score (1-100)':'score'},inplace=True)
2. একসাথে অনেকগুলো কলামকে matrix আকারে গ্রাফ দেখার জন্য :seaborn.pairplot(df[['age','income','score']])  ![output](https://user-images.githubusercontent.com/68488154/144737567-bc3afce8-8bc3-4212-a511-e12872dfb3f1.png)
3. Scatter plot: sns.scatterplot(x='income',y='score',hue='income_cluster',data=df) ![output](https://user-images.githubusercontent.com/68488154/144737789-2ce1774d-1ded-4abc-abc9-efedab708ede.png)


