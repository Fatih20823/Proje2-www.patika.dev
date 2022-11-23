# Proje2-www.patika.dev

* [16,21,11,8,12,22] -> Merge Sort

1. adım diziyi ikiye böl:

16,21,11 ve 8,12,22

2. adım çıkan bu dizileri de ikiye böl:

6 ; 21,11 ; 8,12 ; 22

3. adım elde edilen parçalar 2 veya daha küçük eleman sayısına ulaştığı için dur (aksi durumda bölme işlemi devam edecekti)

4. adım her parçayı kendi içinde sırala

6 ; 11,21 ; 8,12 ; 22

5. Her bölünmüş parçayı birleştir ve birleştirirken sıraya dikkat ederek birleştir (1. ve 2. parçalar ile 3. ve 4. parçalar aynı gruptan bölünmüştü)

6,11,21 ve 8,12,22

6. adım, tek bir bütün parça olmadığı için birleştirmeye devam et

6,8,11,12,21,22

7. adım sonuçta bir bütün birleşmiş parça olduğu için dur. İşte bu sonuç dizisi ilk dizinin sıralanmış halidir.

Big-O gösterimi O(nlogn)
