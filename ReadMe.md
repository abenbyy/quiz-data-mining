# Kisi Kisi Quiz Data Mining

Nanti dikasih 2 csv, anggep aja yang 1 data item, yang 1 data transaksi
Contoh:

### item.csv

|ID|Name    |Price|
|--|--------|-----|
|1 |Burger  |26000|
|2 |Pizza   |22000|
|3 |Calzone |22000|
|4 |Fries   |15000|
|5 |Soda    |9000 |


### transaction.csv

|TID |Item    |
|----|--------|
|T001|Burger  |
|T002|Burger  |
|T002|Fries   |
|T002|Soda    |
|T003|Pizza   |
|T003|Burger  |
|T004|Calzone |
|T004|Pizza   |
|T005|Fries   |
|T005|Soda    |


## Data Visualization
Ada 3 soal:
1. Visualization Only
2. Preprocessing + Visualization
3. Preprocessing + Visualization

```
pie()
barplot()
plot()
legend()
hist()
boxplot()
```

## Frequent Pattern Analysis

### 1. Merge
Gabungin datanya
```
merge()
```
### 2. Filter
Misalnya disuruh filter data dimana harga nya harus diatas 15000

### 3. Split
```
split()
```

### 4. Apriori
Perhatikan minimum support
```
apriori()
```
    
### 5. Association Rules
Perhatikan minimum confidence
```
ruleInduction()
```
