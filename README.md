Method1:-

nums = (1, 2, 3, 4, 5, 6, 7) 
print("Original list: ", nums)
result = map(lambda x: x + x + x, nums) 
print("\nTriple of said list numbers:")
print(list(result))
Method2:-
Num=[1,2,3,4,5,6,7]
Result= list(map(lambda x : x*3 , Num)) #to list
print(Result)
