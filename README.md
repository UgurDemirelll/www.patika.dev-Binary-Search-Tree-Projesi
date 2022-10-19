# www.patika.dev-Binary-Search-Tree-Projesi


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.



1. aşama ###################7#######         root rakamını 7 seçtik.

2. aşama                    7          root'un soluna 5 geliyor
                           /
                          5
                          
3.aşama                     7          1, 7 den ve 5 den küçük olduğu için 5 in soluna geliyor
                           /
                          5
                         /
                        1
                        
4.aşama                     7
                           / \
                          5   8         8 7 den büyük olduğu için root'un sağına geliyor
                         /
                        1
5.aşama                     7
                           / \
                          5   8        3, 7 den ve 5 den küçük 1 den büyük olduğu için 1 in sağına geliyor
                         /
                        1
                         \
                          3
                          
6.aşama                     7
                           / \
                          5   8       6, 7 den küçük 5 ten büyük olduğu için 5 in sağına geliyor
                         / \
                        1   6 
                         \
                          3    
                          
7.aşama                     7
                           / \
                          5   8         0, 7 den 5 den ve 2 den küçük olduğu için 1 in soluna geliyor
                         / \
                        1   6 
                       / \
                      0   3                            
 
8.aşama                     7
                           / \
                          5   8
                         / \   \
                        1   6    9      9, 7 den ve 8 den büyük olduğu için 8 in sağına geliyor 
                       / \
                      0   3   
                      
8.aşama                     7
                           / \
                          5   8
                         / \   \
                        1   6    9      4, 7 den ve 5 den küçük 1 den ve 3 den büyük olduğu için 3 ün sağına geliyor
                       / \
                      0   3  
                           \
                            4
                      
9.aşama                     7
                           / \
                          5   8
                         / \   \
                        1   6    9     2, 7 den ve 5 den küçük 1 den büyük ancak 3 den küçük olduğu için 3 ün soluna geliyor
                       / \
                      0   3  
                         / \
                        2   4                     
                      
