# Binary Tree Sort

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  
---

```
            7
           /
          5  
```
* Root 7'dir. 
* 5'den küçük olduğu için onu 7'nin soluna yerleştiririz.

``` 
             7
            / 
           5
          /
         1
```
* 1, 7'den küçük olduğu için soluna geçer.
* 1, 5'ten küçük onu 5'nin soluna yerleştiririz.

``` 
             7
            / \
           5   8
          /
         1
                

```
* 8, 7'den büyük olduğu için onun sağına yerleştiririz. 


``` 
             7
            / \
           5   8
          /
         1
          \
           3               

```

* 3, 7'den küçük olduğu için onu 7'nin soluna alırız.
* 3, 5'den de küçük olduğu için onu 3'ün soluna alırız.
* 3, 1'den büyük olduğu için onu 1'in sağına yerleştiririz. 


``` 
             7
            / \
           5   8
          / \
         1   6
          \
           3               

```
* 6, 7'den küçük olduğu için onun soluna geçer. 
* Daha sonra 6, 5'den de büyük olduğu için 5'in sağına yerleştiririz.


``` 
             7
            / \
           5   8
          / \
         1   6
        / \
       0   3               

```
* 0, 7'den küçük olduğu için onu 7'nin soluna alırız.
* 0, 5'ten küçük olduğu için onu 5'ün soluna alırız.
* 0, 1'den de küçük olduğu için onu 1'in soluna yerleştiririz.

``` 
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3               

```
* 9, 7'den büyük olduğu için onun sağına geçer. 
* Daha sonra 9, 8'den de büyük olduğu için 8'in sağına yerleştiririz. 


``` 
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
            \               4

```
* 4, 7'den küçük olduğu için 7'nin sağına geçer.
* 4, 5'ten küçük olduğu için 5'ün soluna geçer.
* 4, 1'den de büyük olduğu için onu 1'ün sağına
alırız.
* 4, 3'ten büyük olduğu için onu 3'ün sağına yerleştiririz. 

``` 
             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
          / \
         2   4 

```

* 2, 7'den küçük olduğu için sola geçer.
* 2, 5'den küçük olduğu için 5'in soluna geçer.
* 2, 1'den büyük olduğu için 1'in sağına geçer.
* 2, 3'den küçük olduğu için onu 3'ün soluna yerleştiririz.
