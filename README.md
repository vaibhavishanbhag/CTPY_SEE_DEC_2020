# CTPY_SEE_DEC_2020
5a)Inputs: 3
           1 2
           2 2
           8 7
           2
           3 3
           4 4
           
5b)if k in data1:
     v1=data1[k]
     if v1!=v2:
      dupkeys[k]=[v1,v2]
      del data1[k]
     else:
      data1[k]=v2
      
5c)TEST CASE 1:
  4
  1 2
  3 3 
  3 8
  4 9
  2 
  3 3
  4 4
   
   TESET CASE 2:
   4
   1 2
   2 2 
   3 3
   4 19
   2
   3 3
   4 19
   
   TEST CASE 3:
   The test case written in 5a, breaks the initially written code can be written.
   
