# Binary-Search-Tree-Projesi
patikaProjects

##soru1
[7,5,1,8,3,6,0,9,4,2] 
dizisinin Binary-Search-Tree aşamalarını yazınız.

##cevap1

            
            
         5         
        / \
       4   6
      / \  / \
     2   3 7  8
    / \         \
    0  1          9     
     
0,1,9 leaf 

root = 5
4 <5 ise sağ taraftadır
2<3 ise 2 3 ün sağındadır
2 rakamı tekardan 0 ve 1 olmak üzere ikiye ayrılır.

6>5 ise sol taraftadır
7<8 ise 7 8 in sol tarafındadır
8 rakamı da 9 a bağlanır

binary tree de root seçimi önemlidir çünkü dallanma ne kadar iyi yapılmış olursa ona göre worst ve average case değişmektedir
Rakamlar sırasıyla soldan sağa doğru artan şekilde ve yukarıdan aşağıya doğru azalan şekilde sıralanmış olur
Bu sayede eleman ekleme ve bulmak daha kolay ve daha az zaman harcanarak yapılmış olur.

##MeltemSavaş


    
