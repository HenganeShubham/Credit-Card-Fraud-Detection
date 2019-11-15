# Credit-Card-Fraud-Detection

Fraud = dataset[dataset['Class']==1]
Valid = dataset[dataset['Class']==0]

print("fraud cases:" ,format(len(Fraud)))
print("valid cases:" ,format(len(Valid)))

Fraud cases: 492
Valid cases: 284315

based on this we can simply calculate fraud percentage---

Outlier = len(fraud)/float(len(valid))
print(Outlier)

0.0017304750013189597
