# list-tuppple
Assigning  element to different list
test = [1, 4, 5, 6, 7, 3] 
print ("The original list is : " + str(test_list)) 
 
var1, var2, var3 = [test[i] for i in (1, 3, 5)] 
  
# printing result 
print ("The variables are : " +  str(var1) + 
                           " " + str(var2) +
                            " " + str(var3)) 
Output:
The original list is : [1, 4, 5, 6, 7, 3]
The variables are : 4 6 3




ACCESSING ELEMENT FROM THE TUPLE 
tup1 = ('physics', 'chemistry', 1997, 2000);
tup2 = (1, 2, 3, 4, 5, 6, 7 );
print "tup1[0]: ", tup1[0];
print "tup2[1:5]: ", tup2[1:5];

TUPLE out put: 

tup1[0]:  physics
tup2[1:5]:  [2, 3, 4,] 

DICTNORIRS :

dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}
del dict['Name']; # remove entry with key 'Name'
dict.clear(); # remove all entries in dict
del dict ; # delete entire dictionary
print "dict['Age']: ", dict['Age']
print "dict['School']: ", dict['School']
Output
