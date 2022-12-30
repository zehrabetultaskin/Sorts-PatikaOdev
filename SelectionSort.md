# Selection Sort

### [7,3,5,8,2,9,4,15,6]
---

* İlk olarak ilk elemanla en küçük değerlikli sayıyı kıyaslar. Bu durumda 7 yerine grubun en başına 2 gelir.

```
2,3,5,8,7,9,4,15,6
```
---
* Ardından 2 ve 3 kıyaslanır. 3 yerinde kalır.
---
* Sonra 5 ile gruptaki kalan en küçük sayı kıyaslanır. 5 yerine 4 gelir.

```
2,3,4,8,7,9,5,15,6
```
--- 
* Sonra 8 ile kalan en küçük değer olan 6 kıyaslanır. Ve yer değiştirirler.

```
2,3,4,5,6,9,8,15,7
```
---
* Ardından 9 ile 7 kıyaslanır. Ve yer değiştirirler.

```
2,3,4,5,6,7,8,15,9
```
---
* 8 ile kıyaslama yapılır. Daha küçük bir değer olmadığı için yerinde kalır.
---
```
2,3,4,5,6,7,8,9,15
```
* Son olarak da 9 ve 15 kıyaslanır. Yer değiştirirler. Ve selection sıralaması tamamlanır.