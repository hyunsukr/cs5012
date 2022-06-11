<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

# ICA 3
Name: Hyun Suk (Max) Ryoo

Activity Name: CS 5012: Linear Probing and Chaining In-Class Activity

Computing ID: hr2ee


h(K) = K mod 13

Insert the following keys into the hash tables below, using each conflict resolution method:

18, 41, 22, 44, 59, 32, 31, 73

#### Hash Table: Linear Probing

- h(18) = 18 mod 13 = 5
- h(41) = 41 mod 13 = 2
- h(22) = 22 mod 13 = 9
- h(44) = 44 mod 13 = 5 = 6 (linear probing since 5 is occupied)
- h(59) = 59 mod 13 = 7
- h(32) = 32 mod 13 = 6 = 7 = 8 (linear probing since 6 is occupied and 7 is occupied)
- h(31) = 31 mod 13 = 5 = 6 = 7 = 8 = 9 = 10 (linear probing since 5 is occupied and until 10 every location is occupied)
- h(73) = 73 mod 13 = 8 = 9 = 10 = 11 (linear probing for 8 until resolution at 11)

| 0 | 1 |  2  |  3  |  4|  5 | 6   |  7   |  8  |  9  | 10  | 11   | 12 |
|---|---|---  |---  |---|--- |---  |---   |---  |---  |---  |---   |--- |
|   |   |  41 |     |   | 18 | 44  |   59 |  32 |  22 |  31 |  73  |    |


#### Hash Table: Chaining

- h(18) = 18 mod 13 = 5
- h(41) = 41 mod 13 = 2
- h(22) = 22 mod 13 = 9
- h(44) = 44 mod 13 = 5
- h(59) = 59 mod 13 = 7
- h(32) = 32 mod 13 = 6
- h(31) = 31 mod 13 = 5
- h(73) = 73 mod 13 = 8

| 0 | 1 |  2  |  3|  4|  5  | 6   |  7  |  8  |  9  | 10| 11| 12|
|---|---|---  |---|---|---  |---  |---  |---  |---  |---|---|---|
|   |   |  41 |   |   |  18 | 32  |  59 |  73 |  22 |   |   |   |
|   |   |     |   |   |  44 |     |     |     |     |   |   |   |
|   |   |     |   |   |  31 |     |     |     |     |   |   |   |