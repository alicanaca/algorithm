# [16,21,11,8,12,22] -> Merge Sort tekniğine göre aşamalarını yazınız.
1. [16,21,11,8,12,22] --> [16,21,11]       [8,12,22]
2. [16,21,11]       [8,12,22] --> [16,21]   [11]      [8,12]    [22]
3. [16,21]   [11]      [8,12]    [22] --> [16]   [21]   [11]  [8]    [12]   [22]
4. [16]   [21]   [11]  [8]    [12]   [22] --> [16,21]    [11]     [8,12]     [22]
5. [16,21]    [11]     [8,12]     [22] --> [11,16,21]       [8,12,22]
6. [11,16,21]        [8,12,22] --> [8,11,12,16,21,22]

# Big-O gösterimini yazınız.
O(n*(logn)) -> O(6*(log6))

## Patika Linki
[Cymbolt](https://app.patika.dev/cymbolt)