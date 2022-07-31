# Binary-Search-Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
							
							
		Root : 4 seçelim					
#Adım 1

7>4;
        4
          \
            7
#Adım 2

5>4; 5<7
        4
          \
            7
          /
        5

#Adım 3

1<4;
        4
      /   \
     1     7
          /
        5

#Adım 4

8>4; 8>7
        4
      /   \
     1     7
          / \
        5    8

#Adım 5
3<4; 3>1     
          4
      /      \
     1        7
      \      / \
       3    5    8      
      
#Adım 6
6>4; 4<7; 6>5
          4
      /      \
     1        7
      \      / \
       3    5    8      
             \
              6

#Adım 7
0<4; 0<1;
          4
      /      \
     1        7
   /  \     /  \
  0    3   5    8      
            \
             6

#Adım 8
9>4; 9>7; 9>8
          4
      /      \
     1        7
   /  \     /  \
  0    3   5    8      
            \     \
             6      9
      
#Adım 9
2<4; 2>1; 2<3
          4
      /      \
     1        7
   /  \     /  \
  0    3   5    8      
      /     \    \
     2       6    9      
      
      
      
      
      
       4
      /      \
     1        7
   /  \     /  \
  0    3   5    8      
      /     \    \
     2       6    9
					
          
          
          
Big O Gösterimi;
O(log(n))
					
www.patika.dev
