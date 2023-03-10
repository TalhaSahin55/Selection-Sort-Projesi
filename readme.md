# Selection Sort Projesi

[patika.dev](https://patika.dev) Veri Yapıları ve Algoritmalar eğitimindeki ödev.

## [22,27,16,2,18,6] -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

> ÇÖZÜM:
>
>    [22, 27, 16, 2, 18, 6] n    (en küçük 2 en baştaki ile değiştiririz.)
> 
> [2, 27, 16, 22, 18, 6] (n-1)  (2. küçük sayıolan 6 ile 2. sıradaki sayı olan 27'yi değiştiririz.)
> 
>[2, 6, 16, 22, 18, 27] (n-2)  (3. küçük sayı olan 16'nın yeri değişmez. 4. küçük sayı olan 18 ile 4.sıradaki sayı olan 22 yer değiştirir.)
>
>[2, 6, 16, 18, 22, 27]  (1)
2. Big-O gösterimini yazınız.
> ÇÖZÜM:
>
>n+(n-1)+(n-2)+...+1=(n*(n+1))/2=((n^2)+n)/2 olur. (n^2)'yi alırız. Worst case O(n^2)
3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
* Average case: Aradığımız sayının ortada olması 
* Worst case: Aradığımız sayının sonda olması    
* Best case: Aradığımız sayının dizinin en başında olması.    
> ÇÖZÜM:
>
>Sayı ortada olduğu için Avarage case kapsamına girer.
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

> ÇÖZÜM:
>
> [2 | 3, 5, 8, 7, 9, 4, 15, 6] (n-1) 1.adım
>
> [2, 3, 4 | 8, 7, 9, 5, 15, 6] (n-2) 2.adım
>
> [2, 3, 4, 5 | 7, 9, 8, 15, 6] (n-3) 3.adım
>
> [2, 3, 4, 5, 6 | 9, 8, 15, 7] (n-4) 4.adım