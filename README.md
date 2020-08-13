# list-tuppple
Assigning  element to different list
test = [1, 4, 5, 6, 7, 3] 
  
# printing original list 
print ("The original list is : " + str(test_list)) 
  
# using list comprehension 
# to assign variables from list element 
var1, var2, var3 = [test[i] for i in (1, 3, 5)] 
  
# printing result 
print ("The variables are : " +  str(var1) + 
                           " " + str(var2) +
                            " " + str(var3)) 
Output:
The original list is : [1, 4, 5, 6, 7, 3]
The variables are : 4 6 3
