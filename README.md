# Python-Temel-Proje
Pyhton Temel Modülü kapsamında yapılan proje

1- Bir listeyi düzleştiren (flatten) fonksiyon yazın. Elemanları birden çok katmanlı listelerden ([[3],2] gibi) oluşabileceği gibi, non-scalar verilerden de oluşabilir. Örnek olarak:

input: [[1,2,3], [4,5,6], [7,8,9]]

m=[[1,2,3], [4,5,6], [7,8,9]]

flatten_m=[e for l in m for e in l]

print(flatten_m)



2) Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. Eğer listenin içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün. Örnek olarak:

input: [[1, 2], [3, 4], [5, 6, 7]]

output: [[[7, 6, 5], [4, 3], [2, 1]]

list=[[1,2],[3,4],[5,6,7]]
list.reverse()
for l in list:
    l.reverse()
print(list)
[[7, 6, 5], [4, 3], [2, 1]]
