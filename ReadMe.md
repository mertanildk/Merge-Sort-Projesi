# Merge Sort

[16,21,11,8,12,22] -> Merge Sort 

### 1. Write the stages of the above array according to the sort type.

##### Öncelikle diziyi ikiye bölmeye başlanır, ardından her eleman tek kalacak şekilde bölme işlemi yapılır. Daha sonrasında yerleştirme işlemi yapılır.

| |  |  |  |  |  |  |  |  |  |  |  |
| |- |- |- |- |- |- |- |- |- |- |- |
| |  |  |16|21|11|8 |12|22|  |  |  |
| |  |  |  |  |  |  |  |  |  |  |  |
| |  |16|21|11|  |  |8 |12|22|  |  |
| |  |  |  |  |  |  |  |  |  |  |  |
| |16|21|  |11|  |  |8 |  |12|22|  |
| |  |  |  |  |  |  |  |  |  |  |  |
|6|  |21|  |11|  |  |8 |  |12|  |22|
| |  |  |  |  |  |  |  |  |  |  |  |
| |  |  |  |  |  |  |  |  |  |  |  |
|6|  |21|  |11|  |  |8 |  |12|  |22|
| |  |  |  |  |  |  |  |  |  |  |  |
| |16|21|  |11|  |  |8 |  |12|22|  |
| |  |  |  |  |  |  |  |  |  |  |  |
| |  |11|16|21|  |  |8 |12|22|  |  |
| |  |  |  |  |  |  |  |  |  |  |  |
| |  |  |8 |11|12|16|21|22|  |  |  |


### 2. Big-O Notation

<b>O(n*(logn)) --> O(6*(log6))</b>
